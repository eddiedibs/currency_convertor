# currency_convertor

A Flutter mobile app for converting amounts between currencies.

> **Status:** early development. The project is scaffolded and builds for Android; the conversion features are not implemented yet.

## Tech stack

| | |
|---|---|
| Framework | [Flutter](https://flutter.dev) 3.47 (stable) |
| Language | Dart 3.13 |
| Platforms | Android, iOS |
| Package ID | `dev.edd1e.currency_convertor` |
| Linting | [`flutter_lints`](https://pub.dev/packages/flutter_lints) |

## Prerequisites

- Flutter SDK 3.47 or newer ([install guide](https://docs.flutter.dev/get-started/install))
- Android SDK (platform-tools, API 36) and JDK 17+ for Android builds
- Xcode on macOS for iOS builds (iOS can't be built on Linux or Windows)

Run `flutter doctor` to check your setup.

## Getting started

```bash
git clone git@github.com:eddiedibs/currency_convertor.git
cd currency_convertor
flutter pub get
flutter run            # runs on a connected device or emulator
```

To run on a physical Android phone, turn on **Developer options → USB debugging**, connect the phone over USB, and check that `flutter devices` lists it.

## Development

| Task | Command |
|---|---|
| Run with hot reload | `flutter run` (press `r` to reload, `R` to restart) |
| Static analysis | `flutter analyze` |
| Tests | `flutter test` |
| Debug APK | `flutter build apk --debug` |
| Release APK | `flutter build apk --release` |

## Project structure

```
lib/          Dart source code (entry point: lib/main.dart)
test/         Widget and unit tests
android/      Android host project (Gradle, Kotlin)
ios/          iOS host project (Xcode)
pubspec.yaml  Dependencies and app metadata
```
