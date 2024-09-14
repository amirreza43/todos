# Flutter To-do Application

A lightweight Flutter application for managing tasks, using Hive for local storage. The app provides a simple interface for adding, editing, and deleting to-do items with swipeable actions.

## Features

- **Task Management**: Add, update, and delete to-do items.
- **Swipe Actions**: Swipe on tasks for easy deletion.
- **Local Persistence**: Uses Hive for storing tasks locally on the device.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK (included with Flutter)
- Android Studio or Xcode for device simulation

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/flutter-todos.git
    cd flutter-todos
    ```

2. Fetch dependencies:
    ```bash
    flutter pub get
    ```

3. Run the app:
    ```bash
    flutter run
    ```

## Dependencies

- **flutter**: Core SDK for building the app.
- **hive & hive_flutter**: Local storage solution for persisting to-do items.
- **flutter_slidable**: Provides swipeable task tiles for actions like delete.
- **cupertino_icons**: iOS-style icons.
