# KITCHEN PROJECT — COMPLETE SPECIFICATION (v2)

**Project:** Custom U-Shaped Kitchen Cockpit
**Status:** Finalized Layout, Appliance Selection Complete, Design Review Incorporated
**Last Updated:** 2026-06-29
**Countertop Material:** Dekton Marmorio 20mm (warm Travertino-like tone)
**Cabinet Finish:** Walnut
**Wall Finish:** White paint
**Floor:** Light oak
**Ceiling Height:** 270cm (2.7m)

---

## 0. COORDINATE SYSTEM

All dimensions use the following fixed 2D floor-plan axes.

| Axis | Direction in plan | What it measures | Zero reference |
|------|-------------------|------------------|----------------|
| **X** | Left → Right (West → East) | Width / horizontal position along a wall | X=0 = inner face of west wall |
| **Y** | Top → Bottom (North → South) | Depth / position away from north wall into room | Y=0 = inner face of north wall |
| **Z** | Floor → Ceiling (not shown in plan) | Height | Z=0 = finished floor level |

**Dimension terminology:**
- **Width** = X-axis span (left to right)
- **Depth** = Y-axis span (front to back of a cabinet)
- **Height** = Z-axis span (floor to ceiling)
- **Length** = Y-axis span along west wall; X-axis span along north wall or peninsula

> **Orientation rules:**
> - North wall cabinets: *width* in X, *depth* in Y (project south into room).
> - West wall cabinets: *length* along wall in Y, *depth* in X (project east into room).
> - South peninsula: *width* (run length) in X, *depth* in Y.

---

## 1. SCALED ASCII FLOOR PLAN

```
← X axis (West → East) ————————————————————————————————————————————————————————→

Y=0    X=0           X=83.5               X=173.5       X=233.5       X=292        X=352
       +------------------+--------------------+-------------+-------------+------------+
       |                  |                    |             |             | [6cm pipe  |
       | Top Corner       | 90cm Sink Base     | 60cm DW     | 58.5cm      |  void at   |
       | Cabinet          | (Spüle)            |             | Chimney     |  back]     |
       | 83.5×83cm        |                    |             | Pillar      |            |
        |                  |                    |             | [body 53.5  | 60cm       |
        |                  |                    |             |  +shelf 12.5]| Fridge     |
        |                  |                    |             | 5 open      | (integrated|
        |                  |                    |             | shelves     |  walnut    |
        |                  |                    |             | above ctr   |  panel)    |
Y=66   |                 /+--------------------+-------------+-------------+------------+
       |               /   ← all north wall fronts flush at Y=66 →
Y=83   +-------------|
       |             |
↓      |90cm Ct.Base |                                     ^
Y      |(hob: 80cm) |                                      |
axis   |             |                         130cm work corridor clear
(N→S)  |             |                                      |
       |             |                                      v
Y=173  +-------------+
       | 60×23cm     |
       | Towel/Board |
Y=196  +-------------+-------------+-------------+-----------------+-------+
        | 30cm VOID   | 60cm        | 60cm Oven   | 80cm Mega Drawer| 32cm  |
        | (utility)   | Robot Dock  | Cabinet     |                 | Side  |
        |             |             | (oven inside|                 | Over- |
Y=226  +=============+             |  not visible|                 | hang  |
        |             |             |  from top)  |                 |       |
        | 60cm Corner +-------------+-------------+-----------------+       |
        | Cabinet     | Cab B       |  OPEN — stool knee clearance          |
        | LR access   | (60X, 30Y)  |  (30cm bar overhang above)            |
Y=286  +---LR door---+-------------+-------------------------------+-------+
       X=0           X=60         X=120         X=180             X=260   X=292
```

**Kitchen work corridor (Y=66 to Y=196): 130cm clear**

---

## 2. SPATIAL LAYOUT & CABINETRY SPECIFICATIONS

### A. North Wall Run (Main Wash & Storage)

