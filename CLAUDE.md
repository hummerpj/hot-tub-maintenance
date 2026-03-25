# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

This is a **documentation-only repository** (no code, no build system, no tests) for a 2019 Master Spas Twilight Series 8.2 hot tub (Serial: 1905712, 380 gallons, 240V/40A). It contains reference docs, photo inventories, installation plans, and maintenance guides — not software.

## Repository Structure

- **HOT-TUB-OVERVIEW.md** — Spa identity, specs, electrical requirements, certifications, installed treatment systems
- **PARTS-AND-COMPONENTS.md** — Detailed component documentation: Balboa control board (BP501/601), heater (4.0kW), jet pump (2-speed 230V), circulation pump (Goulds/Laing E14), plumbing layout, water treatment add-ons (ClearBlue ionizer, Clarathon ozonator), wiring diagram connector map
- **REPLACEMENT-PARTS-QUICK-REF.md** — Part numbers, chemistry targets, and image index for quick lookup
- **WATER-BALANCE-CHEAT-SHEET.md** — Dosing tables (380 gal), CYA buildup tracker, routine maintenance schedule, practical tips
- **CLEARBLUE-INSTALL-PLAN.md** — Step-by-step ClearBlue ionizer installation (Option B: pressure side, before heater), parts list, controller settings
- **CIRCULATION-CIRCUIT-DIAGRAM.svg** — Piping diagram of the circulation loop with ClearBlue install location
- **balancing_hot_tub_with_magnesium_and_borates_text_markdown.md** — Deep-dive reference on borate buffering, MgCl2 therapy water, dichlor-then-bleach method, and TDS management
- **images/** — Organized photo documentation (data plates, heater, control board, wiring, plumbing, pumps)

## Key Domain Details

- **Water treatment stack:** ClearBlue mineral ionizer + Clarathon ozonator + dichlor-then-bleach (TFP method) + 50 ppm borates + 200-300 ppm MgCl2
- **Critical voltage warning:** J14 connector outputs **240V**. All devices on J14 (circ pump, ozonator, ClearBlue) must be 240V-rated. J24 and J21 are labeled "OZONE" and "CIRC" on the harness but are **unpowered** — do not use them.
- **Chemistry targets with ionizer+ozone:** FC 1-2 ppm, pH 7.2-7.8, TA 50 ppm, CH 120-150 ppm, CYA 20-30 ppm, borates 50 ppm
- **Dosing is calculated for 380 gallons** (not 400 — the balancing reference doc uses 400 gal as a general guide, but the actual tub is 380 gal)

## Working With This Repo

All content is Markdown and SVG. When editing, maintain the existing table-heavy formatting style. Cross-references between docs use backtick-quoted filenames (e.g., `WATER-BALANCE-CHEAT-SHEET.md`). Photo references use relative paths from the repo root (e.g., `images/03-control-board/09-wiring-diagram.jpg`).

## GitHub Sync

- **Remote:** `origin` → `github.com:hummerpj/hot-tub-maintenance.git`
- **Branch:** `main`
- After making changes, commit and push to keep GitHub in sync. Stage specific files rather than using `git add -A`.
