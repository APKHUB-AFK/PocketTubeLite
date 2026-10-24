# PocketTube Lite — Android WebView starter

**Credit:** MADE BY SHEBIN (LOW_END)

This is the first native Android source project for PocketTube Lite. It loads the official YouTube mobile website (`https://m.youtube.com/`) inside an Android WebView, hides normal browser chrome, keeps HTTP/HTTPS navigation in the app, supports Back navigation, and supports HTML5 custom fullscreen views where YouTube/WebView allow them.

## Important limits
- This ZIP is **source code, not an APK**. It has not been compiled or tested on a device yet.
- Open the folder in Android Studio and build an APK (`Build > Build APK(s)`).
- Android Studio/Gradle 8.9 and JDK 17 are needed for this project setup.
- The project declares Android 4.4 (API 19) as its minimum, but modern YouTube may not work correctly on old Android System WebView versions. Android 4–17 compatibility is not guaranteed.
- YouTube can change or restrict how its site behaves inside WebView. This is a wrapper around the official website, not a recreated YouTube app and not affiliated with YouTube/Google.
- No video downloading, ad bypassing, or login/security bypasses are included.
- The existing AppDeploy website is not replaced or duplicated by this source project.

## Build
1. Install Android Studio on a computer.
2. Open this project folder.
3. Allow Gradle sync to finish.
4. Select **Build > Build APK(s)**.
5. Android Studio will show the APK output path.

For a phone-only workflow, a trusted Android build service could compile the source, but don't upload account passwords or private signing keys to an untrusted service.
