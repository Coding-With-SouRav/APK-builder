Build the APK
1. Install Android Studio and open this folder (ChessApp).
2. Let Gradle sync finish.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK appears at app/build/outputs/apk/debug/app-debug.apk
Command line (with Android SDK installed): ./gradlew assembleDebug

No Android Studio? Use GitHub:
1. Create a free GitHub repo and upload ALL files in this folder (keep the .github folder).
2. Open the repo's Actions tab, wait for "Build APK" to finish.
3. Open the finished run and download the "chess-apk" artifact (zip containing app-debug.apk).
