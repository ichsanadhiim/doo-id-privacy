# Privacy Policy — doo.id

_Last updated: 6 November 2026._

doo.id (the "app") is a personal finance tracker developed by ADHIIM ("we"). The app works
entirely on your device: we have no servers, user accounts, or cloud service that stores your data.

## Summary
- We **do not collect** any personal data through this app.
- The app has **no internet permission** and does not send data to us or anyone else.
- No ads, analytics, trackers, or third-party crash reporting.
- Your data is stored encrypted on your device and only leaves it when you share it yourself.

## Data stored on your device
Everything you record: salary, income, expenses, accounts, pockets, goals, investment products (entered
manually), reminders, and app settings. This data is:
- stored in an encrypted database (SQLCipher) in the app's private storage;
- protected by an encryption key kept in the Android Keystore;
- guarded by a PIN stored only as a salted hash, never the PIN itself;
- unlockable with a fingerprint. The app never accesses your fingerprint data; matching is done by Android.

Android's automatic cloud backup is disabled for this app, so your data is not copied to the cloud unless you
ask for it.

## Permissions requested
| Permission | Purpose |
|---|---|
| Notifications | Expense and payday reminders |
| Exact alarms (SCHEDULE_EXACT_ALARM) | Reminders appear on time |
| Run at startup (RECEIVE_BOOT_COMPLETED) | Re-schedule reminders after the device restarts |
| Biometrics | Unlock the app with a fingerprint (PIN remains the fallback) |
| Vibrate | Vibrate on notifications |

The app does not request Accessibility permission, does not read other apps' notifications or the list of
installed apps, and does not access contacts, location, camera, or microphone.

## Files you choose or share yourself
- **Backups.** The backup feature creates a `.mtbackup` file encrypted with a passphrase you choose. It leaves
  the device only if you save it to a folder or share it yourself (for example to Google Drive or email). We
  cannot open a backup without your passphrase and we do not store it. If you lose the passphrase, the backup
  cannot be restored.
- **CSV import.** The app only reads files you pick, on your device.
- **CSV export.** The Backup feature can also export one type of data (salary, expenses, money received from
  outside, goal deposits, or investment products) to a CSV file. **CSV files are not encrypted**: anyone who
  holds the file can read it. The file is created on your device and leaves it only if you save it to a folder
  or share it yourself. Use the `.mtbackup` backup if you need an encrypted file.
- **PDF reports.** Reports are generated on the device and shared only if you choose to share them through
  another app.

Once a file leaves the app, it is handled by the service or app you chose, under its own privacy policy.

## Deleting your data
- Settings › Reset all data erases everything in the app (requires your PIN).
- Uninstalling the app or clearing its data in Android settings also erases all data on the device.
- Backups, reports, or other files you shared must be deleted by you.

Because we hold no copy of your data, we cannot access, restore, or delete it on your behalf.

## Children
The app is not directed to children under 13.

## Changes to this policy
If the app's behavior changes (for example by adding sync or any feature that uses the internet), this policy
will be updated before the change is released, with the new date at the top of this page.

## Contact
Questions about this policy: dalamadhiim@gmail.com
