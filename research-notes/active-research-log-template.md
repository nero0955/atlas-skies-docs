---
description: >-
  A blank version of our template so you can quickly duplicate it for every new
  test.
---

# 📄 Active Research Log Template

## \[Project Name / Material ID]: Experimental Additive Manufacturing Log

**Date:** YYYY-MM-DD\
**Lead Researcher(s):** @username, @username\
**Status:** \[Concept / In-Progress / Validated / Abandoned]\
**License:** Creative Commons Attribution-ShareAlike 4.0

***

### 1. Objective & Hypothesis

_Briefly describe what you are trying to achieve or test with this specific configuration._

* **Objective:** (e.g., Successfully extrude a 50/50 mix of clay and water using a pneumatic toolhead without nozzle clogging.)
* **Hypothesis:** (e.g., By keeping pressure constant at 2.2 bar and reducing speed to 15mm/s, we can prevent material separation.)

***

### 2. System Hardware & Configuration

_Document the exact physical setup used for this test._

| Component               | Specification / Model            | Modifications / Custom Parts                     |
| ----------------------- | -------------------------------- | ------------------------------------------------ |
| **Base Machine**        | (e.g., Hacked Ender 3)           | (e.g., Removed stock toolhead entirely)          |
| **Extruder / Toolhead** | (e.g., Custom 50cc Syringe Pump) | (e.g., Nema 17 motor with a 4:1 geared plunge)   |
| **Nozzle / Orifice**    | (e.g., Luer Lock Blunt Needle)   | (e.g., 1.5mm inner diameter, stainless steel)    |
| **Build Surface**       | (e.g., Unpolished Ceramic Tile)  | (e.g., Blue painter's tape for initial adhesion) |
| **Firmware & Control**  | (e.g., Klipper / Marlin v2.X)    | (e.g., Custom steps/mm set to X for E-axis)      |

***

### 3. Material Composition & Preparation

_The "recipe" for the material being tested. Exact measurements are crucial for reproducibility._

#### Formulations / Ingredients

* **Base Material:** \[Name] — \[Weight in grams or %]
* **Binder / Solvent:** \[Name] — \[Weight in grams or %]
* **Additive / Modifier:** \[Name] — \[Weight in grams or %]

#### Mixing Process & Cure Notes

1. (e.g., Sift base material through a 100-mesh screen to remove particles larger than 0.15mm.)
2. (e.g., Mix binder and solvent for 5 minutes using a stirrer at 400 RPM.)
3. (e.g., Let the mixture sit for 30 minutes to allow air bubbles to escape before loading.)

***

### 4. Software & Slicing Parameters

_Key parameters from your slicer (OrcaSlicer, Bambu Studio, or custom G-Code script)._

* **Slicer Used:** \* **Layer Height:** `X.XX mm` (or Non-Planar path details)
* **Extrusion Width / Line Width:** `X.XX mm`
* **Print Speed (Perimeters):** `XX mm/s`
* **Travel Speed:** `XX mm/s`
* **Flow Ratio / Extrusion Multiplier:** `X.XX`
* **Temperature (Hotend/Bed):** `XX°C` / `XX°C` _(Set to 0 if cold extrusion)_
* **Retraction Distance / Speed:** `X.X mm` @ `XX mm/s`

***

### 5. Test Results & Data Logs

_Document what actually happened during the print cycle._

#### Quantitative Metrics

* **Total Print Time:** `HH:MM:SS`
* **Success Rate:** `XX%` (Completed vs. Mid-print failures)
* **Measured Layer Adhesion:** \[Excellent / Fair / Poor / Delaminated immediately]
* **Dimensional Accuracy:** Expected `XX.XX mm` vs. Actual `XX.XX mm`

#### Qualitative Observations (The "What Happened" Log)

* **First Layer:** (e.g., Material adhered well, but slight pooling occurred at the start of the perimeter.)
* **Mid-Print Behavior:** (e.g., At layer 14, material started drying out inside the nozzle tip, causing under-extrusion.)
* **Post-Processing / Curing:** (e.g., Part shrunk by roughly 8% along the X/Y axes during the 24-hour air-dry phase.)

***

### 6. Failure Analysis & Media

_Insert photos or screenshots of the toolpaths, successful prints, or spectacular failures._

* **Failure Mode identified:** \[e.g., Nozzle Clog / Structural Collapse / Motor Stalling / Poor Adhesion]
* **Analysis:** (e.g., The raw material contained micro-aggregates that wedged into the 1.5mm nozzle taper. Future tests require finer sifting or a 2.0
