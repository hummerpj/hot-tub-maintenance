# Parts & Components — 2019 Master Spas Twilight Series 8.2

## 1. Control System (Balboa)

### Control Board
| Field | Value |
|---|---|
| System | Balboa BP501 / BP601 |
| Board Part Number | P/N 24200 C |
| Board Revision | 26667 REV.D |
| Wiring Diagram | MS501X, PN 56666-05, dated 07-24-18 |
| Fuse | 30A / 250V (on board, unfused position also present) |
| Power Input | Neutral + Hot terminals with 6 AWG wiring |

### Board Connectors (labeled on PCB)
| Connector | Purpose |
|---|---|
| PUMP 1 | Main jet pump (2-speed) — white Molex connector, red/black/white/green wires |
| PUMP 2 | Secondary jet pump — white Molex connector |
| CIRC | Circulation pump — white Molex connector, yellow/black wires |
| OZONE | Ozonator output — screw terminal block (C27) |
| LED | LED lighting harness |
| S2 | Auxiliary sensor / topside panel |
| HEAT | Heater output — via J46 terminal |

### Relays
| Part | Specs |
|---|---|
| Zettler AZ2150-1A-12DEF | 25A / 250VAC (resistive), 40A / 250VAC (inductive), 1HP / 25VAC |
| Quantity on board | At least 2 (for Pump 1 and Pump 2 switching) |

### Patent Numbers (visible on board housing)
Manufactured under one or more of these U.S. Patents: 5,332,944 / 5,361,215 / 6,560,753 / 5,559,720 / 5,883,459 / 6,282,370 / 7,030,343 / 7,417,834 / 8,666,494 B2. Canadian patents applied for. All software copyright Balboa Water Group.

### Temperature Sensor
| Field | Value |
|---|---|
| Barcode / P/N | 902281043 |
| Description | SENSOR ONLY, 12IN (DIA. 1/4IN) |
| Type | Thermistor probe, 12" lead, 1/4" diameter |

**Photo references:** `images/03-control-board/`

---

## 2. Heater (Balboa)

| Field | Value |
|---|---|
| Manufacturer | Balboa Water Group |
| Power Rating | 4.0 kW |
| Description | HEATER 4.0Kw 800 15IN 2X2 M7 STUD |
| Model Code | MIL15-4.0 |
| Factory ID | TI |
| Serial / Barcode | 58104***1903070349 (manufactured March 7, 2019) |
| UL File | E188744 |
| DIP Switch Labels | RES (C), ELE (D), PS/S (E), HP (G), T (I), TP (I) |
| Warning | Do not attempt to remove element — element removal voids warranty |

**Photo reference:** `images/02-heater/04-balboa-heater-label.jpg`

---

## 3. Main Jet Pump (Balboa)

| Field | Value |
|---|---|
| Manufacturer | Balboa Water Group |
| Part Number | 1016205-NHP |
| Serial Number | 1016205-1902270425 (manufactured Feb 27, 2019) |
| Speed | 2-speed |
| Voltage | 230V |
| Frequency | 60 Hz |
| Amperage | 12.0A (high) / 3.5A (low) |
| Frame | 56FR |
| UL Material | PUUMC2302582FR |
| UL File | E75122 |
| Description | UJM 12.0A 2SP 230V 60Hz 56FR |

**Photo references:** `images/06-pumps/15-jet-pump-full-view.jpg` and `images/01-id-plates-and-specs/02-balboa-pump-label.jpg`

---

## 4. Circulation Pump (Goulds / Laing)

| Field | Value |
|---|---|
| Manufacturer | Goulds Water Technology / Laing Thermotech |
| Series | Laing Thermotech Series — Water Circulating Pump |
| Model | E14-NSTNDNN2W-01 |
| Part / Catalog Number | 6040U0014 |
| Origin | Made in Hungary |
| Certifications | CSA (C/US), UL 510 776, UL/cUL to CSA, STD C22.2 NO. 108 |

**Photo reference:** `images/06-pumps/14-circulation-pump-label.jpg`

---

## 5. Plumbing

### Circulation Pump Circuit — Full Loop

The circulation pump runs 24/7 (or on timed filtration cycles via J14). Water follows this path:

1. **Tub → Intake Gate Valve** — water exits the tub shell through rigid 2" PVC and passes through a maintenance slice/gate valve on the intake side
2. **Gate Valve → Circulation Pump** — 2" PVC drops through a 90° elbow down to the Laing/Goulds circ pump inlet
3. **Circulation Pump → ★ ClearBlue Ionizer Tee → Heater** — circ pump output connects via ~5.5" of 1.5" PVC to the left side of the Balboa BP heater through a 1.5" union fitting; the ClearBlue ionizer tee is spliced into this 1.5" section (pressure side, before heater); flow direction is left → right through the heater
4. **Heater → Output Gate Valve** — heated water exits the right side of the heater via 1.5" union, rises up to a second maintenance slice/gate valve (output/return side)
5. **Gate Valve → Ozone Bypass Tee** — after the output gate valve, the 1.5" rigid PVC continues to a 1.5" PVC tee; a ¾" vinyl bypass branch off the tee runs through the venturi injector and turbo mixer for ozone injection; ¼" tubing runs from the Clarathon ozonator through a Hartford loop and check valve to the venturi injector's ¼" barb
6. **Ozone Tee → Return to Tub** — after the tee, the line routes back to the tub return fittings (exact size TBD — pending zoomed-out photo)

