# Privacy Policy for FocusPulse

**Last Updated**: March 3, 2026  
**Version**: 1.0  
**Effective Date**: March 3, 2026

---

## 1. Introduction

FocusPulse ("**App**") is developed and operated by Sudarshan Chaudhari ("**Developer**", "**we**", "**us**", or "**our**"). This Privacy Policy explains how we handle information in connection with your use of the FocusPulse Android application and related services (the "**Service**").

### Our Privacy Commitment

Your privacy is important to us. FocusPulse is designed with privacy as a core principle. We do not collect personal data, do not sell your information, and do not use analytics or tracking technologies that compromise your privacy.

**The fundamental principle: All your data stays on your device.**

---

## 2. Data We DO NOT Collect

FocusPulse **does not collect**:

- Personal identification information (name, email, phone number)
- Location data
- Contact information or address book data
- Calendar data
- Browsing history
- Device identifiers beyond what's necessary for core functionality
- Biometric data
- Camera or microphone recordings
- Device usage analytics
- Crash logs or diagnostic information
- Behavioral tracking or user activity monitoring
- Third-party advertising or marketing data
- Financial information (except for billing processor records)

---

## 3. Data We Store Locally

FocusPulse stores the following information **exclusively on your device** using Android's encrypted local storage:

### Focus Session Data
- Session start time and end time
- Session duration (in minutes)
- Session type (Work, Short Break, Long Break)
- Completion status (completed or incomplete)
- Associated task ID (if linked)
- Timestamp of session creation

### Task Information
- Task title
- Task description (optional)
- Estimated number of pomodoros
- Completed number of pomodoros
- Completion status
- Priority level (High, Medium, Low)
- Task creation timestamp
- Task completion timestamp (if completed)

### Sound Preferences
- Selected ambient sound (if any)
- Sound volume level setting
- Last played sound identifier

### Timer Presets
- Custom timer duration configurations
- Preset names
- Work/break duration combinations
- Preset usage count

### Application Settings
- Theme preference (Light/Dark mode)
- Notification preferences (enabled/disabled)
- Do Not Disturb mode settings
- Start sound preference
- Break sound preference
- Volume control settings
- Default timer durations

### Automatically Generated Data
- Session statistics (computed from historical data)
- Daily focus metrics
- Weekly productivity summaries
- Completion rates and percentages

---

## 4. Data Storage & Security

### Where Data is Stored

All user data is stored exclusively on your Android device using:

**Android Room Database** (SQLite)
- Encrypted by Android's standard file-level encryption
- Accessible only to the FocusPulse app
- Protected by device lock (PIN, fingerprint, pattern)

**Android DataStore**
- Android's secure preferences storage
- Encrypted by default on Android 7.0+
- Protected by device security

### Data Encryption

- FocusPulse relies on Android's built-in encryption (File-Based Encryption)
- All data at rest is encrypted by your device operating system
- Data in transit (only for billing) uses HTTPS/TLS encryption
- Keys are managed by the Android operating system

### Data Isolation

- FocusPulse data is completely isolated from other apps
- Other applications cannot access FocusPulse data
- Only FocusPulse can read, modify, or delete its own data

### No Cloud Backup

By default, FocusPulse data is **not** sent to cloud services. All data remains on your device only.

---

## 5. Data Retention

### How Long We Keep Data

**Focus Sessions, Tasks, and Statistics**
- Retained indefinitely on your device until you manually delete them or uninstall the app

**App Preferences and Settings**
- Retained indefinitely on your device until you manually delete them or uninstall the app

**Temporary Data**
- Session timers and in-progress states are stored temporarily during active sessions
- Automatically removed when sessions complete or the app is restarted

### Data Deletion

#### Manual Deletion
Users can delete data through the app:
1. Delete individual sessions from history
2. Delete specific tasks from task list
3. Clear all app settings (in Settings > Reset to Defaults)
4. Clear all history and start fresh

#### Complete Data Deletion
All FocusPulse data is automatically deleted when you:
1. **Uninstall the app** from your device
2. **Clear app data** via Android Settings
3. **Factory reset** your device

#### Android Settings Method
To manually delete all FocusPulse data via Android Settings:
1. Open **Settings** → **Apps**
2. Find and select **FocusPulse**
3. Tap **Storage and cache**
4. Tap **Clear storage** or **Clear cache**
5. Confirm the action

---

## 6. Third-Party Services & Integrations

### Google Play Billing

