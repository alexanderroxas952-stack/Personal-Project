# Bill of Materials — Mini-CNC 2-Axis Plotter

Target budget: $50-200 CAD. Estimated total was around $130-180.

**Actual spent (orders up to 2026-10-29): $311.40 CAD.** Over the $200 budget ceiling by $111.40.

**2026-10-30 order (5mm pulleys + LM8UU): cost not yet recorded, estimated $20-25.** Projected total about $331-336 CAD. Still to confirm whether $311.40 includes 13% HST.

| Item | Est. cost | Alternative if unavailable | Where to buy |
|---|---|---|---|
| Arduino Uno (or compatible) | $25–35 (or $0 if reused) | Arduino Nano clone (~$12) | Canada Computers (Weber St N, Waterloo) / Amazon.ca |
| CNC Shield V3 + 2× A4988 stepper drivers | $15–20 | 2× L298N driver boards (cheaper, bulkier, less precise) | Amazon.ca |
| 2× NEMA17 stepper motors | $24–36 | 2× 28BYJ-48 + ULN2003 boards (~$5 each, weaker torque) | Amazon.ca |
| GT2 belt + pulley kit | $10–15 | Fishing line + pulley wheels (DIY, lower precision) | Amazon.ca |
| Smooth rods (8mm, ~300–400mm) ×2–4 | $15–20 | Wooden dowels + skateboard bearings | Home Hardware / Canadian Tire (dowels); Amazon.ca (rods) |
| SG90 micro servo (pen lift) | $5 | Solenoid pen-lift (pricier, overkill) | Amazon.ca |
| Frame material (plywood/MDF/acrylic) | $10–20 | Heavy cardboard or foam board | UW Engineering 3D Print Centre / Rapid Prototyping Centre; Michaels (Waterloo) |
| 12V 2A power supply | $10–15 | Reused laptop/phone charger (matching voltage) | Canada Computers / Amazon.ca |
| Jumper wires + small breadboard | $10 (or $0 if reused) | — | Canada Computers / Amazon.ca |
| Misc hardware (M3 screws, nuts, zip ties) | $5–10 | — | Canadian Tire / Home Hardware |
| USB cable (if needed) | $5 | — | Canada Computers |

**Note:** Canada Computers is reliable for generic electronics (Arduino, USB cables, power supply), but its in-store stock of CNC-specific parts (shield, drivers, NEMA17 motors, GT2 belts) is unverified. Amazon.ca is the more consistent source for those.

## Checklist

All parts are ordered (Amazon.ca, 2026-10-29 and 2026-10-30). `[x]` = ordered; delivery status in parentheses. See [`docs/log.md`](./docs/log.md) for details.

- [x] Arduino Uno REV3 (delivered Oct 29)
- [x] CNC Shield V3 (2 pack, 1 spare) + A4988 drivers (4 pack, 2 spares) (delivered Oct 29)
- [x] 2× NEMA17 stepper motors (3401S) (delivered Oct 29)
- [x] GT2 belt + GT2 pulleys (delivered Oct 29; pulleys are 20T 8mm bore, wrong bore for NEMA17, not usable)
- [x] 2x GT2 20T pulleys, 5mm bore (ordered Oct 30, arriving Tue Nov 3)
- [x] LM8UU linear bearings, 10 pack (ordered Oct 30, arriving Tue Nov 3). Missing from the original BOM: needed for the carriages to slide on the 8mm rods.
- [x] 4× smooth steel rods, 8mm × 300mm (expected Nov 5-9)
- [x] SG90 micro servo (delivered Oct 29)
- [x] Frame material: 1/4" MDF, 11×14, 10 pack (two sheets glued per panel) (delivered Oct 29)
- [x] 12V 2A power supply (expected by Nov 2)
- [x] Jumper wires + breadboard (delivered Oct 29)
- [x] M3 screw/nut kit + zip ties (delivered Oct 29)
- [x] USB A to USB B cable (delivered Oct 29)
