# Posts App | Flutter

A modern Flutter application designed to provide a seamless posts browsing experience with **offline accessibility, local data persistence, and favorites management**.

Built with Flutter and Dart, the application integrates with a REST API to retrieve posts while ensuring users can access previously loaded content even without an internet connection.

---

## Core Features

- **Dynamic Posts Feed:** Retrieve and display posts from an online REST API.
- **Local Data Caching:** Store retrieved posts locally using Hive for reliable offline access.
- **Favorites System:** Easily add or remove posts from your personal favorites list.
- **Persistent Storage:** Retain posts and favorite selections across application restarts.
- **Offline Accessibility:** Browse cached posts and saved favorites without an active internet connection.

## Tech Stack

|    Technology     |               Purpose                  |
|-------------------|----------------------------------------|
| Flutter           | Cross-platform application development |
| Dart              | Application programming language       |
| Hive              | Lightweight local NoSQL database       |
| Hive Flutter      | Hive integration with Flutter          |
| HTTP              | REST API communication                 |
| Connectivity Plus | Network connectivity detection         |

## Project Architecture

The application follows a modular structure, separating data models, UI screens, and business logic into dedicated directories.

```text
lib/
├── models/
│   └── post_model.dart
│
├── screens/
│   ├── posts_screen.dart
│   └── favorites_screen.dart
│
├── services/
│   ├── post_service.dart
│   └── favorites_service.dart
│
└── main.dart
```

## Getting Started

### Prerequisites

Make sure the following tools are installed:

- Flutter SDK
- Dart SDK
- Visual Studio Code or Android Studio

### Installation & Setup

**1. Clone the repository**

```bash
Download zip file from https://github.com/ahmed0xmagdy/hive_posts_app/archive/refs/heads/main.zip then unzip it
```

**2. Navigate to the project directory**

```bash
cd posts_app
```

**3. Install project dependencies**

```bash
flutter pub get
```

**4. Launch the application**

```bash
flutter run
```

## Testing
To validate the project and run its automated tests, execute:

```bash
flutter analyze
```
