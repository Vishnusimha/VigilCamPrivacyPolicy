# VigilCam Privacy Policy

Effective date: 2025-11-17

Thank you for using VigilCam. Your privacy is important. This Privacy Policy explains what data the App collects, how it is used, where recordings are stored, how you can delete data, and how to contact the developer.

This is the end-user privacy policy intended to be published for users. It does not include developer-only notes or Play Console guidance.

---

## Summary

- VigilCam records audio and/or video only when you explicitly start a recording in the app.
- Recordings are saved on your device (app-scoped storage) and are not uploaded to any server by default.
- You can optionally publish a recording to your device's gallery (MediaStore); this is a local action that makes the file visible to other apps on your device.
- The app shows a persistent notification while recording and requests notification permission on Android 13+ to display it.
- Automatic backups of user media are disabled for this app.

---

## What the app collects

1. Audio and Video Recordings
   - Type: Audio and video files produced by the app when you record.
   - Source: Captured from your device's microphone and camera while you record.
   - Purpose: To provide the core functionality of creating local recordings you can review, save, share, or publish to your device's gallery.
   - Storage: Files are stored in app-scoped external storage (for example, the app's `Movies/` and `Music/` directories returned by `getExternalFilesDir()`).

2. App Preferences
   - Type: Non-identifying preferences (UI settings, last-used options) stored locally.
   - Purpose: To remember your settings and improve the app experience.

The app does not upload recordings or preferences to any external servers by default.

Other technical data:

- This app does not collect analytics, crash reports, advertising identifiers, or other telemetry. No data is sent to external servers unless you explicitly share a recording.

---

## Permissions (what they are used for)

- `CAMERA`: Used to capture video during recording sessions you start.
- `RECORD_AUDIO`: Used to capture audio during recording sessions you start.
- `FOREGROUND_SERVICE`: Allows recordings to continue while the app is backgrounded; a persistent notification is displayed.
- `POST_NOTIFICATIONS` (Android 13+): Allows the persistent recording notification to be shown.
- `WAKE_LOCK`: Temporarily keeps the CPU awake so long recordings are not interrupted when the screen turns off.
- `WRITE_EXTERNAL_STORAGE` (legacy, Android ≤ 9): Only used on older devices; modern Android uses scoped storage instead.

---

## How recordings are handled and how to delete them

- Default storage: Recordings are saved in the app's private external storage directories (e.g., `Android/data/<package>/files/Movies`).
- Publish to gallery: If you choose to publish a recording, the app copies the file to your device's gallery (MediaStore) so it is visible to other apps on your device.
- Delete: Delete recordings using the in-app UI. To remove all app data, uninstall the app from your device (this removes app-scoped files). If you published a recording to the gallery, delete it from the gallery as well.

- Delete: Delete recordings using the in-app UI. To remove all app data, uninstall the app from your device (this removes app-scoped files). If you published a recording to the gallery, delete it from the gallery as well.

- Retention: Recordings remain on your device until you delete them. Uninstalling the app removes app-scoped files; if you published a recording to the gallery, that copy remains until you delete it from the gallery.
- Temporary files: The app may create temporary files during recording; these are removed when a recording is finalized or when the app's cache is cleared.

---

## Backups

- The app disables automatic backups of recorded media. Recorded files and sensitive preferences are excluded from device backups.

---

## Data sharing

- The app does not transmit recordings to external servers by default.
- If you share a recording via the Android share sheet or publish it to the gallery, that action makes the file available to other apps on your device and those apps may transfer or upload it according to their own functionality.

---

## Security

- Files are stored in app-scoped storage to limit access by other apps.
- The app uses `FileProvider` to securely share files when required.

## Third-party services

- This app does not use third-party analytics, ad networks, or cloud storage providers. It uses Android Jetpack libraries (WorkManager, DataStore) and Hilt for local functionality.

---

## Children and age restrictions

VigilCam is not directed to children. The app is intended for use by adults and individuals who meet the minimum age required in their jurisdiction. The app does not knowingly collect personal data from children under the applicable minimum age. If you are a parent or guardian and believe your child has provided personal data to the App, remove the app from the child's device and delete any recordings created by the child.

## Legal responsibility and consent

Recordings may capture other people's voices and images. It is your responsibility to comply with local laws when recording. Obtain any required consent before making recordings.

---

## How to revoke permissions and delete data

- Revoke permissions: Android Settings → Apps → VigilCam → Permissions.
- Delete data: Use the app UI to delete recordings or uninstall the app to remove app-scoped files.

---

## Contact

If you have any questions about this Privacy Policy, please contact us at: `vishnusimhaplaystore@gmail.com`

To request a copy of your personal data or to request deletion, email `vishnusimhaplaystore@gmail.com`. We aim to respond within 30 days.

---

## Changes to this policy

We may update this policy from time to time. The effective date above shows when this version became active.

Revision history:

- 2025-11-17: Final end-user privacy policy.