**X-axis span:** X=0 to X=352 (352cm total).
**Y-axis depth:** 66cm (Y=0 to Y=66). Driven by fridge niche: 6cm pipe void + 60cm fridge body. All north wall counters align flush at Y=66.
**Countertop:** Dekton Marmorio, X=0→233.5 only (does NOT extend over chimney shelves area — walnut top there instead).
**Upper cabinets:** Two 75cm-wide walnut cabinets above sink + DW (X=83.5→233.5), 33cm deep, Z=140→270 (50cm gap above counter, to ceiling). Under-cabinet LED strip lighting.

| Element | X range | Width (X) | Y range | Depth (Y) | Notes |
|---|---|---|---|---|---|
| **Top Corner Cabinet** | X=0 → X=83.5 | 83.5cm | Y=0 → Y=83 | 83cm (return leg) | Diagonal carcass. Front face: (X=83.5, Y=66) to (X=60, Y=83). ~29cm diagonal opening — confirm with fabricator. |
| **90cm Sink Base** | X=83.5 → X=173.5 | 90cm | Y=0 → Y=66 | 66cm | Houses 70cm undermount sink, Blanco waste system, and Quooker COMBI+ tank. Includes Blanco ETAGON rail accessories (cutting board, colander, drying rack). |
| **60cm Dishwasher Niche** | X=173.5 → X=233.5 | 60cm | Y=0 → Y=66 | 66cm | Bosch fully integrated. Steam deflection strip recommended under countertop above DW. |
| **58.5cm Chimney Pillar** | X=233.5 → X=292 | 58.5cm | Y=0 → Y=53.5 | 53.5cm (body) | **Structural — cannot be modified.** Base cabinet on south face: 12.5cm deep (Y=53.5→66), walnut top (no Dekton). Above counter: **5 open shelves** (12.5cm deep, Z=90→270), walnut side panels + back panel. |
| **60cm Fridge Niche** | X=292 → X=352 | 60cm | Y=0 → Y=66 | 66cm | 6cm pipe void at back (Y=0→6, sealed). **Integrated fridge** — walnut cabinet panel front. Fridge body Y=6→66. **Requires 200cm² ventilation at plinth AND top.** |

**North wall total:** 83.5 + 90 + 60 + 58.5 + 60 = **352cm** ✓

---

### B. West Wall Run (Cooking Zone)

**Y-axis span:** Y=0 to Y=196 (196cm to peninsula face).
**X-axis depth:** 60cm (X=0 to X=60) for all west wall cabinets.

| Element | Y range | Length (Y) | Depth (X) | Notes |
|---|---|---|---|---|
| **83cm Corner Return** | Y=0 → Y=83 | 83cm | 60cm | Connects to top corner cabinet on north wall. |
| **90cm Cooktop Base** | Y=83 → Y=173 | 90cm | 60cm | Houses 80cm cooktop centered (5cm clearance each side in X). Plinth drawer below for cutlery. cookConnect auto-controls the hood. |
| **60x23cm Towel/Board Cabinet** | Y=173 → Y=196 | 23cm | 60cm | Door on west face (X=0), hallway access. Vertical dividers inside for cutting boards, folded towels, trays. Confirm hallway door swing clearance. |

**West wall total to peninsula:** 83 + 90 + 23 = **196cm** ✓

---

### C. South Peninsula Run (Prep & Social)

**X-axis span:** X=0 to X=292 (292cm total).
**Y-axis depth:** 90cm total — 60cm kitchen-facing (Y=196 to Y=256) + 30cm living-room-facing (Y=256 to Y=286).

#### Kitchen-Facing Side (north face at Y=196)

| Element | X range | Width (X) | Y range | Depth (Y) | Notes |
|---|---|---|---|---|---|
| **30cm Utility Void** | X=0 → X=60 | 60cm | Y=196 → Y=226 | 30cm | Sealed behind corner cabinet. Route power for robot dock, oven 16A hardwire, oven ventilation. **Recommend removable panel** at Y=226 (inside corner cabinet) for future service access. |
| **60cm Robot Vacuum Dock** | X=60 → X=120 | 60cm | Y=196 → Y=256 | 60cm | Open base housing for Dreame L10s Pro Ultra Heat dock. Dock: 340×457×590mm (W×D×H). Floor-level opening at Y=196 (min 360mm W × 100mm H). Power routed from void. No plumbing needed (internal tanks). |
| **60cm Oven Cabinet** | X=120 → X=180 | 60cm | Y=196 → Y=256 | 60cm | Oven hidden inside cabinet (not visible from countertop). **Raised on internal shelf: oven bottom Z≈45cm, top Z≈90cm.** 200cm² vent cut-out in shelf required. Thermal air gap to robot dock partition. |
| **80cm Mega Drawer** | X=180 → X=260 | 80cm | Y=196 → Y=256 | 60cm | Primary prep storage. Consider handle-less (push-to-open) to avoid hip-catching in 130cm corridor. |
| **32cm Side Overhang** | X=260 → X=292 | 32cm | — | — | Unsupported Dekton Marmorio extension. Part of L-shaped bar. Requires hidden steel brackets. |

