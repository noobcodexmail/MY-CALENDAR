# MY-CALENDAR
Ultimate Calendar App for All. 

# Cosmic Calendar 2027

**Android application ยท Version 3.7**

Cosmic Calendar is a dark, cosmic-themed calendar application for viewing dates, organising personal events, reviewing notable dates and exploring date-based visual effects.

> **Android details supplied by the publisher:** package name `com.dnkwebappsstudio.mycalendar`; no Android app permissions are requested; core operation works offline; user data is stored locally on the device only. The exact minimum Android release still needs confirmation.

## Overview

The app presents a mobile-first calendar covering **1 January 2026 through 31 December 2027**. Its interface uses a dark purple/blue cosmic visual theme, animated backgrounds, date transitions and optional event effects.

The Android application version supplied by the publisher is **v3.7**. The original HTML reference file displays **MY CALENDAR - 2027 (v.3.1 Beta)**; that older source-file label is not used as the Android APK version. The repository title used here is **Cosmic Calendar 2027**.

## Main features

- Calendar navigation across January 2026 to December 2027.
- Month navigation, month selection/jump and a Today shortcut.
- Event creation, editing and deletion.
- Event categories: Holiday, Birthday, Personal, Work and Other.
- Event colour selection, custom colours and notes.
- Search by event title or note.
- Highlights and an Omens section.
- Optional date-specific visual effects.
- Settings for week-start preference and text-size controls.
- JSON event backup and restore.
- Sample holiday restoration and event-data reset controls.

See [Features](docs/FEATURES.md) and the [User Guide](docs/USER_GUIDE.md).

## Android installation

1. Download the APK from the repository's **Releases** page.
2. Open the downloaded APK on your Android device.
3. If Android asks, allow installation from the app or browser used to download the APK. This is an Android installation-source setting, not an app permission requested by Cosmic Calendar.
4. Review the installation prompt and install.
5. Launch Cosmic Calendar from your app drawer.

Only install APK files obtained from a source you trust. See [Android Installation](docs/INSTALLATION.md).

## Download

Publish the APK as an asset attached to a GitHub Release. The actual signed APK must be added separately; it is not included in this documentation archive.

Suggested release asset name: `Cosmic-Calendar-2027-v3.7.apk`

## Repository layout

```text
Cosmic-Calendar-2027/
โ”โ”€โ”€ README.md
โ”โ”€โ”€ LICENSE
โ”โ”€โ”€ CHANGELOG.md
โ”โ”€โ”€ SECURITY.md
โ”โ”€โ”€ CONTRIBUTING.md
โ”โ”€โ”€ docs/
โ”   โ”โ”€โ”€ APP_METADATA.md
โ”   โ”โ”€โ”€ FEATURES.md
โ”   โ”โ”€โ”€ INSTALLATION.md
โ”   โ”โ”€โ”€ USER_GUIDE.md
โ”   โ”โ”€โ”€ FAQ.md
โ”   โ”โ”€โ”€ PRIVACY_POLICY.md
โ”   โ”โ”€โ”€ TERMS_OF_USE.md
โ”   โ”โ”€โ”€ CREDITS.md
โ”   โ”โ”€โ”€ SUPPORT.md
โ”   โ”โ”€โ”€ ANDROID_RELEASE_CHECKLIST.md
โ”   โ””โ”€โ”€ PUBLISHING_NOTES.md
โ”โ”€โ”€ assets/
โ”   โ””โ”€โ”€ screenshots/
โ””โ”€โ”€ releases/
```

## App information

| Item | Information |
|---|---|
| Public-facing project name | Cosmic Calendar 2027 |
| In-app footer name | MY CALENDAR - 2027 |
| Documented Android app version | 3.7 (publisher-provided; verify APK metadata) |
| Calendar coverage | 2026-01-01 to 2027-12-31 |
| Platform | Android APK |
| Package name | `com.dnkwebappsstudio.mycalendar` |
| App permissions | None requested, according to the publisher |
| Internet requirement | Not required for core app operation |
| Data storage | Local device storage only, according to the publisher |
| Minimum Android version | Exact release pending confirmation |
| Developer/brand shown in app | DNK WEBAPPS STUDIO |
| Copyright notice shown in app | ยฉ 2026, DNK WEBAPPS STUDIO, All Rights Reserved. |

The Android app version, package name and behaviour above are publisher-provided specifications. The exact minimum Android release, target SDK, version code and signing details remain to be confirmed. See [App Metadata](docs/APP_METADATA.md).

## Offline operation and privacy

According to the publisher, the app works offline, requests no Android app permissions and stores user data locally on the device only. No account or cloud synchronisation is described.

The supplied interface implementation uses browser-style local storage with the key `cosmic-cal-v3` for event and preference data. The app also includes JSON backup and restore. Backup files remain under the user's control and may contain personal event details.

The interface references Google Fonts and includes external website links. These external resources are not required for core offline calendar operation. Online fonts or external pages may be unavailable while offline, and fallback fonts may be used.

Read the [Privacy Policy](docs/PRIVACY_POLICY.md) before publication.

## Credits and links

- Developer/brand: DNK WEBAPPS STUDIO
- Website: https://dnkwebappsstudio.oneapp.dev/
- Certificate link shown in the app: https://drive.google.com/file/d/14-z2IPDE-O5llVfh8BT02oLu1yVYYkpF/view?usp=drivesdk
- Fonts referenced by the supplied interface: Rajdhani and Titillium Web, loaded from Google Fonts.

## Publishing notice

The package name, no-permission behaviour, offline operation and local-only data storage are publisher-provided specifications. Before release, verify the APK signature, version code/name, SDK levels, manifest, app icon, installation, backup/restore and compatibility on the stated minimum Android release.

See [Android Release Checklist](docs/ANDROID_RELEASE_CHECKLIST.md).
