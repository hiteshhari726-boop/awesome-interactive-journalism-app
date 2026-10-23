# Awesome Interactive Journalism Android App

This project is a simple Android app that loads a curated, mobile-friendly list of interactive journalism examples from the repository content.

## Requirements
- Android Studio Ladybug or newer
- JDK 17
- Android SDK with API 34

## Open in Android Studio
1. Start Android Studio.
2. Choose `Open`.
3. Open the folder containing this project.
4. Let Gradle sync complete.
5. Connect a device or launch an emulator.
6. Click `Run`.

## Build APK
1. In Android Studio, select `Build` > `Generate Signed Bundle / APK`.
2. Choose `APK`.
3. Create a keystore if needed.
4. Build the APK.
5. The signed APK will appear in `app/release/` or the output folder shown by Android Studio.

## Project structure
- `app/src/main/java/com/example/awesomeinteractivejournalism/MainActivity.kt` — app entry point
- `app/src/main/assets/index.html` — the local interactive list view
- `app/src/main/AndroidManifest.xml` — app manifest

## Notes
This app is intentionally a lightweight WebView wrapper so the project can be built quickly and runs without a backend.
