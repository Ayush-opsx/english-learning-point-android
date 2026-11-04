# English LEARNING point — Android build

This repository packages the HTML app in `www/index.html` with Capacitor 7.

## Build the APK on GitHub (no computer required)

1. Create a **new empty GitHub repository**.
2. Extract this ZIP on your phone.
3. Upload the **contents** of this folder to the repository root. Keep the `.github/workflows/build-android.yml` path intact. Do not upload only the ZIP.
4. Open the repository's **Actions** tab.
5. Select **Build Android APK** and tap **Run workflow**. A push to `main` also starts a build.
6. When the run succeeds, open the run and download the artifact named `English-LEARNING-point-APK`.
7. Extract the downloaded artifact ZIP; it contains `app-debug.apk`.

This produces a debug APK for testing, not a Play Store release. The current app's local browser storage does not provide cross-device data syncing; add a secure backend before relying on it across teacher/student phones. Change the initial admin password before real use.
