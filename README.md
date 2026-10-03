# Open-Data Timeline & Telemetry Analysis: Flydubai Flight FZ1073 Incident

> **Disclaimer:** This document serves as an independent, non-partisan open-data registry for the Flydubai Flight FZ1073 incident. It synthesizes verified ADS-B transponder telemetry, flight dynamics profiles, passenger testimonies, and multi-agency regulatory statements into a Single Source of Truth for safety analysts and investigators.

---

## 1. Flight Identification & Aircraft Metadata

| Attribute | Recorded Detail | Source / Verification Level |
| :--- | :--- | :--- |
| **Flight Identifiers** | Flydubai FZ1073 / FDB1073 | Flight Manifest / ADS-B Transponder |
| **Aircraft Registration** | A6-FKF | Mode S ICAO 24-Bit Address |
| **Aircraft Model** | Boeing 737 MAX 8 | Manufacturer / Airworthiness Registry |
| **Flight Route** | Dubai (DXB) → Tel Aviv (TLV) | Filed Flight Plan |
| **Passengers & Crew Onboard** | 180 (174 Passengers, 6 Crew) | Saudi GACA & Airport Operational Logs |
| **Emergency Diversion Airfield** | Tabuk Regional Airport (TUU / OETB) | ATC Emergency Clearance Logs |
| **Investigation Authorities** | Saudi Arabia GACA, UAE GCAA, NTSB, ICAO | Multi-Agency Regulatory Statements |

---

## 2. Technical Telemetry & Flight Dynamics

| Telemetry Parameter | Recorded Metric / Parameter | Aviation Context & Verification Status |
| :--- | :--- | :--- |
| **Cruising Altitude** | ~34,000 ft (FL340) | Nominal pressure altitude prior to event onset |
| **Altitude Delta ($\Delta h$)** | ~14,000–19,000 ft drop | High-rate uncommanded descent profile |
| **Descent Duration** | ~30 seconds | ADS-B Pitch/Altitude telemetry log |
| **Peak Descent Rate** | Exceeding -14,000 ft/min | Transonic dive profile recorded by Flightradar24 |
| **Transponder Squawk Sequence**| `7700` (05:32 UTC) $\rightarrow$ `7500` (05:39 UTC) | Mode S Emergency & Unlawful Interference Signals |
| **Level-Off & Stabilization** | ~15,000 ft (FL150) | Manual yoke recovery & pitch stabilization |
| **Structural Impact Observed** | Upper rudder structural separation | Inspection post-touchdown at Tabuk (TUU) |

---

## 3. Event Sequence Chronology

| UTC Time Marker | Phase / Action | Key Actors Involved | Location / Operational Status |
| :---: | :--- | :--- | :--- |
| **03:05 UTC** | **Departure:** Flight departs Dubai International Airport. | Flight Crew | Nominal climb to FL340 |
| **05:21 UTC** | **Assault Onset:** First officer attacks Captain; forces yoke down. | First Officer, Captain Machchar | Flight Deck (Locked) |
| **05:22 UTC** | **Uncommanded Dive:** Aircraft drops >14,000 ft in ~30 seconds. | Avionics / Controls | High-speed descent initiated |
| **05:23 UTC** | **Door Release:** Captain engages emergency door release. | Captain Machchar | Flight Deck Mechanism |
| **05:24 UTC** | **Cabin Intervention:** Passengers & off-duty pilots breach cockpit. | Yaniv Hayun, Crew & Passengers | Flight Deck / Forward Cabin |
| **05:32 UTC** | **Emergency Signal:** Mode S Transponder broadcasts Squawk 7700. | Deadheading Pilots / Avionics | International Airspace |
| **05:33 UTC** | **Flight Level Stabilized:** Yoke pulled back; altitude levels at FL150. | Deadheading Pilots & Passengers | Pitch recovery achieved |
| **05:39 UTC** | **Hijack Signal:** Transponder updated to Squawk 7500. | Avionics / Crew | Regional ATC Notification |
| **06:45 UTC** | **Emergency Landing:** Safe touchdown executed at Tabuk (TUU). | Off-Duty Pilots & Saudi ATC | Tabuk Airport (OETB / TUU) |

---

## 4. Source Verification & Forensic Matrix

| Claim / Detail | Status | Evidence Type | Primary Source |
| :--- | :---: | :--- | :--- |
| **Rapid Altitude Loss (>14,000 ft)** | 🟢 **Verified** | ADS-B Transponder Telemetry | Flightradar24 / RadarBox Logs |
| **Cockpit Door Override & Entry** | 🟢 **Verified** | Eyewitness & Official Statements | Captain Machchar & Passenger Testimony |
| **Transponder Squawk 7700 & 7500** | 🟢 **Verified** | Mode S Transponder Broadcasts | ATC / Flightradar24 Logs |
| **Rudder Structural Damage** | 🟢 **Verified** | Post-Landing Inspection Photos | Runway Inspection at Tabuk (TUU) |
| **Black Box Forensic Analysis** | 🟡 **In Progress** | CVR & FDR Laboratory Audit | Joint GACA / UAE GCAA Investigation |

---

## 5. Regional & Global Media Framing

| Media Group / Sphere | Core Narrative & Focus | Primary Analytical Angle |
| :--- | :--- | :--- |
| **Israeli Media** | Passenger intervention & security response | Eyewitness accounts of Yaniv Hayun & passengers |
| **Gulf / Arab Media** | Regional ATC coordination & safety protocols | Saudi GACA emergency handling & Flydubai briefs |
| **Western Tech / Aviation** | ADS-B telemetry, structural load limits & door engineering | Flight envelope mechanics, aerodynamic stress, and door override systems |

---
## 6. References & Primary Sources

### Telemetry & Flight Tracking Data
* **Flightradar24 Data Log:** [Flydubai FZ1073 Flight History & Telemetry](https://www.flightradar24.com/data/flights/fz1073)
* **RadarBox Live Tracking:** [Flight FZ1073 Playback & ADS-B Altitude Profile](https://www.radarbox.com/)

### Official Regulatory & Government Statements
* **Saudi General Authority of Civil Aviation (GACA):** Press releases on emergency diversion protocols and Tabuk Regional Airport landing clearances.
* **Flydubai Corporate Communications:** Official statements regarding safety protocols and crew/passenger status.

### Verified Witness Accounts & Investigative Reporting
* **Primary Testimony:** Statements by passenger Yaniv Hayun regarding in-cabin response and flight deck intervention.
* **International Media Coverage:**
  * *Reuters / AP:* International coverage on flight deck incident protocols and flight trajectory analysis.
  * *BBC News / CNN:* Analytical coverage of cockpit security mechanisms and multi-jurisdictional investigation status.


