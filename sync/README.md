# Atronic Sync releases

Atronic Sync (Android) is Atronic's rebrand of SMBSync2 2.55 (MIT). Source code: https://github.com/Skisfa99/Atronic-Sync

## Builds

| Version | versionCode | File | Notes |
|---|---|---|---|
| 3.0 (current) | 3000 | `apk/3.0/AtronicSync3.0.apk` | Atronic Books theme, share fallback for updates, new app id `com.atronicsystems.atronicsync` |
| 2.1 | 2001 | `apk/2.1/AtronicSync2.1.apk` | Adds menu > Install Updates |
| 1.3 | 289 | `apk/1.3/AtronicSync1.3.apk` | |
| 1.2 | 288 | `apk/1.2/AtronicSync1.2.apk` | |
| 2.55 rebrands | 287 | `apk/legacy/` | First Atronic SMBsync / Atronic Sync builds of SMBSync2 2.55 |

versionCode = 1000 x revision + update (3.1 will be 3001).

## Other files

- `version.json`: current version, in the same format as the other apps here.

To publish a new build: add `apk/<X.Y>/AtronicSync<X.Y>.apk`, update `version.json` and the table above, and push to `main`.
