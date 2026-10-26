# என்எழுத்து (En Ezhuthu) - Native Android Jetpack Compose App

Complete bilingual social writing application for Tamil and English authors.

## 📱 How to Build on an Android Phone (மொபைல் வழிகாட்டி)

### Option 1: GitHub Actions (No PC needed - Free Cloud APK build)
1. Create a repository on [github.com](https://github.com) named `EnEzhuthu-Android`.
2. Extract this ZIP file and upload the files to your repository.
3. GitHub Actions will automatically compile and provide the `app-release.apk` under the **Actions** tab.

### Option 2: Termux / AIDE directly on Phone
1. In Termux: `pkg update && pkg install openjdk-17 gradle -y`
2. Run: `./gradlew assembleDebug`
3. Output APK: `app/build/outputs/apk/debug/app-debug.apk`

## 💻 Building with Android Studio
1. Open Android Studio -> Open -> Select this project directory.
2. Put your Firebase `google-services.json` into `app/` folder (Project: `ascendant-voyage-301dl`).
3. Press Run (Shift + F10).
