# Atronic Speed releases

- `AtronicSpeed-<version>.apk`: the current signed build. Install it on the phone, or let the app update itself.
- `version.json`: the update feed the app checks when it opens (`versionCode`, `versionName`, `apkUrl`, `notes`).

To publish: build from https://github.com/Skisfa99/Atronic-Speed with the same signing key, replace the APK here, update `version.json`, and push to `main`.