#### Living Room-Facing Side (south face at Y=256)

| Element | X range | Width (X) | Y range | Depth (Y) | Notes |
|---|---|---|---|---|---|
| **60cm Corner Cabinet** | X=0 → X=60 | 60cm | Y=226 → Y=286 | 60cm | Standard depth, fully reachable. LR-accessed, left-hinge door. |
| **Cabinet B** | X=60 → X=120 | 60cm | Y=256 → Y=286 | 30cm | Backs the robot dock. End panel/reveal required at X=60 (depth step from 60cm corner cab to 30cm Cab B). |
| **140cm Stool Clearance Zone** | X=120 → X=260 | 140cm | Y=256 → Y=286 | 30cm | **OPEN below countertop** — no cabinet. 30cm Dekton Marmorio bar overhang cantilevered over this zone for bar seating. Merges with 32cm side overhang to form L-shaped bar. Counter height: 90cm (Z). Suits 60–65cm bar stools with seat depth ≤28cm, no armrests. |

**Peninsula X total:** 60 + 60 + 60 + 80 + 32 = **292cm** ✓
**Peninsula Y total:** 60 + 30 = **90cm** ✓

---

## 3. APPLIANCE LIST

| # | Appliance | Model | Status | Dimensions | Location |
|---|---|---|---|---|---|
| 1 | **Fridge** | Liebherr ICBci 5182-22 | ✅ Bought, at home | W:60cm, H:177cm, D:60cm | North wall, X=292→352, **integrated walnut panel** |
| 2 | **Dishwasher** | Bosch SBD8TCX04E | ✅ Bought, at home | W:60cm, H:86.5cm, D:55cm | North wall, X=173.5→233.5 |
| 3 | **Sink** | Blanco ETAGON 700-U | ✅ Bought, at fabricator | Overall: 73×46cm, Bowl: 70×40×20cm, **graphite**, undermount | North wall, X=92→165 (in 90cm base) |
| 4 | **Tap + Boiling** | Quooker Flex Combi+ Gunmetal | ✅ Bought, at home | Tank: Ø20cm, H:49cm (58cm w/ hose) | Under sink base |
| 5 | **Cooktop** | Siemens EX80BNVV6E | ✅ Bought, at fabricator | W:79.2cm, D:51.2cm, H:5.6cm (flush induction, **no downdraft**) | West wall, Y=88.4→167.6 (centered in 90cm cabinet) |
| 6 | **Hood** | Siemens LC91KLT65 | ⏳ Planned | W:89cm, H:45cm, D:44.7cm, angled Kopffreihaube (iQ700, black glass, bottom close to wall for head clearance) | West wall, above cooktop, Z=135→180 |
| 7 | **Oven** | Siemens CM978GQB1 | ⏳ Planned | W:59.4cm, H:45.5cm, D:54.8cm (compact + microwave) | Peninsula, X=120→180, **hidden inside walnut cabinet** |

---

## 4. VENTILATION & HEAT REQUIREMENTS PER APPLIANCE

