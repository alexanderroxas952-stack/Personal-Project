# Mini-CNC 2-Axis Plotter

A 2-axis drawing machine (stepper motors + GRBL firmware) that takes a design from AutoCAD, exports it as DXF, converts it to G-code, and draws it with a pen.

Built as a personal project (Oct to Dec 2026) to show the CAD-to-fabrication pipeline, AutoCAD and CNC, on top of existing SolidWorks and Arduino experience.

## Status

In progress. See milestones below.

## Build plan

| Week | Dates | Milestone | Status |
|---|---|---|---|
| 1 | Oct 25-31 | Parts list finalized, parts ordered, repo scaffolded | ✅ |
| 2 | Nov 1-7 | Frame cut and assembled, GRBL flashed (done early, Oct 30), shield and drivers wired, A4988 current limit set (rods arrive late, rails moved to Week 3) | 🟨 |
| 3 | Nov 8-14 | Rods and belts mounted, axes jog-tested | ⬜ |
| 4 | Nov 15-21 | Pen-lift servo mounted, steps/mm calibrated | ⬜ |
| 5 | Nov 22-28 | AutoCAD to DXF to G-code pipeline working | ⬜ |
| 6 | Nov 29-Dec 5 | Wiring tidied, repeatability tested, photos/video captured | ⬜ |
| 7 | Dec 6-12 | Full write-up, final commit, linked from portfolio site | ⬜ |

## Bill of materials

See [`BOM.md`](./BOM.md) for the full parts list, costs, alternatives, and where to buy.

## Repo structure

- `firmware/` — Arduino/GRBL configuration and any custom sketches
- `cad/` — SolidWorks and AutoCAD source files for the frame
- `gcode/` — DXF-to-G-code pipeline scripts and sample drawings
- `docs/` — build photos, video, and notes

## Why this project

Mechatronics first-year students start as generalists. A documented, finished personal project is one of the clearest ways to signal depth early. This one targets a gap flagged on my resume, AutoCAD and CNC, while reusing SolidWorks and Arduino experience from coursework (IDEAS Clinic, TRON Day).
