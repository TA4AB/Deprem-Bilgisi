# Privacy Policy — Deprem Bilgisi

**Effective Date:** January 1, 2026  
**Last Updated:** January 1, 2026  
**Developer:** Arif Onur Bütün — AR-SE Technology

---

## 1. Introduction

Deprem Bilgisi ("the App") is a free, independent Android application that provides real-time earthquake data and emergency safety tools. This Privacy Policy describes what device capabilities the App accesses, why it accesses them, and how your data is handled.

> **The App does not collect, store, transmit, or share any personal data. No data ever leaves your device.**

---

## 2. Summary at a Glance

| What | Collected? | Shared? | Stored Remotely? |
|:---|:---:|:---:|:---:|
| Personal identity | ❌ No | ❌ No | ❌ No |
| Location data | ❌ No | ❌ No | ❌ No |
| Device identifiers | ❌ No | ❌ No | ❌ No |
| Usage analytics | ❌ No | ❌ No | ❌ No |
| Crash reports | ❌ No | ❌ No | ❌ No |
| Contacts / call logs | ❌ No | ❌ No | ❌ No |
| App preferences | ✅ Yes | ❌ No | ❌ No (local only) |

---

## 3. Permissions Explained

The App requests the following Android permissions. Each permission is used solely for the feature described below and for no other purpose.

---

### 3.1 `INTERNET`

**Why it's needed:**  
The App fetches real-time earthquake data from official public sources over the internet. No personal data is included in any outbound request — only a standard HTTP GET is made to retrieve publicly available earthquake feeds.

**Data sources accessed:**

| Source | Website | Purpose |
|:---|:---|:---|
| Kandilli Observatory (KOERI) | https://koeri.boun.edu.tr | Earthquake data for Turkey & surrounding region |
| AFAD | https://deprem.afad.gov.tr | Official earthquake data for Turkey |
| EMSC | https://www.seismicportal.eu | Worldwide earthquake data |
| CARTO / OpenStreetMap | https://carto.com | Map tile images for the interactive map |

---

### 3.2 `ACCESS_FINE_LOCATION` and `ACCESS_COARSE_LOCATION`

**Why it's needed:**  
When you tap the **"Nearby"** button, the App reads your device's current location to calculate the distance between you and earthquake epicenters, and to filter the list and map to show only earthquakes within your chosen radius.

**Important:**
- Location is only read when you explicitly activate the Nearby feature.
- Your location is **never transmitted** to any server or third party.
- Your location is **never stored** — it is used in memory only for the duration of the filter operation.
- You can revoke this permission at any time in your device's Settings without affecting other app features.

---

### 3.3 `POST_NOTIFICATIONS`

**Why it's needed:**  
The App sends local push notifications to alert you when an earthquake exceeds your configured magnitude threshold.

**Important:**
- All notifications are generated **entirely on your device**.
- No external push notification service (e.g. Firebase, OneSignal) is used.
- No notification content or delivery data is sent to any server.
- You can disable notifications at any time in your device's Settings or within the App's settings screen.

---

### 3.4 `CALL_PHONE`

**Why it's needed:**  
The Emergency panel includes a **"Call 112"** button that allows you to call emergency services with a single tap.

**Important:**
- This permission is used **only** to pre-fill the emergency number 112 in your phone's dialer.
- No call is ever initiated automatically or without your explicit tap.
- No call logs, contact data, or phone numbers are accessed or stored.

---

### 3.5 `RECEIVE_BOOT_COMPLETED`

**Why it's needed:**  
When your device restarts, Android cancels all scheduled background tasks. This permission allows the App to reschedule its earthquake monitoring worker after a reboot, so you continue receiving notifications without having to manually reopen the App.

**Important:**
- No data is read or transmitted during this process.
- Only the App's own internal background task is rescheduled.

---

### 3.6 `FOREGROUND_SERVICE`

**Why it's needed:**  
Android requires this permission to allow background tasks (WorkManager jobs) to run reliably, even when the App is not in the foreground.

**Important:**
- No persistent foreground notification is shown to the user.
- This permission does not grant the App access to any personal data.

---

## 4. Data Storage

All user preferences — including notification threshold, selected data source, theme choice, magnitude filter, and radius setting — are stored **locally on your device** using Android's SharedPreferences mechanism.

- This data **never leaves your device**.
- It is not synced to any cloud service by the developer.
- It can be deleted at any time by clearing the App's data or uninstalling the App.

---

## 5. Third-Party Services

The App retrieves earthquake data and map tiles from the following third-party public services. The App does not share any user data with these services — only standard anonymous HTTP requests are made.

| Service | Privacy Policy |
|:---|:---|
| Kandilli Observatory (KOERI) — https://koeri.boun.edu.tr | [koeri.boun.edu.tr](https://koeri.boun.edu.tr) |
| AFAD — https://deprem.afad.gov.tr | [afad.gov.tr](https://www.afad.gov.tr) |
| EMSC — https://www.seismicportal.eu | [seismicportal.eu](https://www.seismicportal.eu) |
| OpenStreetMap — https://www.openstreetmap.org | [openstreetmap.org/copyright](https://www.openstreetmap.org/copyright) |
| CARTO — https://carto.com | [carto.com/privacy](https://carto.com/privacy) |

---

## 6. Advertising and Analytics

The App contains:

- ❌ No advertisements of any kind
- ❌ No analytics SDKs (e.g. Google Analytics, Firebase Analytics, Mixpanel)
- ❌ No crash reporting services (e.g. Crashlytics, Sentry)
- ❌ No A/B testing or feature flag services
- ❌ No user tracking or behavioral profiling

---

## 7. Children's Privacy

The App does not target children and does not knowingly collect any personal information from anyone, including children under the age of 13 (or the applicable age of digital consent in your jurisdiction). There are no user accounts, registration forms, or data entry fields of any kind in the App.

---

## 8. Data Security

Since the App does not collect or transmit personal data, there is no personal data at risk of breach. All locally stored preferences are protected by Android's standard application sandboxing, which prevents other apps from accessing them.

---

## 9. Your Rights

Because the App does not collect any personal data, there is no personal data to access, correct, export, or delete. You may remove all locally stored preferences at any time by:

- Going to **Settings → Apps → Deprem Bilgisi → Clear Data** on your device, or
- Uninstalling the App.

---

## 10. Changes to This Policy

This Privacy Policy may be updated to reflect changes in the App's features or applicable legal requirements. The **"Last Updated"** date at the top of this document will be revised accordingly. Continued use of the App after any changes constitutes your acceptance of the updated policy.

---

## 11. Contact

If you have any questions or concerns about this Privacy Policy, please contact:

**Developer:** Arif Onur Bütün  
**Organization:** AR-SE Technology  
**Google Play Store Listing:** [Deprem Bilgisi on Google Play](https://play.google.com/store/apps/details?id=com.aob.earthquake)

---

*© 2026 Arif Onur Bütün · AR-SE Technology. All rights reserved.*
