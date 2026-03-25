# ClearBlue Ionizer Installation Plan — Option B

**Location:** Pressure side, between circulation pump output and heater input (1.5" PVC section, ~5.5" available)

**Rationale:** Fewest parts, fewest glue joints, fewest leak points. Pressure side with consistent flow. Ionization is temperature-independent. Zinc ions from the ClearBlue cell may help prevent scale on the downstream heater element.

---

## Parts Needed

### Included in ClearBlue Kit
- 1× ClearBlue controller
- 1× Mineral cell (electrode assembly)
- 1× 2" clear PVC tee
- 1× 2" to 1.5" reducer bushing
- 1× Copper test strips

### Additional Parts to Buy
- 1× Schedule 40 PVC reducer bushing, 2" spigot × 1.5" socket (to match kit's included one — need two total)
- 1× PVC primer (purple)
- 1× PVC cement (clear or blue — rated for pressure)

### Tools Needed
- Hacksaw, reciprocating saw, or PVC pipe shears
- Marker/pencil for cut lines
- Tape measure
- Rags/towels (water will drain from cut pipe)
- Bucket (to catch residual water)

---

## Pre-Install Checklist

- [ ] Kill power to the hot tub at the breaker (GFCI 50A)
- [ ] Confirm power is off — no lights, no pump hum
- [ ] Close BOTH gate/slice valves (intake and output) to isolate the circ pump and heater
- [ ] Have towels and bucket ready — residual water in the pipe between the valves will drain when you cut

---

## Step-by-Step Installation

### Step 1: Prep the Cut Area
Locate the 1.5" PVC pipe between the circ pump output and the heater's left-side union (see Photo 19). You have approximately 5.5" to work with. Mark the center of this section — this is where you'll cut out 2.5" of pipe for the ClearBlue tee.

Mark two cut lines 2.5" apart, centered in the available space. This should leave roughly 1.5" of pipe on each side for the reducer bushings and glue joints.

### Step 2: Cut the Pipe
Using a hacksaw or PVC shears, make two clean, square cuts at the marks. Remove the 2.5" section. Let any residual water drain into the bucket.

Clean and deburr both cut ends — remove any burrs, shavings, or rough edges. The cleaner the cuts, the better the glue joints.

### Step 3: Dry-Fit the Assembly
Before gluing, dry-fit everything to confirm alignment:

```
[Circ Pump Output] → [1.5" pipe stub] → [Reducer 1.5"→2"] → [ClearBlue 2" Tee] → [Reducer 2"→1.5"] → [1.5" pipe stub] → [Heater Union]
```

The ClearBlue tee's top opening (perpendicular port) should face UP — the ionizer cell screws in from the top with electrode bars pointing down. Confirm nothing binds, the tee sits square, and the cell port is accessible.

### Step 4: Glue the Assembly
Work one joint at a time, starting from the heater side:

1. Apply PVC primer to the inside of the reducer bushing socket AND the outside of the 1.5" pipe stub (heater side)
2. Apply PVC cement to both primed surfaces
3. Push the reducer bushing onto the pipe stub with a quarter-turn twist — hold for 10 seconds
4. Immediately prime and cement the reducer's 2" spigot end into the ClearBlue tee's inline port
5. Repeat for the circ pump side — prime, cement, push, twist, hold

**Important:** PVC cement sets fast. Have all pieces lined up and ready before you start. You have about 15–20 seconds of working time per joint.

### Step 5: Let Cure
Allow glue joints to cure per the cement manufacturer's instructions — typically:
- 15 minutes before handling
- 2 hours before pressurizing (running the pump)
- 24 hours for full cure at full pressure

In a hot tub application, waiting at least 2 hours before powering on is strongly recommended.

### Step 6: Install the Ionizer Cell
Screw the ClearBlue mineral cell into the top port of the tee. The cell threads in by hand — do not overtighten. The electrode bars should point DOWN into the water flow. Ensure the O-ring is seated properly.

### Step 7: Wire the Controller
Route the ClearBlue controller's power cable to the control pack. Connect via Y-splitter at J14 (CIRC + O3) alongside the circulation pump and Lamudo ozonator. See PARTS-AND-COMPONENTS.md Section 6 for the full wiring plan.

Mount the controller box in a dry, accessible location inside the equipment bay.

### Step 8: Test
1. Open both gate valves
2. Restore power at the breaker
3. Let the circ pump run and check ALL glue joints for leaks — especially the two reducer-to-tee joints
4. Verify the ClearBlue controller powers on and shows normal operation
5. Run for 24 hours, then test copper levels with the included test strips

---

## Controller Settings — 380 Gallon Hot Tub

ClearBlue A-400 uses a 0–33 linear scale. Formula: **Volume ÷ 2,500 × 33**

| Setting | Calculation | Value |
|---|---|---|
| **Maintain (Ion/Action)** | 380 ÷ 2,500 × 33 | **5** |
| **Large Dose (Increase)** | ~3× Maintain for initial startup | **~15 hours** |

**How it works:**
- Set Maintain to **5** first, then set Large Dose to **15**
- Large Dose counts down 1 hour per hour automatically, then switches to Maintain mode
- Large Dose is the initial ionization charge — runs at full output to build copper up to target level
- Once Large Dose expires, controller stays on Maintain setting indefinitely

**Startup chlorine:** Add 3 spa-sized chlorine pucks (or equivalent to reach 3–5 ppm) when you start the Large Dose

**Adjustments:**
- Test copper weekly with included test strips — target **0.2–0.4 ppm**
- Copper too high (> 0.4 ppm): reduce Maintain by 25% → set to **4**
- Copper too low (< 0.2 ppm): increase Maintain by 25% → set to **6 or 7**

**Ongoing chlorine maintenance:** 1 spa-sized puck per week (or maintain 0.5–1 ppm FC)

---

## Post-Install Notes

- Target copper level: 0.2–0.4 ppm (per ClearBlue instructions)
- Test copper weekly for the first month, then monthly thereafter
- The ClearBlue system works synergistically with the Clarathon ozonator — both reduce chlorine demand
- Maintain FC at 1–3 ppm even with the ionizer running (do not rely on ionizer alone)
- The ionizer cell is a consumable — replace per ClearBlue's recommended schedule
- Note: Large Dose hours (~15) should be verified against the manual included with your specific unit

---

## Diagram Reference

See `CIRCULATION-CIRCUIT-DIAGRAM.svg` for the updated piping diagram showing the Option B installation location (marked with a star between the circ pump and heater).
