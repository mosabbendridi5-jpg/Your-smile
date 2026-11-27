# Smart Smile Scanner — Android project

Android application wrapper for the Smart Smile Scanner by MOSSAAB Media.

- Opens the bundled app UI inside an Android WebView (no external browser chrome).
- Uses an app-assets HTTPS origin so camera APIs can work in supported Android WebView versions.
- Includes camera permission handling and image file picker.
- Requires internet for the current MediaPipe vision library/model loaded by the HTML.

## Build an APK
1. Open this folder in Android Studio (Giraffe or newer recommended).
2. Allow Gradle sync and install Android SDK Platform 35 if prompted.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Android Studio will show the generated APK path, usually `app/build/outputs/apk/debug/app-debug.apk`.

Package: `com.mossaabmedia.smartsmilescanner`
App name: `Smart Smile Scanner`
Developer label: `MOSSAAB Media`
