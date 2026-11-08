# WaterExperiment — Privacy Policy

**Effective Date:** 2026-05-17
**Last Updated:** 2026-11-08
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

WaterExperiment is a daily ritual app for Android. Everything you write stays on your device. Sudarshan Tech Labs operates no backend server, collects no personal data, and receives nothing from the App — not even crash reports.

The App contains no networking code at all. It does not request the `INTERNET` permission, so it is incapable of sending your data anywhere.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Your daily intention text, and whether you spoke or wrote it | The core ritual record for each day | Room database on your device |
| Glasses of water logged per day | Tracking against your daily goal | Room database on your device |
| Affirmations, including any you write yourself, and their category | The affirmation library you choose from | Room database on your device |
| Reminder time and whether reminders are enabled | Scheduling your daily notification | Room database on your device |
| Your daily water goal, selected category, theme, and onboarding state | App settings | Room database on your device |

**Nothing is collected by us.** There is no account, no sign-in, no identifier, no analytics and no advertising.

---

## How We Use Your Data

We do not use your data, because we never receive it. Everything the App stores is read only by the App, on your device, to show you your ritual history, your water log and your reminders.

---

## Data Storage and Security

- **All data is stored locally** in a Room database inside the App's private directory
- **No transmission is possible:** the App declares no `INTERNET` permission and contains no HTTP client, no Firebase, and no analytics or crash-reporting SDK
- **Android sandbox:** the database sits in app-private storage, isolated from other apps by Android

## Data Retention

| Data | Retention |
|---|---|
| All local app data | Until you delete it or uninstall the App |

---

## Data Sharing

Nothing is shared. We do not sell user data, and your intentions never leave your device. There are no third-party SDKs in this App.

---

## Background Behaviour

WaterExperiment schedules a daily reminder notification using Android's WorkManager. This runs on your device only and sends nothing outward. After a device reboot, WorkManager re-registers that reminder so your notification keeps arriving — that is the sole purpose of the `RECEIVE_BOOT_COMPLETED` permission.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `POST_NOTIFICATIONS` | Show your daily ritual reminder |
| `RECEIVE_BOOT_COMPLETED` | Re-schedule your reminder after the device restarts |

These are the only two permissions the App declares.

### No microphone access

The ritual offers a "speak" option, which means you say your intention aloud yourself. **The App does not record audio.** It declares no `RECORD_AUDIO` permission and contains no `SpeechRecognizer`, `MediaRecorder` or `AudioRecord` usage. Choosing "speak" records only that you chose it, not anything you said.

---

## Your Rights and Controls

- **Turn reminders off:** in the App's settings
- **Delete all data:** uninstall the App, or go to Android Settings → Apps → WaterExperiment → Storage → Clear Data

Because your data exists only on your device and we hold no copy, a data access or deletion request to us would return nothing — you already have the only copy, and clearing app data destroys it permanently.

---

## Health Disclaimer

WaterExperiment is a journaling and habit app, not a medical device. The water log is a record of what you tell it, not health advice, and nothing in the App is a substitute for guidance from a qualified professional.

---

## Children's Privacy

WaterExperiment is not directed at children under 13. We collect no personal information from anyone.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of WaterExperiment after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Personal info | No | No | — |
| Health and fitness (water intake) | Local only, never collected | No | App functionality |
| Your intentions and ritual history | Local only, never collected | No | App functionality |
| Crash logs | No | No | — |
| Device or other IDs | No | No | — |

Declare **"No data collected"** in the Play Console data safety form. The App has no network capability, so there is no transfer to disclose.

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-11-08

---

This is the published policy, served at https://sudarshanchaudhari.github.io/waterexperiment-privacy-policy/ from the `main` branch of this repository. `index.html` carries the same content for the web and must be updated alongside this file. The copy in the [WaterExperiment app repository](https://github.com/SUDARSHANCHAUDHARI/WaterExperiment/blob/main/PRIVACY_POLICY.md) is kept identical.
