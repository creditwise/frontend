# Development

This approach is for development integrated with Android Studios
### Setting up IDE
### Requirements
- [Android Studio](https://developer.android.com/studio/install?hl=zh-tw#mac)
- [flutter](https://docs.flutter.dev/get-started/install)
  - [bind to bin](https://docs.flutter.dev/get-started/install/macos/mobile-android#add-flutter-to-your-path≠)
    diagnose using `$ flutter doctor --android-licenses`
  - The important ones are:
    - [✓] Flutter (Channel stable, 3.27.1, on macOS 15.1.1 24B2091 darwin-arm64, locale zh-Hant-SG)
      [✓] Android toolchain - develop for Android devices (Android SDK version 34.0.0)
      [✓] Android Studio (version 2024.2)
      [✓] Connected device (3 available)
      [✓] Network resources
  - some config fixes
    ```
    flutter config --android-studio-dir="<YOUR_DIR>"
    flutter config --android-sdk="<YOUR_DIR>"
    ```