# ZIVO AI — Free Offline Starter

This project creates an Android app named ZIVO AI.

## Honest capability note
This build is an offline starter assistant with simple built-in responses. It does not include a large language model and is not equivalent to ChatGPT. It uses no Gemini/OpenAI account, API key, backend, or paid service. Voice recognition uses the Android speech-recognition service available on the device and may depend on installed speech services.

## Build an APK
1. Extract this ZIP.
2. Open the extracted `ZivoAI` folder in Android Studio.
3. Allow Gradle sync to finish (internet is needed once to download build dependencies).
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the APK at `app/build/outputs/apk/debug/app-debug.apk`.

## Build without Android Studio
1. Create a GitHub repository and upload the contents of this folder.
2. Open the repository's Actions tab.
3. Run `Build ZIVO AI APK` (or push to main).
4. Download the `ZIVO-AI-debug-APK` artifact from the completed workflow.

## Install on Redmi Y3
Transfer the APK to the phone, open it, and allow installation from that file manager if Android asks. Only install APKs you built or trust.

Package: `com.zivo.ai`
Minimum Android: API 23 (Android 6.0)
