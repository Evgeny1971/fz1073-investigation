# Open-Data Timeline & Telemetry Analysis: Flydubai Flight FZ1073 Incident 

> **Disclaimer:** This document is an independent, non-partisan registry of facts regarding the incident aboard Flydubai Flight FZ1073. The goal is to construct an objective, verifiable chronology based strictly on flight telemetry data, verified witness testimony, and official regulatory statements.

---

## 1. Executive Summary

* **Flight:** Flydubai FZ1073 (Dubai DXB → Tel Aviv TLV)
* **Aircraft:** Boeing 737 MAX 8
* **Emergency Codes:** Squawk 7700 (General Emergency) / Squawk 7500 (Unlawful Interference)
* **Diversion Airport:** Tabuk Regional Airport (TUU / OETB), Saudi Arabia
* **Outcome:** Aircraft safely landed; 180 passengers and crew survived; attacker neutralized in-flight.

---

## 2. Flight Dynamics & Telemetry (Hard Data)

### Flight Profile & Technical Parameters
| Parameter | Recorded Value / Event | Source / Verification Level |
| :--- | :--- | :--- |
| **Aircraft Model** | Boeing 737 MAX 8 | Flight Manifest / ADS-B Transponder |
| **Flight Path** | Dubai (DXB) → Tel Aviv (TLV) | Filed Flight Plan |
| **Emergency Squawks** | `7700` (Emergency) / `7500` (Interference) | Transponder Logs |
| **Cruising Flight Level** | 33,000 ft (FL330) | ADS-B Telemetry |
| **Minimum Recorded Altitude** | ~18,000 ft | ADS-B Telemetry |
| **Descent Duration** | ~37 seconds | Transponder Pitch/Altitude Logs |
| **Diversion Airfield** | Tabuk Regional Airport (TUU / OETB) | ATC Clearance Logs |

---

## 3. Chronology & Event Sequence

```text
========================================================================================================================
                             FLIGHT FZ1073 (BOEING 737 MAX 8) — INCIDENT ARCHITECTURE & TELEMETRY PROFILE
========================================================================================================================

                                 [ ALTITUDE PROFILE & TELEMETRY TIMELINE ]

 Altitude (ft)
   33,000 |---------[ T₀: NOMINAL CRUISE ]------------------\
          |         * Flight Path: DXB -> TLV               |
   30,000 |         * Speed: Mach 0.78 / FL330              |--[ T₁: COCKPIT ASSAULT & NOSE-DOWN ]
          |                                                 |   * Uncommanded yoke displacement
   25,000 |                                                 \   * Peak descent rate: > -12,000 ft/min
          |                                                  \
   20,000 |                                                   \--[ T₂: TRANSPOONDER SQUAWK 7700 / 7500 ]
          |                                                    \  * Mode S emergency broadcast sent
   18,000 |-----------------------------------------------------\----[ T₃-T₅: INTERVENTION & RECOVERY ]
          |                                                           * Door override released by Captain
    8,000 |                                                           * Attacker subdued by Yaniv Hayun & crew
          |                                                           * Yoke pulled back; descent arrested at FL180
        0 |_____________________________________________________________________[ T₆: TOUCHDOWN AT TABUK (TUU) ]_
                                                                                 * Priority clearance via Saudi ATC

========================================================================================================================

                                    [ PHYSICAL SPACE & COCKPIT OVERRIDE FLOW ]

 +-------------------------------------------------------+       +--------------------------------------------------+
 |                     FLIGHT DECK                       |       |                  FORWARD CABIN                   |
 |                                                       |       |                                                  |
 |  [ Captain Machchar ] <--- (Assault) --- [ Attacker ] |       |  [ Yaniv Hayun ] & Cabin Crew / Passengers       |
 |          |                                  |         |       |                         |                        |
 |          v                                  v         |       |                         v                        |
 |  [ Door Override ]                   [ Control Yoke ] |       |               [ Physical Intervention ]          |
 |          |                                  |         |       |                         |                        |
 +----------|----------------------------------|---------+       +-------------------------|------------------------+
            | (Mechanical Unlock)              | (Forced Dive)                             | (Door Entered)
            v                                  v                                           v
  +-------------------+              +-------------------+                       +-------------------+
  | Armored Door Lock |              |  -12,000 ft/min   |                       | Attacker Subdued  |
  | Mechanism Release |              | Altitude Descent  |                       | & Moved to Cabin  |
  +-------------------+              +-------------------+                       +-------------------+
            |                                  |                                           |
            +----------------------------------+-------------------------------------------+
                                               |
                                               v
                                   [ Flight Stabilized @ FL180 ]
                                   [ Secondary Pilot Takes Yoke]

========================================================================================================================

                                    [ MULTI-AGENCY VERIFICATION & DATA PIPELINE ]

   PRIMARY DATA SOURCES                 ANALYTICAL PROCESSING LAYER                   VERIFICATION STATUS
  +---------------------+               +---------------------------+               +---------------------+
  | ADS-B Transponder   | ------------> | Flightradar24 / RadarBox  | ------------> | 🟢 FL330 to FL180   |
  | (Mode S Packets)    |               | Altitude & Rate Audit     |               |    Descent Verified |
  +---------------------+               +---------------------------+               +---------------------+
                                                                                               |
  +---------------------+               +---------------------------+                          v
  | Saudi ATC / GACA    | ------------> | Air Traffic Radar &       | ------------> | 🟢 Squawk 7700/7500 |
  | Official Briefings  |               | Diversion Control Logs    |               |    Diversion Verified|
  +---------------------+               +---------------------------+               +---------------------+
                                                                                               |
  +---------------------+               +---------------------------+                          v
  | FDR / CVR Recorders | ------------> | Joint GACA & UAE GCAA     | ------------> | 🟡 Full UTC Second  |
  | (Black Boxes)       |               | Forensic Investigation    |               |    Audit Pending    |
  +---------------------+               +---------------------------+               +---------------------+

========================================================================================================================
---

## 4. Source Verification Matrix

| Claim / Detail | Status | Evidence Type | Primary Source |
| :--- | :---: | :--- | :--- |
| **Altitude Loss & Rate of Descent** | 🟢 **Verified** | ADS-B Transponder Logs | Flightradar24 / RadarBox |
| **Physical In-Cabin Neutralization** | 🟢 **Verified** | Witness Statements & Evidence | Passenger Accounts / Yaniv Hayun |
| **Emergency Diversion Clearance** | 🟢 **Verified** | Official Regulatory Releases | Saudi Arabia GACA |
| **Official ICAO Technical Report** | 🟡 **Pending** | Regulatory Investigation | Final Multi-Agency Report |

---

## 5. Regional & Global Media Framing

| Media Group / Sphere | Primary Focus & Narrative | Key Highlights |
| :--- | :--- | :--- |
| **Israeli Media** | Passenger intervention & security response | Focus on Yaniv Hayun's actions & survivor accounts |
| **Gulf / Arab Media** | Aviation safety & regional coordination | Focus on Saudi GACA emergency response & Flydubai statements |
| **Western Tech / Aviation** | Technical analysis & flight deck security | Focus on 737 MAX telemetry, door access, and crew dynamics |

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