**What data is shared:**
- In-app purchase transactions are processed through Google Play Services
- Information sent: Product ID, purchase status, transaction timestamp
- Google's own privacy policy applies to billing data

**Why it's needed:**
- Process in-app purchases (premium features)
- Verify purchase validity
- Handle billing disputes

**Privacy safeguard:**
- We do not store credit card information
- Billing data is managed entirely by Google Play
- No user payment details are stored locally

**Google's Privacy Policy**: [policies.google.com/privacy](https://policies.google.com/privacy)

### Google Play Services (Metadata Only)

The app includes reference to Google Play Services for billing functionality. No tracking, analytics, or usage data is collected through this integration.

### No Other Third-Party Services

FocusPulse does **NOT** integrate with:
- Firebase or other Google analytics services
- Facebook, Twitter, or other social media
- Third-party crash reporting tools (Sentry, Bugsnag, etc.)
- Advertising networks or ad tracking services
- Data brokers or marketing platforms
- Location services (GPS, geofencing)
- Any other external servers for user data

---

## 7. Internet & Network Usage

### When FocusPulse Uses the Internet

FocusPulse uses internet connection **only for**:

1. **In-App Purchases** (if enabled)
   - Verifying purchase eligibility with Google Play
   - Checking billing entitlements
   - Restoring previous purchases

2. **App Updates** (if enabled)
   - Checking for app updates via Google Play
   - Downloading new versions through Google Play Store

**All other functionality operates completely offline.**

### Offline Functionality

The app is designed to work entirely **offline**:
- Timers run without internet
- Task management works offline
- Sound playback requires no internet
- Statistics are computed locally
- Notifications work offline

### No Tracking or Analytics

FocusPulse does **NOT**:
- Send diagnostic data
- Collect usage statistics
- Report crash information
- Track user behavior
- Monitor session frequency or duration
- Analyze app performance with user data
- Share data with analytics platforms

---

## 8. Permissions & Their Use

### Requested Permissions

All permissions in AndroidManifest.xml serve specific functionality:

