# Privacy Policy — FocusPulse

**Last updated:** 2026-03-21
**Effective date:** 2026-03-21

This Privacy Policy describes how **Sudarshan Tech Labs** ("we", "us", or "our") handles information in the **FocusPulse** Android application ("the App").

---

## 1. About This App

FocusPulse is a focus and Pomodoro timer application. It runs focus sessions with background audio, Do Not Disturb integration, and session statistics. All focus data is stored locally on your device.

---

## 2. Data We Do Not Collect

Sudarshan Tech Labs does not operate a backend server for FocusPulse. We do not collect, store, or process your focus session data on any server we control.

---

## 3. Data Stored Locally

| Data | Purpose | Storage |
|---|---|---|
| Focus session history and statistics | Progress tracking | Room database (on-device) |
| Timer settings and preferences | Personalisation | DataStore (on-device) |

This data never leaves your device except for crash reports as described below.

---

## 4. Third-Party Services

### 4.1 Firebase Crashlytics

FocusPulse uses Firebase Crashlytics to detect and report app crashes. When a crash occurs:

- **Data sent:** Device model, OS version, app version, crash stack trace
- **Not sent:** Focus session data, timer history, or any personal information
- **Purpose:** Diagnose and fix app stability issues
- **Stored by Google:** See https://firebase.google.com/support/privacy

### 4.2 Google Play Billing

In-app purchases are processed by Google Play. We do not receive or store payment information.

---

## 5. Permissions Explained

| Permission | Reason |
|---|---|
| `POST_NOTIFICATIONS` | Send alerts when focus sessions or breaks complete |
| `FOREGROUND_SERVICE` | Keep the timer running when the app is in the background |
| `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Required for background audio playback service |
| `WAKE_LOCK` | Prevent the device from sleeping during an active focus session |
| `ACCESS_NOTIFICATION_POLICY` | Enable Do Not Disturb mode automatically during focus sessions |
| `VIBRATE` | Haptic feedback when sessions complete |
| `INTERNET` | Required for Firebase Crashlytics and Google Play Billing |
| `ACCESS_NETWORK_STATE` | Check connectivity before network calls |

---

## 6. Background Services

FocusPulse runs two foreground services:

- **TimerService** — Keeps the focus timer running when the app is backgrounded
- **AudioPlayerService** — Plays ambient sounds during focus sessions

Both services are visible to the user via a persistent notification and can be stopped at any time.

---

## 7. Data Retention and Deletion

| Data | Retention |
|---|---|
| Local focus session data | Until you delete it or uninstall the App |
| Firebase Crashlytics reports | 90 days (per Firebase policy) |

To delete all local data: uninstall the App or clear app data via Android Settings.

---

## 8. Children's Privacy

FocusPulse is not directed at children under 13. We do not knowingly collect personal information from children.

---

## 9. Data Security

- All focus data is stored locally in a Room database protected by Android's application sandbox
- Network communication uses HTTPS/TLS

---

## 10. Changes to This Policy

We will notify you of significant changes by updating the "Last updated" date. Continued use of the App constitutes acceptance.

---

## 11. Contact

**Sudarshan Tech Labs**
Official website: https://sudarshantechlabs.com
Company email: sudarshantechlabs@gmail.com
Developer contact: sunny.sudarshan@gmail.com

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Crash logs | Yes (Firebase Crashlytics) | No | App stability |
| Focus session data | No (local only) | No | — |

---

*This policy applies to the FocusPulse Android application published by Sudarshan Tech Labs.*
