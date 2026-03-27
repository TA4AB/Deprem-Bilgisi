# Privacy Policy

**Deprem Bilgisi** — Earthquake Information App  
**Developer:** Arif Onur Bütün  
**Last Updated:** March 2026

---

## Overview

Deprem Bilgisi ("the App") is an independent Android application developed to provide real-time earthquake data and emergency safety tools. This Privacy Policy explains what information the App accesses, how it is used, and your rights as a user.

> **The App does not collect, store, transmit, or share any personal data with the developer or any third party.**

---

## Information We Access

### 1. 📍 Location (Fine & Coarse)
**Permissions:** `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`

**Purpose:**  
Your device location is used **only on your device** to:
- Filter and display earthquakes near your current position ("Nearby" feature on the map)
- Calculate the distance between your location and earthquake epicenters

**What we do NOT do:**
- We do not transmit your location to any server
- We do not store your location history
- Location is only accessed when you explicitly tap the "Nearby" button

---

### 2. 🔔 Notifications
**Permission:** `POST_NOTIFICATIONS`

**Purpose:**  
Used to send local push notifications when an earthquake above your configured magnitude threshold occurs. All notifications are generated **locally on your device** — no notification service or external server is involved.

---

### 3. 📞 Phone / Call
**Permission:** `CALL_PHONE`

**Purpose:**  
Used exclusively to enable the **112 Emergency Call** button in the Emergency panel. When tapped, the app opens your phone's dialer with 112 pre-filled. No calls are made automatically without your explicit action.

---

### 4. 🌐 Internet
**Permission:** `INTERNET`

**Purpose:**  
Used to fetch real-time earthquake data from the following official public sources:
- **Kandilli Observatory (KOERI)** — `koeri.boun.edu.tr`
- **AFAD** — `deprem.afad.gov.tr`
- **EMSC** — `seismicportal.eu`
- **Map tiles** — `basemaps.cartocdn.com` (OpenStreetMap/CARTO)

No personal data is included in any of these requests.

---

### 5. 🔁 Receive Boot Completed
**Permission:** `RECEIVE_BOOT_COMPLETED`

**Purpose:**  
Allows the App to reschedule background earthquake monitoring after the device restarts, so you continue receiving notifications without manually reopening the app.

---

### 6. ⚙️ Foreground Service
**Permission:** `FOREGROUND_SERVICE`

**Purpose:**  
Required by Android to run background tasks (earthquake monitoring worker) reliably. No persistent foreground service is shown to the user.

---

## Data Storage

All user preferences (notification threshold, selected data source, theme, filter settings) are stored **locally on your device** using Android SharedPreferences. This data:
- Never leaves your device
- Is not backed up to any cloud service by the developer
- Can be cleared at any time by uninstalling the app or clearing app data

---

## Third-Party Services

The App fetches data from the following third-party public APIs. Please refer to their own privacy policies:

| Service | URL | Purpose |
|---|---|---|
| Kandilli Observatory | koeri.boun.edu.tr | Earthquake data (Turkey) |
| AFAD | deprem.afad.gov.tr | Earthquake data (Turkey, official) |
| EMSC | seismicportal.eu | Earthquake data (worldwide) |
| CARTO / OpenStreetMap | carto.com / openstreetmap.org | Map tiles |

---

## Children's Privacy

The App does not knowingly collect any information from children under the age of 13. The App contains no user accounts, registration, or data collection of any kind.

---

## Changes to This Policy

This Privacy Policy may be updated to reflect changes in the App's functionality or legal requirements. The "Last Updated" date at the top of this document will reflect any changes. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## Contact

If you have any questions about this Privacy Policy, please contact:

**Developer:** Arif Onur Bütün  
**Organization:** AR-SE Technology  

---

*This privacy policy is effective as of March 2026.*
