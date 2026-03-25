# 2019 Master Spas Twilight Series 8.2 — Maintenance Reference

Reference documentation, maintenance guides, and photo inventory for a **2019 Master Spas Twilight Series 8.2** hot tub.

## Quick Specs

| Spec | Value |
|---|---|
| Model | Twilight Series 8.2 (Model 5700) |
| Serial | 1905712 |
| Water Capacity | 380 gallons |
| Seating | 6 persons, 44 jets |
| Electrical | 240V / 40A / 60Hz single-phase |
| Heater | 4.0 kW |
| Pumps | 2-speed jet pump + Goulds/Laing E14 circulation pump |
| Control System | Balboa BP501/601 |

## Water Treatment Stack

This tub runs a multi-layer sanitization approach:

- **ClearBlue mineral ionizer** (copper/silver ions)
- **Clarathon ozonator** (CD ozone injection)
- **Dichlor-then-bleach method** (TFP approach)
- **50 ppm borates** (pH buffering)
- **200–300 ppm MgCl2** (therapy water)

**Chemistry targets (with ionizer + ozone active):**

| Parameter | Target |
|---|---|
| Free Chlorine | 1–2 ppm |
| pH | 7.2–7.8 |
| Total Alkalinity | 50 ppm |
| Calcium Hardness | 120–150 ppm |
| CYA | 20–30 ppm |
| Borates | 50 ppm |

## Key Files

| File | Description |
|---|---|
| [`HOT-TUB-OVERVIEW.md`](HOT-TUB-OVERVIEW.md) | Spa identity, specs, electrical requirements, certifications |
| [`PARTS-AND-COMPONENTS.md`](PARTS-AND-COMPONENTS.md) | Component details — control board, heater, pumps, plumbing, wiring connector map |
| [`REPLACEMENT-PARTS-QUICK-REF.md`](REPLACEMENT-PARTS-QUICK-REF.md) | Part numbers, chemistry targets, and image index |
| [`WATER-BALANCE-CHEAT-SHEET.md`](WATER-BALANCE-CHEAT-SHEET.md) | Dosing tables (380 gal), CYA tracker, maintenance schedule, practical tips |
| [`CLEARBLUE-INSTALL-PLAN.md`](CLEARBLUE-INSTALL-PLAN.md) | ClearBlue ionizer installation plan (pressure side, before heater) |
| [`CIRCULATION-CIRCUIT-DIAGRAM.svg`](CIRCULATION-CIRCUIT-DIAGRAM.svg) | Piping diagram of the circulation loop with ClearBlue location |
| [`balancing_hot_tub_with_magnesium_and_borates_text_markdown.md`](balancing_hot_tub_with_magnesium_and_borates_text_markdown.md) | Deep-dive on borate buffering, MgCl2 therapy water, and TDS management |

## Photo Inventory

The `images/` directory contains organized photo documentation:

| Folder | Contents |
|---|---|
| `images/01-id-plates-and-specs/` | Data plates and spec labels |
| `images/02-heater/` | Heater assembly |
| `images/03-control-board/` | Balboa control board and wiring diagram |
| `images/04-wiring-and-connectors/` | Wiring harness and connector detail |
| `images/05-plumbing/` | Plumbing layout and fittings |
| `images/06-pumps/` | Jet pump and circulation pump |

## Critical Safety Note

The **J14 connector** on the Balboa board outputs **240V**. All devices connected to J14 (circ pump, ozonator, ClearBlue) must be 240V-rated. The J24 and J21 connectors labeled "OZONE" and "CIRC" on the harness are **unpowered** — do not use them.
