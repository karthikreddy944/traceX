# traceX – Lost and Found App

traceX is a Flutter-based lost and found application that helps users report, search for, and reconnect with lost items. The project includes a Flutter front-end (Android, iOS, Web, Windows, Linux, macOS) along with an ML backend component for additional intelligence features.

## Features

- Report lost or found items with descriptions and images
- Browse and search reported items
- Cross-platform support via Flutter (Android, iOS, Web, Desktop)
- Firebase integration for backend services
- ML backend module for smart matching/recognition

## Tech Stack

- **Frontend:** Flutter (Dart)
- **Backend:** Firebase
- **ML Backend:** Python (see `ml_backend/`)
- **Platforms:** Android, iOS, Web, Windows, Linux, macOS

## Project Structure

```
traceX/
├── android/              # Android platform files
├── ios/                   # iOS platform files
├── web/                   # Web platform files
├── windows/ linux/ macos/ # Desktop platform files
├── lib/                   # Main Flutter app source code
├── assets/images/         # Image assets
├── ml_backend/            # ML backend service
├── test/                  # Tests
├── pubspec.yaml           # Flutter dependencies
└── firebase.json          # Firebase configuration
```

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- A configured Firebase project (add your own `google-services.json` / `GoogleService-Info.plist` and Firebase config — these are gitignored for security)

### Setup

```bash
git clone https://github.com/karthikreddy944/traceX.git
cd traceX
flutter pub get
flutter run
```

### ML Backend

```bash
cd ml_backend
pip install -r requirements.txt
python app.py
```

## Notes

- Firebase credentials and service account keys are **not** included in this repo for security reasons. You'll need to add your own configuration files to run the app.

## License

This project currently has no license specified.
