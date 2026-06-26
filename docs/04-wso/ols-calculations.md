# OLS calculations and declared distances

This chapter expands on the Obstacle Limitation Surfaces content in the WSO module by covering the calculation methods and declared distance adjustments required for the AVIB0004 unit of competency — Inspect and report on obstacle limitation surfaces.

---

## Regulatory basis

> 📋 **CASA reference:** MOS Part 139, Chapter 6 — Obstacle limitation surfaces. ICAO Annex 14, Chapter 4 — Obstacle restriction and removal. AIP AD section for YSNF — current declared distances.

---

## Why OLS calculations matter

An FOO or WSO who cannot calculate whether a piece of equipment penetrates the OLS is a liability in the works planning process. The calculation is not complex — but it must be done correctly every time before any works vehicle or equipment enters the airside.

The key principle: **it is not the height of the equipment alone that determines OLS penetration — it is the height of the equipment at its specific location relative to the runway.**

---

## OLS surface types — in depth

### Approach surface

The approach surface begins at the runway threshold and slopes upward away from the runway. Its purpose is to protect the approach path for landing aircraft.

**Key dimensions at a code 4C aerodrome (YSNF):**

| Parameter | Value |
|---|---|
| Inner edge width | 300m |
| Divergence (each side) | 15% |
| Length | 3,000m (first section) |
| Slope | 2% (1:50) |

What this means in practice: an object 100m beyond the threshold must be below 2m AGL to avoid penetrating the approach surface. An object 500m beyond the threshold must be below 10m AGL.

**Quick calculation formula:**
```
Maximum permitted height = Distance from threshold (m) × 0.02
```

Example: A crane positioned 250m from the runway 11 threshold.
Maximum permitted height = 250 × 0.02 = 5.0m AGL

If the crane extends to 8m, it penetrates the approach surface by 3m and a NOTAM is required.

### Take-off climb surface

The take-off climb surface begins at the end of the take-off run available (TORA) and protects departing aircraft during initial climb.

**Key dimensions:**

| Parameter | Value |
|---|---|
| Inner edge width | 180m (code 4) |
| Divergence (each side) | 12.5% |
| Length | 15,000m |
| Slope | 2% (1:50) |

The same calculation formula applies — the slope is identical to the approach surface.

### Transitional surface

The transitional surface slopes outward from the side of the runway strip and from the approach surface. It connects the strip to the horizontal surface.

**Slope:** 14.3% (1:7)

This is the steepest of the OLS surfaces — objects immediately beside the runway strip can penetrate the transitional surface at a relatively low height.

### Horizontal surface

A flat surface at 45m above the aerodrome elevation that extends outward from the aerodrome. Obstacles within this surface must not penetrate it — but in practice this is more relevant to permanent structures and tall vegetation than to works equipment.

### Conical surface

Slopes upward from the outer edge of the horizontal surface at 5%. Again primarily relevant to permanent obstacles.

---

## Practical OLS assessment — step by step

For any proposed works activity involving equipment that might penetrate the OLS:

**Step 1: Determine the working position**
Establish the exact position of the equipment on the aerodrome. Measure from the nearest runway threshold and from the runway centreline.

**Step 2: Identify which OLS surface applies**
- Beyond the threshold? → Approach or take-off climb surface
- Beside the runway strip? → Transitional surface
- On the apron? → May be outside all OLS surfaces (check the aerodrome manual)

**Step 3: Calculate the maximum permitted height**
Using the slope ratio for the applicable surface:
- Approach/take-off climb: height = distance from threshold × 0.02
- Transitional: height = lateral distance from strip edge × 0.143

**Step 4: Compare to the equipment's maximum extended height**
If equipment height > maximum permitted height → OLS penetration occurs

**Step 5: Determine required action**
- OLS penetration during operations → NOTAM required. Assess whether operations can safely continue.
- OLS penetration during runway closure → NOTAM required. Works may proceed during the closure period.
- Penetration at the level of the inner approach surface → may require a runway closure and instrument approach procedure change. Consult with Airservices Australia.

---

## Declared distances — understanding and applying them

The four declared distances (TORA, TODA, ASDA, LDA) are published in the AIP AD for each runway direction at YSNF. They are the distances available to aircraft for take-off and landing performance calculations.

| Distance | Full name | What it measures |
|---|---|---|
| **TORA** | Take-off Run Available | Length of runway available for the ground roll of a taking-off aircraft |
| **TODA** | Take-off Distance Available | TORA plus any clearway beyond the runway end |
| **ASDA** | Accelerate-Stop Distance Available | TORA plus any stopway — the distance available to accelerate and then stop following a rejected take-off |
| **LDA** | Landing Distance Available | The length of runway available for the ground roll of a landing aircraft. May be less than TORA if the threshold is displaced |

### Threshold displacements and LDA

A **displaced threshold** moves the start of the landing area further into the runway. The area before a displaced threshold is available for take-off and taxi, but not for landing.

When a threshold is displaced:
```
LDA = TORA - displacement distance
```

Example: YSNF runway 11 TORA is 1,951m. If a threshold displacement of 150m is applied (due to construction near the threshold), the LDA reduces to 1,801m.

As the WSO planning works near a threshold, you must assess whether your works create a safety condition requiring a threshold displacement. If they do, you must:
1. Calculate the new LDA
2. File a NOTAM with the revised declared distances
3. Notify Airservices Australia of the change
4. Notify the airline so their pilots can recalculate landing performance

> 📋 **CASA reference:** MOS Part 139, Chapter 2 — Physical characteristics. The declared distance requirements are at Section 2.2.

---

## OLS inspection — what to look for

As part of the AVIB0004 competency, you are required to inspect the OLS for penetrating obstacles. During your regular aerodrome inspections:

**Check the approach surfaces:**
- Walk or drive the threshold area and look for any objects that appear above the slope angle
- Check vegetation — trees and shrubs grow. A tree that cleared the OLS last year may not clear it this year
- Check for any new structures in the approach area — masts, buildings, temporary works

**Check the transitional surfaces:**
- Look for any objects immediately beside the runway strip that project above the strip surface
- Check lighting towers, fencing, and ground-mounted equipment

**Check the take-off climb surface:**
- Look beyond the upwind threshold — terrain, obstacles, and structures
- At YSNF, terrain rises steeply beyond the runway ends — be particularly alert to any new structures on the slopes

**Document any penetrations:**
- Photograph the obstacle
- Measure its height and position as accurately as possible
- Compare against the OLS calculation
- If it penetrates the OLS — file a NOTAM and notify maintenance and management

> 🔁 **Scenario:** You are reviewing the aerodrome for an upcoming resurfacing project. The contractor proposes positioning a material stockpile 80m from the threshold 29 end, 15m to the right of the runway centreline. The stockpile will be 4m high. Does it penetrate the OLS? Show your calculation.

**Answer:**
- Surface: Approach surface (beyond the threshold)
- Distance from threshold: 80m
- Maximum permitted height: 80 × 0.02 = 1.6m AGL
- Stockpile height: 4m
- Penetration: 4m - 1.6m = **2.4m penetration — NOTAM required**

The stockpile must either be moved further from the threshold, kept below 1.6m, or the works must be scheduled during a runway closure.
