# Privacy Policy — QR Scanner

**Last updated: March 12, 2026**

---

## Overview

QR Scanner is a free mobile application for scanning and creating QR codes. We are committed to protecting your privacy. This policy explains what data the app accesses and how it is used.

---

## Data We Collect

### Data collected automatically

**Anonymous usage statistics** — when you launch the app, an anonymous ping is sent to our server containing:
- A randomly generated device ID (UUID, created on first launch)
- App version number
- No personal data, no name, no email, no location

This data is used solely to count active installs and check for available app updates. It cannot be used to identify you personally.

### Data we do NOT collect

- We do not collect your name, email address, or phone number
- We do not collect your location
- We do not read or store the content of QR codes you scan (all history is stored locally on your device only)
- We do not collect photos or images from your camera roll
- We do not share any data with third parties for advertising purposes

---

## Permissions

| Permission | Why it's needed |
|---|---|
| `CAMERA` | To scan QR codes using the device camera |
| `VIBRATE` | To vibrate briefly when a QR code is successfully scanned |
| `INTERNET` | To check for app updates and send anonymous usage ping |
| `ACCESS_NETWORK_STATE` | To check if internet is available before making requests |
| `ACCESS_WIFI_STATE` | To read Wi-Fi network info when scanning Wi-Fi QR codes |
| `CHANGE_WIFI_STATE` | To assist with connecting to Wi-Fi networks via QR codes |
| `POST_NOTIFICATIONS` | To show a notification after saving a QR code image |

---

## Local Storage

All QR scan history is stored **locally on your device** using an encrypted database (Room/SQLite). This data is never uploaded to any server.

Saved QR code images are stored in your device's Pictures/QRScanner folder and are accessible through your Gallery app.

---

## Third-Party Services

The app uses the following third-party SDKs:

- **Google ML Kit** (barcode scanning) — [Privacy Policy](https://developers.google.com/ml-kit/terms)
- **Google ZXing** (QR code generation) — open source, no data collection
- **AndroidX / Jetpack libraries** — [Google Privacy Policy](https://policies.google.com/privacy)

---

## Children's Privacy

QR Scanner does not knowingly collect any information from children under the age of 13. The app contains no advertising, in-app purchases, or social features.

---

## Data Retention

Anonymous usage statistics (UUID + version) are retained on our server for up to 12 months, after which they are automatically deleted.

---

## Your Rights

Since we do not collect personal data, there is nothing to request deletion of. If you wish to reset your anonymous device ID, you can clear the app's data in your device Settings → Apps → QR Scanner → Clear Data.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. The latest version will always be available at this page. Continued use of the app after changes constitutes acceptance of the new policy.

---

## Contact

If you have any questions about this Privacy Policy, please open an issue on our GitHub repository.

---

*QR Scanner — simple, fast, private.*
