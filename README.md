# Nexora Manager Downloaders

Downloader plugins for Nexora Manager.

This repository is an independently maintained fork of the GPL-3.0 licensed ReVanced Manager Downloaders project. Nexora is not affiliated with or endorsed by ReVanced.

## Current status

The active downloader is:

- **APKMirror Downloader** — opens APKMirror and lets the user select the APK/APKM normally; APKM bundles can be merged into a standard APK.

The Play Store downloader remains disabled because its login flow is currently broken upstream as well.

## Compatibility

The application package is `com.nexora.manager.downloaders`.

For compatibility with the current Nexora Manager downloader host, this project temporarily compiles against the legacy host API package `app.revanced.manager.downloader.*`. That compatibility layer will be migrated separately; it is not presented as a Nexora-owned API.

## Building

Requirements:

- JDK 17
- Git
- GitHub Packages read access for the temporary legacy Manager API dependency

Build with:

```bash
./gradlew assembleRelease
```

The output is written as `nexora-manager-downloaders-<version>.apk`.

## Licence and provenance

This project remains licensed under GPL-3.0. The upstream history and `CHANGELOG.md` are intentionally preserved for attribution and provenance.

Upstream source: `ReVanced/revanced-manager-downloaders`.
