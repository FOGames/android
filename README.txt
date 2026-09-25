FO.Games Android WebView
========================

This project builds a native Android WebView APK for:
https://fogames.github.io/FO.Games/

The website remains online; the Android app opens it inside the app's WebView.
Network requests made by the WebView run under the app process/UID, so Android
normally accounts the app's network usage as app data usage. Exact reporting can
vary by Android version and system settings.

Build on GitHub:
1. Upload the contents of this folder to the GitHub repository.
2. Commit the changes.
3. Open Actions -> Build FO.Games APK.
4. Open the successful run.
5. Download the FOGames-APK artifact.
6. Extract it and install app-debug.apk on Android.
