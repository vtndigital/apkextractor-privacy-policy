# Privacy Policy for APK Extractor

**App name:** APK Extractor  
**Package name:** `com.apkextractor.vtn`  
**Platform:** Android 7.0 and newer  
**Effective date:** October 26, 2026  
**Last updated:** October 26, 2026

## Overview

APK Extractor copies APK files that are already installed on your Android device to a
folder you can access, and can rebuild split APKs into one installable APK. The app is
designed to work entirely on your device.

**The app does not collect, transmit, sell, or share your personal information.** It has no
internet permission, no user accounts, no advertising, no analytics, no crash reporting, and
no tracking.

## Information the app accesses

To provide its features, APK Extractor accesses the following information locally on your
device:

- **Installed app information:** app names, package names, icons, versions, APK sizes, SDK
  versions, ABIs, install/update dates, installer names, signing-certificate fingerprints,
  requested permissions, and split APK names. This is read through Android's
  `PackageManager` API so the app can show the app list and let you choose what to extract.
- **APK files:** the app reads the APK files of the app you select and copies or merges them.
  It does not read other apps' private data, accounts, messages, photos, contacts, or files.
- **Files you choose:** if you use the Files tab's file picker, the app reads only the file
  you select so it can install or inspect it.
- **App settings and file index:** your theme, filename template, sort order, merge
  preference, and a local list of files the app has saved. These are stored in Android
  `SharedPreferences` on your device.

This information is used only to display the app's interface and perform the action you
requested. It is not uploaded to a server.

## How information is stored

- Extracted APKs, merged APKs, `.apks.zip` bundles, and exported icons are saved to shared
  storage under `Downloads/APK Extractor` or `Pictures/APK Extractor`, as shown in the app.
- Temporary files used for sharing or installation are written to the app's private cache.
- App settings and the local saved-file index are stored in the app's private storage.
- The saved-file index is excluded from Android cloud backup and device-to-device transfer.
- Android may back up app preferences if you have Android backup enabled. That backup is
  controlled by your Android device and Google account settings, not by this app. You can
  disable it in Android Settings.

## Sharing and installing

- **Share:** when you tap Share, the app creates a temporary copy of the selected APK and
  opens Android's system share sheet. The file is shared only with the app you choose. The
  receiving app's own privacy policy applies to what it does with the file. APK Extractor
  does not share files automatically.
- **Install:** when you tap Install, the app opens Android's system package installer. You
  must review and confirm the installation. The app cannot install anything silently.
- **Files tab:** installing a file you picked uses the same system installer and your
  confirmation.

## Permissions

| Permission | Why the app uses it |
| --- | --- |
| `QUERY_ALL_PACKAGES` | Lists installed apps so you can choose one to extract. The list is displayed locally and is not transmitted. |
| `REQUEST_INSTALL_PACKAGES` | Opens the Android system installer for an APK or split bundle you choose. You confirm every install. |
| `WRITE_EXTERNAL_STORAGE` (Android 9 and below only) | Saves extracted files to public Downloads/Pictures on older Android versions. Android 10 and newer use MediaStore and do not need this permission. |

The app does not request internet, location, contacts, camera, microphone, SMS, call log,
calendar, health, or advertising-ID access.

## Data collection and sharing

APK Extractor does **not**:

- collect personal data;
- transmit app lists, file names, extracted APKs, settings, or device identifiers to the
  developer or any third party;
- use advertising, analytics, telemetry, crash-reporting, or tracking SDKs;
- sell, rent, or trade data;
- create user profiles;
- require an account or login.

The app uses local AndroidX/Compose libraries and local APK-processing libraries. These
libraries run on the device and do not send data anywhere.

Google Play and the Android operating system may collect diagnostic, installation, or usage
information independently under Google's own policies. That collection is outside APK
Extractor's control.

## Data retention and deletion

- Extracted APKs, bundles, and icons remain in shared storage until you delete them. You can
  delete saved files from the Files tab, or delete them with a file manager.
- You can clear the app's local settings and saved-file index by clearing the app's storage
  in Android Settings, or by uninstalling the app.
- Uninstalling the app does **not** delete extracted files in Downloads or Pictures. Delete
  those files separately if you no longer need them.
- Android backup copies of app preferences, if any, can be managed or deleted through your
  Google account's backup settings.
- Because the app has no server and does not collect data, there is no server-side data to
  request or delete.

## Security

APK Extractor processes files locally and does not send data over a network. App-private
settings and cache are protected by Android's app sandbox. Files you export to Downloads or
Pictures are in shared storage and may be accessible to other apps or people with access to
your device. Share extracted APKs only with people you trust.

Extracted APKs may contain third-party code and may be signed by the original app publisher
or, for merged APKs, by APK Extractor's public export key. Only extract and install apps you
have the legal right to copy or use.

## Children's privacy

APK Extractor is not directed to children under 13 and does not knowingly collect personal
information from children. The app does not collect personal information from any user.

## Third-party links and services

The app does not contain third-party advertising, analytics, or tracking services. If you
open a link to an external website or use a third-party app through Android's share sheet,
that service's privacy policy applies.

## Changes to this policy

This policy may be updated if the app's features or legal requirements change. The updated
version will show a new effective date. Continued use of the app after an update means you
accept the revised policy.

## Contact

For privacy questions, use the developer contact email shown on the APK Extractor listing in
Google Play (package `com.apkextractor.vtn`). Please include "Privacy" in the subject line.

## Legal notice

APK Extractor is a local file-management tool. It does not grant you any rights to apps or
APK files. Extract and share only apps you are entitled to copy, and comply with the app
publisher's terms and applicable copyright law.
