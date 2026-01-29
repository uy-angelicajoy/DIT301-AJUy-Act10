# Cross-Platform To-Do List App

## Framework Used: Flutter

This application is built using **Flutter**, Google's UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.

## Native vs Cross-Platform Development

### Native Development
- **Pros**: Maximum performance, full access to platform APIs, best user experience
- **Cons**: Separate codebases for iOS (Swift) and Android (Kotlin), doubled development time and maintenance

### Cross-Platform Development (Flutter/React Native)
- **Pros**: Single codebase for multiple platforms, faster development, consistent UI, easier maintenance
- **Cons**: Slightly larger app size, occasional platform-specific adjustments needed

**Why Flutter?**
- Hot reload for instant UI updates during development
- Rich widget library with Material Design and Cupertino styles
- Excellent performance (compiles to native ARM code)
- Strong community and Google backing

## App Features

✅ **Add Tasks**: Enter text and click "Add" button to create new tasks
✅ **Task List**: View all your tasks in a scrollable list
✅ **Remove Tasks**: Delete tasks by clicking the red delete icon
✅ **Clean UI**: Simple, intuitive single-screen interface
✅ **State Management**: Efficient task list updates using Flutter's setState

## Getting Started

### Prerequisites
- Flutter SDK (3.0.0 or higher)
- Android Studio / Xcode (for mobile development)
- VS Code or Android Studio with Flutter plugin

### Installation

1. Clone this repository
2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

### Platform-Specific Commands

**Android:**
```bash
flutter run -d android
```

**iOS:**
```bash
flutter run -d ios
```

**Web:**
```bash
flutter run -d chrome
```

## Screenshots

### How to Take Screenshots
Once the app is running, you can capture screenshots:
- **Android Emulator**: Click the camera icon in the emulator toolbar
- **Physical Device**: Use device screenshot shortcuts (Power + Volume Down)
- **Flutter DevTools**: Use the screenshot feature in Flutter DevTools

### Main Screen (Empty State)
![Empty State](screenshots/empty_state.png)
*The app shows a helpful message when no tasks exist*

### Main Screen (With Tasks)
![With Tasks](screenshots/with_tasks.png)
*Tasks displayed in a clean list with delete buttons*

### Adding a Task
![Adding Task](screenshots/adding_task.png)
*Simple text input with Add button*

## Project Structure

```
lib/
  └── main.dart          # Main application code with TodoApp and TodoListScreen
pubspec.yaml             # Flutter dependencies and configuration
README.md                # This file
```

## Key Takeaway

💡 **Cross-platform frameworks like Flutter enable faster development by sharing a single codebase across platforms.**

Flutter provides powerful tools to build consistent, maintainable mobile applications while balancing performance and productivity. With hot reload, rich widgets, and native performance, Flutter is an excellent choice for modern app development.
