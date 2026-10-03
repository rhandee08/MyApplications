PHOENIX TEAMS - ANDROID APP PROJECT

The APK builds automatically on GitHub. See the steps in chat. (Manual option below.)

Manual build (Android Studio):
1. Install Android Studio (free): https://developer.android.com/studio
2. Unzip this folder.
3. In Android Studio: File > Open, then pick the "android" folder inside.
4. Wait for "Gradle sync" to finish (first time downloads files).
5. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Click "locate" in the pop-up. The file is app-debug.apk.
7. Send app-debug.apk to your phone (USB, email, Drive).
8. On the phone, open it and allow "install from this source".

Or plug in your phone (USB debugging on) and press the green Run button.

To change the app later: edit www/index.html, then run:  npx cap sync android
