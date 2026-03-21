# FocusPulse — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

FocusPulse is a Pomodoro and focus timer for Android. It runs structured focus sessions with background audio, automatic Do Not Disturb integration, and detailed productivity statistics. All session data is stored locally on your device.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Focus session history (duration, type, date, completion status) | Statistics and progress tracking | Room database on your device |
| Timer settings and preferences | Personalisation | DataStore on your device |
| Session streak and productivity stats | Motivation and tracking | Room database on your device |

This data never leaves your device except for crash reports described below.

### Data Collected by Third-Party Services

**Firebase Crashlytics:**
When the App crashes, the following is automatically sent to Firebase Crashlytics:
- Device model, Android OS version, app version
- Crash stack trace and error logs
- No focus session data or personal information is included

**Google Play Billing:**
In-app purchases are processed by Google Play. Sudarshan Tech Labs does not receive or store payment information.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Run and track focus sessions | Local session data |
| Display productivity statistics and charts | Local session history |
| Play ambient sounds during focus sessions | Device audio (MediaPlayer) |
| Send session completion notifications | Local notification scheduling |
| Fix app crashes | Firebase Crashlytics reports |

---

## Background Services

FocusPulse runs two foreground services, visible to you via a persistent notification:

- **TimerService** — Keeps the focus timer running when the App is backgrounded or the screen is off
- **AudioPlayerService** — Plays ambient sounds (e.g., rain, white noise) during focus sessions

Both services can be stopped at any time by dismissing the notification or closing the App.

---

## Data Storage and Security

- **Session data:** Stored in a Room database in the App's private directory
- **No cloud storage:** Sudarshan Tech Labs operates no backend server for FocusPulse
- **Android sandbox:** All data is protected by Android's application sandboxing

## Data Retention

| Data | Retention |
|---|---|
| Local focus session data | Until you delete it or uninstall the App |
| Firebase Crashlytics reports | 90 days (Firebase default) |

---

## Data Sharing

We do not sell your data. The only external data transmission is crash reports sent automatically to Firebase Crashlytics when the App crashes.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `POST_NOTIFICATIONS` | Alert you when focus sessions or breaks complete |
| `FOREGROUND_SERVICE` | Keep the timer running when the App is in the background |
| `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Required service type for background audio playback |
| `WAKE_LOCK` | Prevent the device from sleeping during an active focus session |
| `ACCESS_NOTIFICATION_POLICY` | Enable Do Not Disturb mode automatically during focus sessions |
| `VIBRATE` | Haptic feedback when sessions complete |
| `INTERNET` | Required for Firebase Crashlytics and Google Play Billing |
| `ACCESS_NETWORK_STATE` | Check connectivity before network calls |

---

## Your Rights and Controls

- **Stop background services:** Dismiss the persistent notification or close the App
- **Delete all session data:** Uninstall the App or go to Android Settings > Apps > FocusPulse > Storage > Clear Data
- **Disable Do Not Disturb integration:** Turn off the setting in App preferences

---

## Children's Privacy

FocusPulse is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of FocusPulse after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Focus session data | Local only | No | App functionality |
| Crash logs | Yes (Crashlytics) | No | App stability |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
