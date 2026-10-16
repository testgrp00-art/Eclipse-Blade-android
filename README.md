# Eclipse Blade

Android game (Java + WebView) by Nitai Studio. Package: `com.nitaistudio.eclipseblade`

Paid, fully offline, ad-free. No ad SDKs, no tracking, no internet permission.

## Build (GitHub Actions)
Push to GitHub -> Actions -> "Android Build" -> download:
- `EclipseBlade-debug-apk`   (install on phone for testing)
- `EclipseBlade-aab-unsigned` (Play Console: let Google Play App Signing sign it, or sign it yourself)

## Project layout
- `app/src/main/assets/index.html` + `assets/img/` - the game
- `app/src/main/java/.../MainActivity.java` - WebView host
- `store/icon-512.png` - Play Store icon
- `PRIVACY_POLICY.md` - publish this text on a public URL for the Play Console
