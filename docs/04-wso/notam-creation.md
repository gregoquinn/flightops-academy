# NOTAM creation

Creating NOTAMs is one of the most operationally significant things you will do as a Flight Operations Officer. A well-written NOTAM accurately informs pilots of conditions at your aerodrome. A poorly written NOTAM — or a missing one — can contribute to an accident.

---

## Regulatory basis

> 📋 **CASA reference:** AIP Australia, GEN 3.16 — NOTAM. NOTAMs in Australia are filed through Airservices Australia's NAIPS system. CASA AC 139-01 provides guidance on aerodrome reporting.

---

## What is a NOTAM?

A NOTAM (Notice to Air Missions) is a notice containing information essential to personnel concerned with flight operations that is not known sufficiently in advance to be published by other means (in the AIP).

NOTAMs are distributed through the international NOTAM system (ICAO Annex 15) and are available to all pilots planning flights to or through the affected area.

---

## When to issue a NOTAM

You must issue a NOTAM whenever there is a change in aerodrome conditions that could affect the safety of aircraft operations. Common triggers at YSNF:

| Trigger | NOTAM required? |
|---|---|
| Runway closed | Yes — always |
| Taxiway partially closed | Yes |
| Three or more consecutive edge lights unserviceable | Yes |
| PAPI unserviceable | Yes |
| Aerodrome beacon unserviceable (reduced visibility) | Yes |
| Works in progress on movement area | Yes |
| Crane or obstacle penetrating OLS | Yes |
| Significant pavement defect | Yes |
| Runway threshold displaced | Yes |
| Declared distances changed | Yes |
| Increased wildlife activity — significant hazard | Yes |
| Single isolated edge light unserviceable | No — but record |
| Minor pavement crack with no operational impact | No — but record |

When in doubt, issue the NOTAM. It is far better to give pilots more information than less.

---

## Filing a NOTAM — NAIPS

All Australian NOTAMs are filed through the **NAIPS** (National Aeronautical Information Processing System) web portal operated by Airservices Australia.

Access: [naips.airservicesaustralia.com](https://naips.airservicesaustralia.com)

You will need a NAIPS account authorised for NOTAM filing. Your airport manager will arrange this access when you commence the role.

### NAIPS NOTAM filing steps

1. Log into NAIPS
2. Select **File NOTAM**
3. Enter the NOTAM details in the structured fields (see below)
4. Review the NOTAM text before submitting
5. Submit — NAIPS will issue the NOTAM a NOTAM number (e.g., A1234/26)
6. Record the NOTAM number in your shift log

---

## NOTAM structure

A NOTAM has a standardised structure defined by ICAO. You do not need to format this manually in NAIPS — the system builds the NOTAM from the fields you enter — but you need to understand what each field means.

| Field | Code | Content |
|---|---|---|
| Q-line | Q) | Classification, ICAO location, purpose, scope, lower/upper limit, coordinates, radius |
| A-line | A) | Aerodrome location indicator (YSNF) |
| B-line | B) | Start date/time (UTC) |
| C-line | C) | End date/time (UTC) or PERM or UFN (Until Further Notice) |
| D-line | D) | Schedule (if not continuous) |
| E-line | E) | Free text — the actual NOTAM content |
| F/G-line | F) G) | Lower and upper limits (for airspace NOTAMs — not usually required for aerodrome NOTAMs) |

The E-line (the free text) is where most of your effort goes.

---

## Writing the E-line — NOTAM text

The NOTAM E-line must be clear, unambiguous, and concise. Use plain English where possible, supplemented by standard ICAO abbreviations.

### Common ICAO abbreviations for aerodrome NOTAMs

| Abbreviation | Meaning |
|---|---|
| RWY | Runway |
| TWY | Taxiway |
| APRON | Apron |
| THR | Threshold |
| TDZ | Touchdown zone |
| CLSD | Closed |
| UNSERVICEABLE / U/S | Unserviceable |
| WIP | Works in progress |
| OPN | Open |
| AVBL | Available |
| LGT | Light/lighting |
| PAPI | Precision Approach Path Indicator |
| ACFT | Aircraft |
| APN | Apron |

### E-line examples

**Runway closure:**
```
RWY 11/29 CLSD DUE RESURFACING WIP. AERODROME CLSD.
```

**Lighting unserviceable:**
```
RWY 29 EDGE LGT U/S 3 CONSECUTIVE LGT LH SIDE 400M FM THR 29.
NIGHT OPS RWY 29 NOT AVBL.
```

**PAPI unserviceable:**
```
PAPI RWY 11 U/S. VISUAL APPROACH GUIDANCE NOT AVBL RWY 11.
```

**Works in progress:**
```
WIP APRON RESEAL. CRANE OPR MAX HT 15M AGL POSN 400M WEST APN.
PENETRATES OLS. ACFT CAUTION ADVISED.
```

**Wildlife hazard:**
```
INCREASED BIRD ACTIVITY VICINITY AERODROME. BIRD STRIKE RISK
ELEVATED. PILOTS ADVISED EXERCISE CAUTION ALL PHASES OF FLT.
```

**Threshold displacement:**
```
RWY 11 THR DISPLACED 120M. LDA RWY 11 REDUCED TO 1831M.
```

---

## NOTAM start and end times

All NOTAM times are in **UTC (Coordinated Universal Time)**, not local time. Norfolk Island Standard Time (NFST) is UTC+11:30. Norfolk Island Daylight Time (NFDT) is UTC+12:30.

> ⚠️ **Important:** Always calculate NOTAM times in UTC. Getting the local-to-UTC conversion wrong can mean a NOTAM is not active when pilots are planning their flight, or expires before works are complete.

**Conversion reminder:**
- NFST (winter): subtract 11 hours 30 minutes from local time to get UTC
- NFDT (summer): subtract 12 hours 30 minutes from local time to get UTC

---

## NOTAM validity

### Start time
The NOTAM must be active before any change it describes takes effect. If you are about to close the runway for maintenance, issue the NOTAM first, then close the runway.

### End time
Set the end time to when you expect the condition to be resolved, plus a buffer. It is better to cancel a NOTAM early (when works finish ahead of schedule) than to have an expired NOTAM that no longer reflects conditions.

Use **UFN (Until Further Notice)** when the duration is genuinely uncertain. However, avoid using UFN as a default — pilots find time-limited NOTAMs easier to plan around.

### Cancelling a NOTAM

When the condition described in a NOTAM no longer exists (works complete, lighting repaired, runway reopened), cancel the NOTAM through NAIPS:

1. Log into NAIPS
2. Select **Cancel NOTAM**
3. Enter the NOTAM number
4. Confirm cancellation

Record the cancellation time and NOTAM number in the shift log.

---

## NOTAM review on shift

At the start of every shift, retrieve and read all active NOTAMs for YSNF from NAIPS. Review the end times of all active NOTAMs and:
- Cancel any that have expired and whose conditions no longer apply
- Extend any that are about to expire if the conditions remain
- Note any that affect operations during your shift and brief accordingly

> 💡 **Operational tip:** Keep a written summary of active NOTAMs on the operations desk during your shift. When a pilot asks about current conditions, you should be able to answer immediately without having to log back into NAIPS during a busy period.
