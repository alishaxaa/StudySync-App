
---

## 🚀 Features

- **Google Sign-In Authentication**: Secure login via Google OAuth
- **Session Management**: Create & join collaborative study sessions
- **Notes**: Personal note-taking with cloud sync
- **Pomodoro Timer**: Focused study with built-in timer
- **Real-time Chat**: Chat within study sessions
- **Cross-Platform**: Android, iOS, Web, Desktop

---

## 🛠️ Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (latest stable)
- [Firebase](https://firebase.google.com/) project
- [Google Cloud Console](https://console.cloud.google.com/) project for OAuth

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/ilhamlabs-ai/StudySync-App.git
    cd StudySync-App
    ```

2. **Install dependencies**
    ```bash
    flutter pub get
    ```

3. **Configure Firebase**
    - Place `google-services.json` in `android/app/`
    - Place `GoogleService-Info.plist` in `ios/Runner/`
    - Update `lib/firebase_options.dart` with your Firebase config

4. **Run the app**
    ```bash
    flutter run
    ```

---

## 📦 Project Structure

- `lib/` — Main app code
- `android/`, `ios/`, `web/`, `windows/`, `macos/` — Platform-specific code
- `.gitignore` — Protects sensitive files

---

## 🏗️ Architecture

- **Provider Pattern**: State management
- **GoRouter**: Declarative navigation & auth guards
- **Firebase**: Auth, Firestore, etc.
- **Material 3**: Modern UI

---

## 🔒 Security

Sensitive files are protected by `.gitignore`:
- Firebase API keys & configs
- OAuth secrets
- Android keystores & signing certs

**Never commit sensitive authentication files to version control.**

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---
