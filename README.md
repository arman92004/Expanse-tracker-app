# Private Expense Tracker — Android APK

This Android project wraps the offline expense-tracker web UI inside a local Android WebView.

## GitHub Actions build
1. Create a GitHub repository.
2. Upload this entire project.
3. Open the repository's **Actions** tab.
4. Select **Build APK** and run it, or push to `main`.
5. Open the completed workflow run.
6. Download the `private-expense-tracker-apk` artifact.
7. Extract it and install `app-debug.apk` on Android.

GitHub Actions performs the Gradle build in the cloud. The APK is a debug build intended for personal installation/testing.

## Local data
Expense data is stored in the WebView's local browser storage/IndexedDB. The app does not contain a cloud backend or account system.

## Important
This version does not yet implement encrypted backups or biometric/PIN locking. Those can be added in a later version.
