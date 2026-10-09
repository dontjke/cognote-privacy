---
title: Cognote Privacy Policy
lang: en
---

# Cognote Privacy Policy

[中文](../zh/) · **English** · [Русский](../ru/)

- **Effective:** October 9, 2026 (app version 3.4.0)
- **Developer:** Roman Stepanov
- **Contact:** cognote03042026@yandex.ru
- **App:** Cognote, `com.stepanov.cognote`

## In short

Cognote is a notes app that keeps everything **only on your device**. It has
no accounts, no servers of its own, no ads and no analytics. The developer
never receives your notes or any personal data.

## What data is processed and where

Notes, attachments (photos, files, videos, audio recordings, drawings),
reminders and settings are stored on the device, in the app's private storage.
Other apps cannot access this storage. This data is not sent to the developer
or to any third party.

## Permissions and why they are needed

| Permission | Purpose |
|---|---|
| Microphone (`RECORD_AUDIO`) | Recording audio notes — saved inside the note on your device. Voice typing and voice search — speech is recognized on the device, is not stored and is not sent anywhere. Used only after you tap the corresponding button. |
| Internet (`INTERNET`, `ACCESS_NETWORK_STATE`) | Only to download the speech recognition language model once (about 45 MB), the first time you use transcription or voice typing. |
| Notifications, exact alarms, start after reboot (`POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `RECEIVE_BOOT_COMPLETED`, `VIBRATE`, `WAKE_LOCK`) | Note reminders, including after the phone restarts. |
| Background work (`FOREGROUND_SERVICE`) | Required by the system background-work library: updating the widget and reminders. |
| Biometrics (`USE_BIOMETRIC`, `USE_FINGERPRINT`) | Opening locked notes. Your fingerprint or face is verified by Android; the app never receives biometric data. |

The app does not request special storage permissions: you pick photos and
files in the system picker, and the app gets access only to what you picked.

## Internet connection

The language model is downloaded from the Vosk project site (`alphacephei.com`)
or its mirror on `huggingface.co`. The app **sends none of your data**: the
server only sees the technical details of the request, as with any file
download (such as your IP address), handled under those sites' own policies.
The app makes no other network requests.

## When data leaves the device

Only when you do it:

- Share and export to PDF or Markdown — the note goes to the app you choose;
- Backup — the archive is saved where you choose.

If system backup is enabled on the device (for example, Google or Huawei),
the system may store notes in the cloud backup of **your** account. This is
controlled by the device settings. Audio recordings and language models are
not included in the cloud backup.

## Security

A lock hides the note's content in the list, search, notifications and when
sharing; the note opens only after biometric verification. The app does not
apply its own encryption to note content — data is protected by the system:
the app's storage is not accessible to other apps.

## Deleting data

You can delete notes in the app; the trash is emptied manually. Uninstalling
the app deletes all of its data from the device.

## Children

The app is not specifically directed at children and collects no personal
data from anyone.

## Changes to this policy

A new version is published at this address with a new date. Significant
changes will be mentioned in the update notes.

## Contact

Privacy questions: **cognote03042026@yandex.ru**