| Permission | Purpose | Data Collected |
|:-----------|:--------|:---------------|
| `POST_NOTIFICATIONS` | Send session alerts | None (local notification only) |
| `FOREGROUND_SERVICE` | Keep timer in background | None (local service only) |
| `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Play ambient sounds in background | None (local audio only) |
| `WAKE_LOCK` | Maintain timer accuracy when device sleeps | None (system state only) |
| `ACCESS_NOTIFICATION_POLICY` | Enable Do Not Disturb mode | None (device setting only) |
| `VIBRATE` | Provide vibration feedback | None (device hardware only) |
| `INTERNET` | Connect for billing verification | Only sent to Google Play Services |
| `ACCESS_NETWORK_STATE` | Check connectivity status | Connection status only (not stored) |
| `BILLING` | Enable in-app purchases | Transaction info sent to Google |

### Permissions We DO NOT Request

FocusPulse does **NOT** request permission for:
- ❌ `ACCESS_FINE_LOCATION` (GPS location)
- ❌ `ACCESS_COARSE_LOCATION` (approximate location)
- ❌ `CAMERA` (camera access)
- ❌ `RECORD_AUDIO` (microphone)
- ❌ `READ_CONTACTS` (contact information)
- ❌ `READ_CALENDAR` (calendar events)
- ❌ `READ_SMS` (text messages)
- ❌ `READ_CALL_LOG` (call history)
- ❌ `WRITE_EXTERNAL_STORAGE` (write to shared storage)
- ❌ Any other sensitive permissions

---

## 9. Background Services & Notifications

### Timer Service

**Purpose**: Keep the timer running when the app is closed

**Data handled**: 
- Current timer state (duration, elapsed time)
- Session type (Work/Break)
- None of this is logged, tracked, or stored for analytics

**Persistence**: 
- Data exists only while the timer is active
- Erased when the timer completes or is stopped

### Audio Service

**Purpose**: Play ambient sounds during focus sessions

**Data handled**:
- Audio file being played
- Volume level
- Playback state

**Persistence**: 
- No recording or logging
- No data retention after playback stops

### Notifications

**What we send**:
- Timer completion alerts
- Session reminders (if configured)
- In-app messages about features

**What we don't do**:
- No marketing or promotional notifications
- No behavioral targeting notifications
- No data mining or tracking notifications
- No third-party ad notifications

---

## 10. User Rights & Control

### Your Data Rights

You have the right to:

**1. Access Your Data**
- View all your sessions, tasks, and settings within the app
- Export session data using the app's export function

**2. Delete Your Data**
- Delete individual sessions or tasks anytime
- Clear all app data via Android Settings at any time
- Delete the app completely to remove all data

**3. Opt-Out of Optional Features**
- Disable notifications
- Disable in-app purchases
- Disable all optional permissions
- Use the app offline without any cloud sync

**4. Control Permissions**
- Grant or revoke permissions anytime via Android Settings
- The app will gracefully handle denied permissions
- Revoking permissions disables only that feature

**5. Transparency**
- View this privacy policy anytime
- Access data storage information
- Understand exactly what data is collected

### No Right to Deletion from Service Provider

Since FocusPulse does not operate backend servers or cloud storage:
- Deleting from your device immediately removes all data
- No backup or recovery process from external servers
- Once deleted, data cannot be recovered unless you have a device backup

---

## 11. Children's Privacy (COPPA)

### Age Restrictions

FocusPulse does **NOT**:
- Knowingly collect data from children under 13
- Provide features specifically targeting children
- Use behavioral tracking that would affect minors

### Parental Controls

Since the app is designed for students and remote workers:
- Parents can control access via Android parental controls
- No special children's mode exists
- Parents should review permissions before allowing children use

If a parent becomes aware that a child under 13 has used FocusPulse and provided information, they may contact us to request deletion (see Contact section).

---

## 12. Security Practices

### Technical Protections

**Local Storage Security**:
- Android file-level encryption (FBE)
- Database access restricted to app process
- No unencrypted backups (by default)

**Network Security** (when using billing):
- TLS/HTTPS only for any network communication
- API requests to Google Play Services only
- No data transmitted to other third parties

**Code Security**:
- Regular security updates via app updates
- Reviewed code for injection vulnerabilities
- No hardcoded credentials or secrets

### What We Don't Have

FocusPulse does **NOT** have:
- Backend servers to hack
- Cloud databases with user data
- API keys or credentials exposed in code
- External authentication systems
- User tracking infrastructure

---

## 13. Data Breach Notification

### In the Unlikely Event of a Breach

Since FocusPulse stores all data locally on your device with no backend infrastructure:

**Risk Assessment**:
- No central database to breach
- No user accounts to compromise
- No backend servers to attack
- Data breach would require compromise of user's own device

**If Your Device is Compromised**:
- Any app with access to your device could potentially access FocusPulse data
- We recommend standard mobile security practices
- Install security updates promptly
- Use device lock (PIN, fingerprint, face recognition)
- Do not download apps from untrusted sources

**If FocusPulse Code is Compromised**:
- Compromised code could potentially read local data
- We would fix the issue immediately in an emergency update
- Users would be notified through app privacy page and release notes

---

## 14. Privacy Policy Updates

### Changes to This Policy

We may update this Privacy Policy to:
- Reflect changes in features (new integrations, etc.)
- Comply with new regulations or laws
- Improve clarity and accuracy

### How We Notify You

**Material Changes**:
- We will notify users within the app
- Update the "Last Updated" date
- Provide at least 30 days notice before changes take effect

**Minor Changes**:
- Clarifications or language improvements
- Updated immediately with no notice period

**Your Consent**:
- Continued use of the app after updates = acceptance of new policy
- If you disagree, you can delete the app

### Previous Versions

Previous versions of this policy will be maintained in the GitHub repository.

---

## 15. Compliance & Legal

### Regulatory Compliance

This Privacy Policy is designed to comply with:

**Privacy Regulations**:
- GDPR (General Data Protection Regulation) - EU
- CCPA (California Consumer Privacy Act) - California, USA
- LGPD (Lei Geral de Proteção de Dados) - Brazil
- Google Play Data Safety requirements

**Children's Privacy**:
- COPPA (Children's Online Privacy Protection Act) - USA
- Similar regulations in other jurisdictions

**Data Security**:
- NIST Cybersecurity Framework
- Android Security & Privacy Documentation

### Your Rights Under GDPR (if applicable)

If you're in the EU or covered by GDPR:

**Right to Access**:
- You have the right to request what personal data we hold
- Since we hold none, this right is automatically satisfied

**Right to Deletion**:
- You have the right to delete your data
- You can do this anytime via Android Settings or app uninstall

**Right to Privacy**:
- Guaranteed by our local-only data storage model
- No processing of data outside your device

**Data Processor Info**:
- No data processors (no third parties handling your data)
- Exception: Google Play Services for billing only

**No Response Timeline Required**:
- Since no personal data is collected, response timelines do not apply

### Your Rights Under CCPA (if applicable)

If you're in California or covered by CCPA:

**Right to Know**:
- What data is collected: Only local session/task data
- This policy fully discloses what is stored

**Right to Delete**:
- You can delete data anytime via Android Settings
- Complete deletion guaranteed when you uninstall

**Right to Opt-Out**:
- No data selling occurs (we don't have data to sell)
- No behavioral tracking practices

**No Discrimination**:
- Privacy choices don't affect service quality
- All features work whether permissions are granted or not

---

## 16. Data Processing & Controller

### Data Controller

**Name**: SudarshanTechLabs
**Email**: sudarshantechlabs@gmail.com
**Location**: Bangkok, Thailand

### Data Processor (Google Play Billing)

**Name**: Google LLC  
**Email**: See Google's privacy policy  
**Website**: google.com  
**Privacy Policy**: https://policies.google.com/privacy

For billing-related data processing questions, refer to Google's privacy documentation.

---

## 17. Contact & Support

### Questions About This Privacy Policy

If you have questions or concerns about this Privacy Policy, data practices, or your privacy rights:

**Email**: sudarshantechlabs@gmail.com
**Location**: Bangkok, Thailand

**Response Time**: We will respond to privacy inquiries within 30 days.

### Feedback

We welcome feedback about our privacy practices:
- GitHub Issues: https://github.com/sudarshantechlabs/FocusPulse/issues
- Email: sudarshantechlabs@gmail.com

### Complaints

If you believe we've violated your privacy rights:

**In the EU**: Contact your supervisory authority (local privacy regulator)  
**In the US**: Contact the FTC (Federal Trade Commission)  
**In Other Countries**: Contact your local data protection authority  

---

## 18. Additional Information

### Sensitive Data

FocusPulse does **NOT** collect or process:
- Special categories of data (race, ethnicity, religious beliefs, etc.)
- Biometric data
- Health data (though session times might indicate work patterns)
- Financial data (beyond billing transactions)

### Automated Decision-Making

FocusPulse does **NOT** use:
- Profiling
- Automated decision-making
- Machine learning based on user data
- Algorithmic content curation

### Cross-Device Tracking

FocusPulse does **NOT**:
- Track users across multiple devices
- Synchronize data between devices (without explicit cloud opt-in)
- Use device identifiers for tracking

### Retention & Archival

- No archived copies of user data are maintained
- No backup retention beyond device restore points
- No long-term storage in servers

---

## 19. Special Disclosures

### About Permissions Being Requested

When you first open FocusPulse on Android 6.0+, you'll be prompted to grant runtime permissions:

1. **Notification Permission** - Required to alert you when timers finish
2. **Foreground Service Permission** - Required to keep timer running in background
3. **Do Not Disturb Mode Permission** - Optional, for auto-DND during sessions

All requests are necessary for core functionality. You can use the app with minimal permissions and disable features as needed.

### About In-App Purchases

Premium features may require:
- Verifying your Google Play account
- Processing transactions through Google Play Billing
- Checking purchase entitlements on subsequent app launches

These operations require internet connectivity and are subject to Google's privacy policies.

### About Background Services

FocusPulse includes a persistent timer service:
- Shows continuous notification (Android requirement)
- Runs only when you explicitly start a focus session
- Stops when session ends or you stop it

This is normal Android behavior for background timers.

---

## 20. Conclusion

FocusPulse is built on a foundation of privacy and transparency:

✅ **Privacy-First Design**: All data stays on your device  
✅ **Complete Transparency**: This policy explains everything  
✅ **User Control**: You control what data is stored  
✅ **No Tracking**: No analytics, no behavior monitoring, no profiling  
✅ **No Selling**: Your data has no commercial value to us  
✅ **Secure Storage**: Encrypted by your device  
✅ **Easy Deletion**: Delete anytime with one click  

We believe productivity should never compromise privacy. FocusPulse delivers both.

---

## 21. Acknowledgments

This Privacy Policy was crafted with attention to:
- Industry best practices for mobile app privacy
- Regulatory requirements (GDPR, CCPA, others)
- Google Play requirements for data transparency
- User expectations for privacy-first software

---

**Last Updated**: March 3, 2026  
**Version**: 1.0.0  
**Repository**: https://github.com/sudarshantechlabs/FocusPulse

For the most current version, visit: [PRIVACY_POLICY.md](https://github.com/sudarshantechlabs/FocusPulse/blob/main/PRIVACY_POLICY.md)
