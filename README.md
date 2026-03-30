<div align="center">

<img src="app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.png" width="128" alt="Deprem Bilgisi"/>

# Deprem Bilgisi

### Real-Time Earthquake Tracker for Turkey & the World

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://android.com)
[![Min SDK](https://img.shields.io/badge/Min%20SDK-Android%207.0-blue?style=flat-square)](https://developer.android.com)
[![Version](https://img.shields.io/badge/Version-1.0.0-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Privacy](https://img.shields.io/badge/Privacy-No%20Data%20Collected-brightgreen?style=flat-square)](#privacy)

**Stay informed. Stay safe.**

[Download on Google Play](#) · [Privacy Policy](privacy_policy.md) · [Report an Issue](../../issues)

</div>

---

## What is Deprem Bilgisi?

Turkey sits on one of the world's most active seismic zones. When the ground shakes, every second matters — knowing what happened, where, and how strong it was can make a real difference.

**Deprem Bilgisi** (Turkish for *Earthquake Information*) is a free, ad-free Android app that pulls live earthquake data from three official sources and puts it in your hands instantly. No sign-up. No tracking. No noise — just the information you need, when you need it.

---

## Features

### 🗺️ Live Earthquake Feed
The moment an earthquake is recorded, it appears in your list — sorted by time, color-coded by magnitude so you can read the situation at a glance.

| Color | Magnitude | What it means |
|:---:|:---:|:---|
| 🟢 Green | ≤ 2.9 ML | Minor — barely felt |
| 🟠 Orange | 3.0 – 4.0 ML | Moderate — noticeable |
| 🔴 Red | 4.1+ ML | Strong — take notice |

---

### 🌐 Three Official Data Sources
Switch between providers with a single tap. All data comes directly from official institutions — no middlemen, no delays.

<table>
  <tr>
    <td align="center"><b>🏛️ Kandilli (KOERI)</b></td>
    <td align="center"><b>🇹🇷 AFAD</b></td>
    <td align="center"><b>🌍 EMSC</b></td>
  </tr>
  <tr>
    <td align="center">Boğaziçi University<br/>Turkey & region</td>
    <td align="center">T.C. Disaster & Emergency<br/>Management Authority<br/>Official Turkey data</td>
    <td align="center">European Mediterranean<br/>Seismological Centre<br/>Worldwide coverage</td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.koeri.boun.edu.tr">koeri.boun.edu.tr</a></td>
    <td align="center"><a href="https://www.afad.gov.tr">afad.gov.tr</a></td>
    <td align="center"><a href="https://www.seismicportal.eu">seismicportal.eu</a></td>
  </tr>
</table>

---

### 🗺️ Interactive Earthquake Map
See every earthquake plotted on a live map. Markers are color-coded and scaled by magnitude. Tap any marker for full details. Two powerful overlays make the map even more useful:

- **Fault Line Layer** — visualize Turkey's major fault lines and understand the seismic landscape around you
- **Nearby Filter** — draw a radius around your location and see only what's close to home

---

### 🔔 Smart Notifications
Set your own magnitude threshold and get notified the moment an earthquake crosses it. Each event triggers only one notification — no repeated buzzing for the same quake.

> Notifications are generated entirely on your device. No external push service is used.

---

### 📍 Location-Based Filtering
Whether you're at home or traveling, the Nearby feature filters both the list and the map to show only earthquakes within your chosen radius — from 100 km to 2,000 km.

---

### 🆘 Emergency Survival Tools
When disaster strikes and you need to act fast, the Emergency panel gives you the tools that matter:

| Tool | What it does |
|:---|:---|
| 📞 **Call 112** | One tap to reach emergency services |
| 🔊 **Whistle** | Loud alarm tone to signal for help |
| 🆘 **S.O.S Whistle** | Morse code (· · · — — — · · ·) audio signal |
| 🔦 **Flashlight** | Instantly activate your phone's torch |
| 🆘 **S.O.S Flashlight** | Morse code S.O.S flash pattern |

---

### 🎨 Personalization
The app adapts to you — not the other way around.

- Light, Dark, or System theme
- Magnitude filter for the list view
- Adjustable notification threshold (1.0 – 7.0 ML)
- Adjustable nearby radius
- All settings saved automatically across sessions

---

## Privacy

Deprem Bilgisi was built with a simple principle: **your phone is yours**.

- ✅ No user accounts or sign-up
- ✅ No personal data collected
- ✅ No analytics or telemetry
- ✅ No advertisements
- ✅ Location is used only on-device, never transmitted
- ✅ All preferences stored locally only

📄 Read the full [Privacy Policy](privacy_policy.md)

---

## Permissions

| Permission | Why it's needed |
|:---|:---|
| `INTERNET` | Fetch earthquake data from official sources |
| `ACCESS_FINE_LOCATION` | Show earthquakes near your location |
| `ACCESS_COARSE_LOCATION` | Fallback location for the nearby filter |
| `POST_NOTIFICATIONS` | Send local earthquake alerts |
| `CALL_PHONE` | Enable one-tap 112 emergency call |
| `RECEIVE_BOOT_COMPLETED` | Resume monitoring after device restart |
| `FOREGROUND_SERVICE` | Run background earthquake monitoring reliably |

---

## Data Sources

All earthquake data is fetched directly from official public APIs:

| Source | Coverage | Official URL |
|:---|:---|:---|
| Kandilli Observatory (KOERI) | Turkey & surrounding region | http://www.koeri.boun.edu.tr |
| AFAD | Turkey (official government data) | https://www.afad.gov.tr |
| EMSC | Worldwide | https://www.seismicportal.eu |

---

## Screenshots

> *Coming soon*

---

## Disclaimer

> Deprem Bilgisi is an **independent, informational app**. It is not affiliated with, endorsed by, or officially connected to AFAD, Kandilli Observatory, EMSC, or any government agency. For official earthquake warnings and evacuation orders, always follow guidance from **T.C. AFAD** at [afad.gov.tr](https://www.afad.gov.tr) and authorized government agencies.

---

## Developer

<div align="center">

**Arif Onur Bütün**  
Independent Android Developer · AR-SE Technology

*Built with ❤️ for the people of Turkey and beyond.*

</div>

---

<div align="center">

© 2026 Arif Onur Bütün · AR-SE Technology

</div>