| Appliance | Ventilation needed? | Heat insulation needed? | Key requirement |
|---|---|---|---|
| **Fridge** (Liebherr) | 🔴 **Yes** | ❌ No | 200cm² grilles at plinth (intake) AND top of housing (exhaust). Confirm airflow path behind unit — 6cm pipe void is sealed, may need rear spacers or ventilation channel. |
| **Dishwasher** (Bosch) | ❌ No | ❌ No | Steam deflection strip under countertop recommended. |
| **Cooktop** (Siemens) | ❌ No | ❌ No | Standard induction hob. Internal cooling fans only. Cabinets must withstand ≥90°C. Min worktop thickness 16mm. |
| **Hood** (Siemens) | ⚠️ Filter kit needed | ❌ No | Recirculation mode requires separate purchase: Clean Air Plus kit (LZ11BKV16) or Long Life kit (LZ11BKR11). Min 450mm above cooktop surface. **Sole extraction for kitchen.** |
| **Oven** (Siemens) | 🔴 **Yes** | ⚠️ Air gap (not insulation) | 200cm² base vent + ventilation cut-out in shelf. No insulation strips on sides (per manufacturer). Air gap between oven and robot dock partition — dock contains Li-ion batteries (max 45°C). |
| **Quooker tank** | 🟡 Recommended | ❌ No | 20×20cm opening in cabinet back or base plate. 8cm clearance above tank for hoses. Place beside drain (not under sink bowl) for full 72cm internal height. Vacuum-insulated (~10W standby). |
| **Sink** (Blanco) | ❌ No | ❌ No | Passive fixture. |

---

## 5. OVEN Z-HEIGHT SPECIFICATION

The compact oven is raised on an internal shelf inside the peninsula base cabinet.

| Metric | Value |
|---|---|
| **Oven bottom (niche floor)** | **Z ≈ 45cm** |
| **Cavity center** | Z ≈ 68cm |
| **Oven top** | Z ≈ 90cm (flush with countertop) |
| **Drawer below oven** | Z=15 (plinth top) to Z=45 → 30cm storage drawer |

Ergonomic note: Cavity center at Z≈68cm is below the ideal Z=90–120cm range but is the best achievable in a peninsula base cabinet. Textbook ideal (Z≈105cm center) would require a tall housing column, which the layout cannot accommodate.

**Fabrication notes for the raised shelf:**
- 200cm² ventilation cut-out in the shelf (Siemens requirement)
- Shelf must support oven weight (~35kg)
- Must not obstruct the oven's front ventilation slot

---

## 6. COUNTERTOP — DEKTON MARMORIO 20mm

### L-Shaped Bar Overhang

| Section | Span | Overhang depth | Direction |
|---|---|---|---|
| Back seating bar | X=120 → X=260 (140cm) | 30cm | South (Y direction) |
| Side overhang | X=260 → X=292 (32cm) | Along Y | East (X direction) |
| L-corner | At ~(X=260, Y=256) | 32cm × 30cm | Both X and Y — **unsupported in both directions** |

**Structural requirements (already exceed 20cm unsupported Dekton limit):**
- Hidden steel brackets every 45–60cm along the 140cm back bar (~3–4 brackets)
- 1–2 brackets along the 32cm side
- **Hidden L-shaped steel frame at the corner** — welded flat bar (min 10mm thick × 50mm wide), bolted into cabinet carcass at X=260 and Y=256. **Mandatory — this is where Dekton bar tops crack.**
- Adhesive: flexible polyurethane (not rigid epoxy)
- Max static load on overhang: 100kg

### Extending to 35cm overhang (under consideration)
Feasible — same bracket approach, slightly deeper brackets (~30cm instead of ~25cm), possibly one extra bracket. The L-corner steel frame is needed regardless. **Confirm bar stool seat depth fits under the chosen overhang before finalizing.**

---

## 7. CRITICAL INSTALLATION NOTES

1. **Under-Sink Co-Housing:** The 90cm sink base (X=83.5→173.5) houses the Blanco waste system (~55cm Z clearance needed) and Quooker COMBI+ tank (49cm H, 58cm with hose). Sink bowl depth ~19cm reduces under-bowl height to ~53cm — potential ~2cm shortfall for waste pull-out directly under bowl. Offset waste pull-out eastward; place Quooker tank beside drain (not under bowl) for full 72cm height.

2. **Cooktop Centering:** 80cm hob centered in 90cm base cabinet — 5cm clearance each side in X.

3. **Top Corner Cabinet:** Diagonal carcass (not L-shape). Diagonal front: (X=83.5, Y=66) to (X=60, Y=83). Opening ~29cm — confirm fabricator can fit door + internals.

