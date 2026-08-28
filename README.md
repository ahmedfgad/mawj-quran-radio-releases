# Mawj Quran Radio — موج

A calm Quran radio for listening to live recitations and Islamic programmes,
without accounts or in-app advertising.

This public repository hosts **application downloads only**. The application
source code is private. Download published builds from
[Releases](../../releases/latest).

## Download

Android is Mawj's primary published platform. Builds for the other supported
platforms are distributed here when they are available.

| Platform | Expected file | Notes |
|---|---|---|
| **Windows** | `Mawj-<version>-windows-x64.zip` | 64-bit. Extract the archive and run `Mawj.exe`. |
| **Linux** | `Mawj-<version>-linux-x86_64.zip` | 64-bit. Extract the complete app folder before running it. |
| **macOS** | `Mawj-<version>-macos-arm64.zip` | Apple Silicon build unless a release says otherwise. |
| **iOS** | `Mawj-<version>-ios-unsigned.ipa` | Unsigned developer/sideloading build when provided. |
| **Android** | `Mawj-<version>-android.apk` | Universal debug-signed sideload package; the official Google Play version is preferred. |

Only files actually attached to a GitHub release are available. A platform
listed in the table may not have a build in every release.

## Installing

### Windows

Extract the zip and run `Mawj/Mawj.exe`. Keep the bundled `_internal` folder
next to the executable. An unsigned build may trigger
Windows SmartScreen; review the downloaded file and release notes before
choosing **More info → Run anyway**.

### Linux

```bash
unzip Mawj-<version>-linux-x86_64.zip
chmod +x Mawj/Mawj
./Mawj/Mawj
```

Keep the bundled `_internal` folder beside the executable. Linux builds are
produced on Ubuntu for x86-64 and require a reasonably recent glibc.

### macOS

Unzip the archive and move `Mawj.app` to Applications. If the release is not
notarized, use **right-click → Open** for the first launch or follow the exact
instructions in that release.

### iOS

An unsigned `.ipa` cannot be installed by tapping it on a stock iPhone. It must
be signed with your Apple ID using a sideloading/development workflow. Each
release will state its supported devices and signing limitations.

### Android

Use Mawj's official Android publishing channel when available. If an APK is
attached here, Android may require you to allow installation from the browser or
file manager used to open it.

## Network and privacy

Mawj streams radio audio from third-party radio providers, so listening requires
an internet connection. Settings, favorites, listening history, and recordings
are stored privately on the device. Radio and content providers receive normal
connection data.

## Issues

Please report download or installation problems in this repository's
[Issues](../../issues).

## License

Copyright (c) 2026 Ahmed F. Gad. All rights reserved.

Application binaries are distributed for personal use. The source code is not
public.
