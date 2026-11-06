# Ottercal Privacy Policy

Effective: November 16, 2026  
Last updated: November 7, 2026  
Operator: binarybiscuit (sole proprietor) · Contact: ottercal.app@gmail.com

Ottercal has no sign-up and uses no advertising, analytics, or tracking tools. The developer does not receive or store your events, tasks, photos, or voice. This page explains where and how the app handles each kind of information.

## 1. Processed only on your device
- **Calendars**: used to show and edit your iPhone calendar events. Events stay in iOS Calendar and are never sent to the developer.
- **Camera & Photos**: used only to read text from a picture to create an event. Text recognition runs on device; photos are not saved or sent.
- **Microphone & Speech Recognition**: used only when you dictate an event. Speech is converted to text on device; audio is not saved or sent.
- **Event reminders**: scheduled on your device; no server involved.
- **Settings & memos**: stored on your device. Anniversaries sync between your own devices through your iCloud (Apple Account).

## 2. Sent to outside services (only when you use the feature)
| Feature | Information sent | Recipient |
|---|---|---|
| Weather forecast | Current location coordinates | Apple WeatherKit, Open-Meteo |
| Place search | The place name you type | Naver Local Search API, Apple Maps (MapKit) |
| Google connection (optional) | Google sign-in, reading/writing your Google Tasks, creating/deleting Google calendars, setting email reminders on Google Calendar events | Google |

Each recipient handles this information under its own privacy policy. None of it passes through a developer server.

## 3. Google user data
- Connecting Google is optional. Sign-in tokens are stored only on your device, and the app talks to Google directly.
- Google Calendar events are shown through iOS Calendar (Settings › Calendar › Accounts). The in-app Google connection is used only to show and edit your Google Tasks and to create or delete Google calendars when you ask, and, if you turn it on, to set email reminders on your Google Calendar events. Ottercal does not access Google Drive.
- The developer does not receive, share, or sell Google data, and does not use it for advertising or to train AI models.
- Ottercal's use and transfer of information received from Google APIs adheres to the **Google API Services User Data Policy**, including the Limited Use requirements.
- You can disconnect in Settings or revoke access anytime at [Google Account permissions](https://myaccount.google.com/permissions).

### How we protect Google user data
- Your Google sign-in credential (refresh token) is stored in the iOS Keychain on this device only. It is not synced to other devices through iCloud Keychain. Access tokens are kept only in memory while the app is running and are never written to storage.
- The app talks to Google directly over HTTPS (TLS encryption) only. Nothing passes through any server of ours, and the developer never receives or sees your Google user data.
- We do not sell or transfer Google user data to third parties, do not use it for advertising, and no person reads it.
- **We do not use Google user data to develop, train, or improve artificial intelligence (AI) or machine learning (ML) models.**
- The app requests only the access its features need: reading and writing your Google Tasks, creating or deleting a Google calendar you ask for and setting email reminders on your events, and the email address of the signed-in account.

### Retention and deletion of Google user data
- **What stays on the device**: the signed-in email address, a copy of your Google Tasks list (so it shows right away when you open the app; refreshed on every sync), the color you chose for each task, and email-reminder requests not yet applied to Google (deleted as soon as they are applied). All of this stays only in the app's storage on this device.
- **How long**: until you disconnect Google or delete the app.
- **When you disconnect**: when you disconnect Google in Settings, the app asks Google to revoke the token and immediately deletes the Keychain token, the email address, the task copy, the task colors, and any pending reminder requests.
- **When you delete the app**: the app's storage is deleted with it. A token that iOS may keep in the Keychain is deleted the first time the app runs after a reinstall.
- **Backups**: backup files you create and your iCloud settings backup include your task color settings (task IDs and color numbers). They stay only in your own files and your own iCloud and never reach the developer. A backup file is gone when you delete it, and the task colors in the iCloud settings backup are removed the next time you leave the app after disconnecting Google.
- **Revoking access**: you can remove Ottercal's access at any time at [Google Account › Security › Third-party apps with account access](https://myaccount.google.com/permissions).
- Your Google Tasks and Google Calendar data themselves live in your Google account and are not deleted when you disconnect.
- The developer does not store any Google user data, so there is nothing to delete on our side. For questions or deletion requests, email ottercal.app@gmail.com.

## 4. Parse reports (only when you tap)
If you tap the "Report" button in Quick Memo, the **sentence** you wrote, **how Ottercal understood it** (title, date, time), the app build number, and a **random device ID** created by the app are sent to the developer's iCloud (CloudKit) storage. They are used only to improve date recognition and are not linked to your name, contact details, or Apple Account. Text read from photos is never included. Email us to have reports deleted.

## 5. Children
Ottercal is not directed at children and does not knowingly collect children's personal information.

## 6. Changes
If this policy changes, the updated version will be posted on this page with its date.

## 7. Contact
ottercal.app@gmail.com
