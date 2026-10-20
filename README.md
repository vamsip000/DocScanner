# Doc Scanner (ML Kit)
Build locally: install JDK 17 + Android Studio, open this folder, Build > Build APK(s).
Or CLI: gradle wrapper --gradle-version 8.7 && ./gradlew assembleDebug
Output: app/build/outputs/apk/debug/app-debug.apk
No Android Studio? Push this folder to a GitHub repo; the Actions workflow builds the APK
(Actions tab > Build APK > Artifacts). Needs Google Play Services on the device.
