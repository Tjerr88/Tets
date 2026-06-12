CHOP WOOD & CARRY WATER - ANDROID/PWA

CONTENTS
- index.html: the app
- manifest.json: Android install metadata
- service-worker.js: offline support
- assets/: logo and Android icons

INSTALL ON ANDROID
1. Upload this entire folder to an HTTPS web host.
2. Open index.html through that HTTPS address in Chrome on Android.
3. Open Chrome's menu and choose "Install app" or "Add to Home screen".
4. The app then opens standalone and continues working offline after its first load.

IMPORTANT
- Opening index.html directly through file:// is fine for testing, but Android cannot
  install the PWA that way.
- Keep all files and folders together; the relative paths are required.
- Practice progress remains stored locally on the device/browser.

APK OPTION
This PWA can later be packaged as an APK/AAB with Trusted Web Activity or Capacitor.
For Play Store distribution, the app also needs an Android package ID, signing key,
store listing, privacy details and hosted HTTPS version.