### Pipe Sizes and Fittings

| Component | Size / Type |
|---|---|
| Main circulation loop rigid pipe | 2" schedule 40 white PVC (main runs) |
| Circ pump → heater pipe | 1.5" schedule 40 white PVC (~5.5" section) |
| Heater → output gate valve pipe | 1.5" schedule 40 white PVC |
| Heater unions | 1.5" threaded unions (gray) |
| Gate/slice valves (×2) | 2" — one intake, one output |
| Ozone bypass tee | 1.5" PVC tee |
| Ozone bypass branch line | ¾" vinyl tubing — branches off tee through venturi injector and turbo mixer |
| Return line (after ozone tee) | Size TBD — pending zoomed-out photo |
| Ozone injection tubing | Clear vinyl tube with check valve |
| 90° elbows | 2" schedule 40 sweep elbows |
| ClearBlue ionizer tee | 2" tee w/ 2×1.5" reducer bushings — spliced into circ pump→heater section |

### ClearBlue Ionizer — Installation Plan (Option B: Pressure Side, Before Heater)

**Location:** On the 1.5" PVC section between the circulation pump output and the heater's left-side union. This is on the pressure side of the circ pump, upstream of the heater. Approximately 5.5" of accessible straight pipe available; the ClearBlue tee requires cutting out a 2.5" section, leaving ~1.5" on each side for glue joints.

**Why this location:**
- Pressure side (after circ pump) — consistent flow, no air pocket risk
- No extra pipe, couplings, gate valves, or ozone tubing extensions needed
- ClearBlue's zinc ions may help prevent scale buildup on the heater element downstream
- Copper/silver ionization effectiveness is independent of water temperature
- ClearBlue recommends "after heater" but does not provide a technical reason; all credible sources confirm ionization works equally well at any point on the pressure side

**Fittings required:**
- 1× ClearBlue 2" clear tee (included in kit)
- 2× Schedule 40 reducer bushing, 2" spigot × 1.5" slip (kit includes one; **buy one additional**)
- PVC primer and cement (not included in kit)

**Orientation:** Ionizer cell screws in from the top of the tee, electrode bars pointing down. Vertical pipe section is an approved orientation per ClearBlue documentation. Do NOT install cell upside-down (air pocket risk around electrode bars).

### General Components

- **PVC pipe:** 2" schedule 40 white PVC (main circulation loop)
- **90-degree elbows:** standard sweep elbows connecting vertical and horizontal runs
- **Union fittings:** 2" threaded unions at heater connections (gray)
- **Gate/slice valves:** 2× maintenance valves — one on intake, one on output — allows isolation of heater and circ pump for service without draining the tub
- **Ozone bypass tee:** 1.5" PVC tee with ¾" vinyl bypass branch for venturi injector and turbo mixer
- **Flexible hoses:** clear vinyl tubing for ozone lines; white corrugated spa flex for return run
- **Insulation:** reflective foil-backed insulation lining the cabinet walls

**Photo references:** `images/05-plumbing/`
- `12-plumbing-elbow-union.jpg` — elbow and union detail
- `13-plumbing-tee-overview.jpg` — original tee overview (unannotated)
- `16-ozone-bypass-tee-closeup-annotated.jpg` — annotated: bypass tee, vinyl tube to ozone injector, ozonator, flow direction, main return pipe
- `17-gate-valve-heater-return-side.jpg` — annotated: output gate valve, control panel, heater, return direction
- `18-heater-front-flow-direction.jpg` — annotated: heater front view (BP system), flow direction L→R, circ pump 24/3° below
- `19-intake-gate-valve-circ-pump.jpg` — annotated: intake gate valve, circ pump, flow direction toward heater
- `20-return-side-wide-view.jpg` — wide view: ozone tee, flex return hose, circ pump area

---

## 6. Water Treatment Add-Ons

### ClearBlue Mineral System
| Field | Value |
|---|---|
| Manufacturer | ClearBlue (Floatron / ClearBlue Ionizer) |
| Purpose | Copper/silver ion mineral sanitizer — reduces chlorine demand |
| How it works | Electrolytic cell releases copper/silver ions that kill algae and bacteria, allowing lower FC maintenance levels |
| Target FC with ClearBlue | 1–3 ppm (lower end of normal range) |
| Installation | Inline with circulation plumbing or hung in skimmer/filter area |
| Notes | Do not exceed recommended copper levels; test copper monthly. Compatible with borates and MgCl₂ system. |

### Ozone System

> ⚠️ **VOLTAGE WARNING:** J14 outputs **240V** on this system (circ pump is 230/240V; Balboa requires ozone = same voltage). Any ozone generator connected to J14 **must be rated for 240V**. 110V/120V units will burn out immediately.

#### Ozone Generator — Clarathon Universal Spa Ozonator Kit

