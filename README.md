# 🚀 Task Flow (Code Todo)

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)](https://firebase.google.com)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com)

**Task Flow** is a high-performance, gamified task management application designed specifically for software developers. It bridges the gap between generic todo apps and developer workflows by integrating code snippets, Git context, and a GitHub-style contribution system.

---

## ✨ Key Features

### 💻 Developer Workflow
- **Code-Centric Tasks**: Attach code snippets with syntax highlighting (Dart, JS, Python, etc.) directly to your tasks.
- **Git Integration**: Link tasks to specific Git branches, commit hashes, or GitHub Issues.
- **Task Templates**: Create reusable task templates for common development patterns (e.g., "Feature Implementation", "Bug Fix", "Refactor").

### 🎮 Gamification (RPG Style)
- **XP & Levels**: Earn Experience Points for every completed task and level up your developer profile.
- **Achievements**: Unlock specialized badges like "Code Master", "Night Owl", and "Hello World".
- **Streaks**: Maintain your focus with a daily productivity streak system.

### 📊 Intelligent Analytics
- **Contribution Graph**: A GitHub-style heat map visualizing your activity over the year.
- **Productivity Trends**: Detailed charts showing completion rates, category distributions, and velocity.
- **AI Smart Assistant**: Natural language processing for task categorization and due date parsing.

### 🛡️ Core & Social
- **Focus Mode**: A dedicated mode to minimize distractions and track deep work sessions.
- **Teams & Social**: Collaborate with other developers, share achievements, and compete on leaderboards.
- **Cross-Platform**: Built with Flutter for a consistent experience on macOS, iOS, Android, and Windows.

---

## 🛠️ Technology Stack

| Component | Technology |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **State Management** | Provider |
| **Database** | Hive (Local) & Cloud Firestore (Sync) |
| **Authentication** | Firebase Auth |
| **Styling** | Custom "Liquid Glass" Theme |
| **Charts** | Syncfusion Charts & FL Chart |
| **Highlights** | Flutter Highlight (Syntax Highlighting) |

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (>= 3.10.0)
- Firebase Account (for auth/sync)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/task-flow.git
   cd task-flow
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Place your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS/macOS) in the respective directories.
   - Run `flutterfire configure` if you have the CLI installed.

4. **Run the app**
   ```bash
   flutter run
   ```

---

## 📖 Deeper Documentation

For more detailed information, check out our technical guides:

- [📁 Architecture Overview](docs/ARCHITECTURE.md) - Deep dive into models, providers, and services.
- [📁 Features Guide](docs/FEATURES_GUIDE.md) - Detailed breakdown of every feature.
- [📁 Local Storage](docs/STORAGE.md) - Understanding Hive boxes and persistence.
- [📁 Contributing](CONTRIBUTING.md) - How to help us build the future of developer tools.

---

## 🎨 Design Philosophy
Task Flow uses a unique **"Liquid Glass"** aesthetic, combining blurred surfaces with vibrant animated gradients to create a premium, modern feel that mirrors high-end macOS applications.

---

*Built with ❤️ for developers by [Omar Tolba](https://github.com/omartolba)*
# taskflow-app-code
