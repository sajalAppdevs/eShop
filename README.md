# eShop - Flutter E-commerce Application

## Overview
eShop is a modern e-commerce mobile application built using Flutter framework. The application supports multiple platforms including Android, iOS, Web, Windows, Linux, and macOS, providing a seamless shopping experience across different devices.

## Features
- Cross-platform compatibility (Android, iOS, Web, Windows, Linux, macOS)
- Material Design implementation
- Responsive UI layout
- Platform-specific optimizations

## Technical Specifications
- **Flutter Version**: Using stable channel
- **Minimum SDK Versions**:
  - iOS: 9.0+
  - Android: As specified in Flutter's minSdkVersion
- **Package Name**: com.example.emart_app
- **Supported Orientations**: Portrait primary

## Getting Started

### Prerequisites
1. Flutter SDK (stable channel)
2. Android Studio / VS Code
3. Git

### Installation
1. Clone the repository
2. Navigate to project directory
3. Run the following commands:
```bash
flutter pub get
flutter run
```

### Building for Different Platforms
- **Android**: `flutter build apk`
- **iOS**: `flutter build ios`
- **Web**: `flutter build web`
- **Windows**: `flutter build windows`
- **Linux**: `flutter build linux`
- **macOS**: `flutter build macos`

## Development Resources

For developers new to Flutter, here are some helpful resources:

- [Flutter Documentation](https://docs.flutter.dev/)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Flutter API Reference](https://docs.flutter.dev/)

## Project Structure
The project follows standard Flutter project structure with platform-specific configurations in their respective directories:
- `/android` - Android-specific configurations
- `/ios` - iOS-specific configurations
- `/web` - Web platform configurations
- `/windows` - Windows platform configurations
- `/linux` - Linux platform configurations
- `/macos` - macOS platform configurations
- `/lib` - Main Flutter source code

## License
This project is licensed under standard copyright laws. All rights reserved.

## Contact
For any queries or support, please create an issue in the project repository.