| Field | Value |
|---|---|
| Manufacturer | Clarathon (sold via SpaDepot) |
| Model | Universal Spa Ozonator Kit (HCD-55 platform) |
| Voltage | **100–240V AC auto-sensing** — genuinely universal, UL listed |
| Technology | Corona Discharge (CD) — output does not degrade over time like UV |
| Ozone Output | 50 mg/hr (hot tubs ≤500 gal) / 200 mg/hr (swim spas ≤2,500 gal) |
| Connector | AMP-4 plug — connects to J14 via Y-splitter |
| Connection | J14 (CIRC + O3) — Y-splitter alongside circ pump and ClearBlue |
| Warranty | 1 year factory |
| Includes | 6 ft. ozone tubing, check valve, hose clamps, AMP-4 cord, installation instructions |
| Why chosen | Only unit verified as genuinely universal voltage at a reasonable price point; prior HCD-55 generic and Lamudo SPA-124 both failed/incompatible due to 240V on J14 |
| Notes | Works synergistically with ClearBlue mineral system. Ozone + minerals = significantly lower chlorine consumption. Do not rely on ozone alone — maintain FC at all times. |

#### Venturi Injector — SpaDepot Hot Tub Ozone Venturi Injector

| Field | Value |
|---|---|
| Supplier | SpaDepot |
| Connection | ¾" barb (water line) × ¼" barb (ozone tubing) |
| Function | Installs inline in ¾" water line; flowing water creates venturi suction that draws ozone from generator through the ¼" port |
| Orientation | Arrow on body must point in direction of water flow — critical; reversed installation pushes water into ozone tubing |
| Includes | Hose clamps |
| Backflow prevention | Install check valve (from kit) as close to this fitting as possible, arrow pointing toward injector |

#### Ozone Turbo Mixer — SpaDepot Hot Tub Ozone Turbo Mixer

| Field | Value |
|---|---|
| Supplier | SpaDepot |
| Connection | ¾" barb (both ends) |
| Function | Installs inline in ¾" water line immediately after the venturi injector; mechanically mixes ozone bubbles into water |
| Benefit | Increases dissolved ozone by up to 33%; compensates for short water contact runs |
| Installation order | Water flow → venturi injector → turbo mixer → spa return |

#### Ozone Injection Assembly — Installation Order

```
Ozonator (J14) → 1/4" vinyl tubing → Hartford loop (up above injection height)
    → check valve (arrow → injector) → 1/4" barb on venturi injector
                                                    ↕
1.5" PVC return → ozone bypass tee → 3/4" vinyl branch → venturi injector → turbo mixer → back to tee → spa
```

**Hartford loop reminder:** Route the ¼" vinyl tubing up in a loop higher than both the ozonator and the injection point before descending to the venturi injector. This prevents gravity siphon backflow even if the check valve fails.

### Wiring Diagram Connector Map (MS501X PN 56666-05)
Relevant connectors from the pink-circled row in the wiring diagram photo:

| Connector | Label on Diagram | Status | Notes |
|---|---|---|---|
| J24 | UNUSED | ⚠️ No power | Harness is labeled "OZONE" but unpowered — do not use |
| J21 | UNUSED | ⚠️ No power | Harness is labeled "CIRC" but unpowered — do not use |
| J8 | PUMP 1 | In use | 240V — main jet pump |
| J47 | AV | Available | Audio/Visual accessory output |
| J14 | CIRC + O3 | ✅ Active | Combined **240V** output for circ pump AND ozone generator — Laing E14 circ pump is 230/240V; Balboa requires ozone = same voltage as circ pump |

### ClearBlue Mineral System — Installation Detail
| Field | Value |
|---|---|
| Connector | Flat white 3-conductor plug (standard Molex spa pack style) |
| Operating Voltage | 110V or 220V (universal) |
| Correct Connection Port | **J14 (CIRC + O3)** — Y-splitter off J14 alongside circ pump and 240V ozonator |
| Why J14 | Active 240V output; runs during filtration cycles; designed for circ pump + ozone accessories |
| DO NOT use | J24 or J21 — harness labels say "OZONE" and "CIRC" but both are UNUSED/unpowered per wiring diagram |
| DO NOT use | S2 connectors (low-voltage signal lines for topside/sensors) |
| DO NOT use | J8 Pump 1 (240V — wrong connector type) |

### Installation Summary — J14 (CIRC + O3)
All three devices share J14 via Y-splitter(s):
1. **Circulation pump** — already connected (230/240V)
2. **Clarathon ozonator** — 100–240V auto-sensing, AMP-4 plug; add via Y-splitter ✅ installed
3. **ClearBlue Mineral System** — universal 110–240V; add via Y-splitter (3-conductor flat white)

**Photo references:** `images/03-control-board/09-wiring-diagram.jpg` (full wiring diagram with connector labels), `images/04-wiring-and-connectors/11-equipment-bay-wide.jpg` (equipment bay harness connectors)

---

## 7. Cabinet & Structure

- Foam insulation between shell and cabinet panels
- Reflective radiant barrier lining
- Wood frame supports visible behind plumbing
- ABS pan bottom (if premium option installed)
- Black synthetic exterior cabinet panels
