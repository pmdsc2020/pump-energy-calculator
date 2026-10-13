# Pump Energy Design Tool

Interactive calculator for irrigation pump energy requirements based on the **FAO Irrigation Manual, Module 5 — Chapter 8: Energy Requirements**.

**Try it online:** https://pmdsc2020.github.io/pump-energy-calculator/

## Features
- Live schematic with animated water flow
- Sliders for all inputs (discharge, static lift, friction, pressure, efficiencies)
- Brake power in kW and HP
- Suggested motor size (FAO list, Indian market sizes, or no rounding)
- Annual energy calculation (kWh and kWh/ha), plus energy at the pump's actual load
- System comparison: Surface vs Sprinkler vs Localized across static lifts
- Based on FAO Examples 6–9 and Table 3

## How to use
Open the live page on a phone or computer. Everything runs in the browser; nothing is uploaded.

## Offline copy
Want a copy for your team or a training session? Message Jitendra Sonawane on LinkedIn and he will share the download link.

## Notes on the FAO numbers
The tool reproduces FAO Example 6 exactly (15.4 kW, 18 kW motor, 3,070 h, 4,485 kWh/ha) and Examples 7–9 and Table 3 within rounding. Two printed values in Module 5 do not follow from FAO's own method, so the tool differs there:
- Table 3, surface irrigation at 20 m static lift, uses 20 m of head instead of 25 m (Example 7 gives 25.8 kW for the same case).
- Example 9, localized irrigation, leaves out the ÷ 0.88 motor efficiency (about 52,330 kWh, not 46,050 kWh).

## Source
FAO Irrigation Manual (Savva & Frenken, FAO SAFR, Harare, 2001), Module 5: Irrigation Pumping Plant.

Daily Irrigation Engineering SketchNotes series · Jitendra Sonawane, Agriculture Engineer · 7720045808