4. **Towel/Board Cabinet:** 23cm Y-span, 60cm X-depth. Door on west face (hallway). Confirm hallway swing clearance. Install vertical dividers for flat items.

5. **Chimney Pillar:** Structural — **cannot be modified**. Display shelf (12.5cm deep) on south face. Consider adding a lip/rail to prevent items sliding off, and an LED strip on the underside.

6. **Utility Void (30cm):** Behind corner cabinet (Y=196→226, X=0→60). Route robot dock power, oven electrical (16A), and oven ventilation through here. Install removable panel at Y=226 for future access.

7. **Robot Dock Floor Opening:** Remove plinth/kick plate section at Y=196 (X=60→120) to create unobstructed floor-level entry, min 360mm wide × 100mm tall.

8. **Oven ↔ Robot Dock Thermal:** Air gap (10–20mm) between oven niche and dock partition. No insulation strips (per Siemens). Ventilation at top and bottom of the gap. Dock Li-ion batteries must stay below 45°C.

9. **Fridge Ventilation:** 200cm² intake at plinth, 200cm² exhaust at top of housing. Confirm pipe void airflow or install rear spacers. Socket must be accessible, not directly behind unit.

10. **Hood Recirculation Kit:** Must purchase separately — hood does not ship with recirculation filters. Order LZ11BKV16 (Clean Air Plus) or LZ11BKR11 (Long Life).

---

## 8. ELECTRICAL REQUIREMENTS (TO BE SPECIFIED)

| Location | Circuit | Notes |
|---|---|---|
| Cooktop | Dedicated, per spec | Hardwired |
| Oven | 16A dedicated | Hardwired, cable routed through utility void |
| Dishwasher | Dedicated | Accessible socket, not behind unit |
| Fridge | Dedicated | Accessible socket, not behind unit |
| Quooker tank | 13A socket within 50cm of tank | Under sink |
| Robot dock | Standard socket | Inside dock niche, power routed from utility void |
| Hood | Per spec | Wall-mounted connection |
| Worktop outlets | General | North wall backsplash, peninsula countertop (pop-up/flush-mount) — **positions TBD** |

---

## 9. ROOM FINISHES & ARCHITECTURAL ELEMENTS

| Element | Specification |
|---|---|
| **Walls** | White paint (all kitchen walls) |
| **Floor** | Light oak |
| **Ceiling** | 270cm (2.7m) |
| **Cabinets** | Walnut finish (all zones: north, west, peninsula) |
| **Plinth** | Dark walnut |
| **Countertop** | Dekton Marmorio 20mm (warm Travertino-like tone) |
| **Window 1** | West wall, Y=0→66 (66cm wide), sill Z=95cm, H=140cm |
| **Window 2** | West wall, Y=196→286 (90cm wide), sill Z=95cm, H=140cm |

---

## 10. OPEN ITEMS

| Item | Status | Notes |
|---|---|---|
| Bar overhang depth | 🟡 30cm confirmed, 35cm under consideration | Feasible structurally. Confirm bar stool compatibility first. |
| Worktop outlet positions | 🔴 Not specified | Need positions for backsplash and peninsula outlets. |
| Plumbing plan | 🔴 Not specified | Water supply and drain positions for sink and DW. |
| Handle style | 🟡 Under consideration | Handle-less (push-to-open) recommended for peninsula kitchen face. |
| Backsplash | 🔴 Not specified | Material, height, extent — especially behind cooktop. |
| Lighting plan | 🟢 Partially specified | Under-cabinet LED strips on upper cabinets (above sink+DW). Hood lighting. Peninsula plinth LED, bar pendant — TBD. |
| Hood recirculation kit | 🔴 Not ordered | LZ11BKV16 or LZ11BKR11 — must purchase separately. |
| Fridge ventilation details | 🔴 Not confirmed | Pipe void airflow, plinth grille, top grille — confirm with builder. |
| Bar stool selection | 🟡 Pending | Seat height 60–65cm, depth ≤28cm, no armrests. Source before finalizing overhang. |
| DW steam deflector | 🟡 Minor | Aluminium strip under countertop above DW. ~€10. |
