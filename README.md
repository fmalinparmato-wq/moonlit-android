# Moonlit Android WebView App

A simple Android wrapper for https://moonlit-begonia-c36a3b.netlify.app.

## Build locally
- Open this folder in Android Studio (recent version with Android SDK 35 support).
- Allow Gradle sync/downloads.
- Select **Build > Build APK(s)** or run `gradle assembleDebug`.
- APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## Build APK via GitHub Actions
- Create a GitHub repository and upload/push this project to the `main` branch.
- In the repository, open **Actions** and run **Build Android APK** (workflow_dispatch) if not automatically triggered.
- Download the artifact named `Moonlit-Android-APK` from the completed workflow.
- Install the APK on Android. For sideloading, Android may ask to allow installation from that source.

This project uses a WebView. The target website must be reachable from the device and permit embedding in WebView.
