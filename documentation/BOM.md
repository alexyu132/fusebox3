# Recommended Suppliers (US)
- Extrusions: Misumi (US-based)
- Pulleys, closed loop belts: Powge (Aliexpress)
- Open loop belts: Trianglelab (Aliexpress), Powge (Aliexpress)


# BOM - Non-printed

## Frame
### Extrusions

| Item | Quantity  | Notes|
|-----------------------------------------------------------------------------------------|----------|-----|
| 2020 extrusion, 407mm (407mm minimum, these can be increased to 410mm or more to give more room at the bottom of the printer) | 4  | Z axis |
| 2020 extrusion, 332mm | 4  | Y axis. The Y extrusions can be lengthened to increase Y travel without needing to modify any other components. To be able to use 300mm MGN9 rails on the Y axis, the Y extrusions should be at least 345mm, and the top Y extrusions should be at least 385mm. |
| 2020 extrusion, 372mm | 2  | Top Y axis. Must be 40mm longer than Y axis extrusions. |
| 2020 extrusion, 310mm | 4  | X axis |
| 2020 extrusion, 260mm | 2  | Bed X axis |
| 2020 extrusion, 120mm | 2  | Bed Y axis |

### Brackets and fasteners
There are two options for joining frame extrusions. The easiest and quickest, but more expensive, option is to use corner brackets everywhere. The second option is to tap the ends of the extrusions and join them with M5 hardware. This will also require access holes to be drilled through some of the extrusions. Note that this option still requires a few corner brackets to prevent certain extrusions from twisting. The required brackets are marked in yellow in the Sketchup file.

**Option 1: All corner brackets**

| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| Corner bracket (20x20x17mm) | 32 |
| M5x8mm button head | 64 |
| M5 T nut | 64 |

**Option 2: Tapped ends**

| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| Corner bracket (20x20x17mm) | 8 |
| M5x8mm button head | 16 |
| M5 T nut | 16 |
| M5x12mm button head | 24 |
| M5 washer | 24 |

## CoreXY movement (excluding print head)

| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| MGN9 linear rail with MGN9H block, 280mm long (can use 300mm length if Y extrusions are extended, see extrusions section above) | 2 |
| MGN12 linear rail with MGN12C block, 300mm | 1 |
| M3 T nut | 8 |
| M5 T nut | 20 |
| M3x6mm socket head | 8 |
| M3x8mm socket head | 16 |
| M5x8mm button head | 20 |
| M3x10mm button head | 12 |
| M3x20mm button head | 8 |
| M3x30mm button head | 2 |
| M3 nylon lock nut | 22 |
| M3 washer | 8 |
| 16T toothed 2GT idler, 3mm bore | 8 |
| 16T smooth 2GT idler, 3mm bore | 4 |
| 20T 2GT pulley, 5mm bore | 2 |
| 2GT 6mm width belt | 3M |
| NEMA 17 stepper (60+ oz-in/42+ N-cm preferred) | 2 |
| PCB endstop | 1 |

## Print head
| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| M3x6mm socket head | 4 |
| M3x25mm button head | 2 |
| M3x16mm button head | 4 |
| M3x10mm button head | 7 |
| M3 nylon lock nut | 13 |
| E3D V6 or Lite6 hotend (Bowden) | 1 |
| 4010 blower fan (ball bearing recommended) | 2 |
| 4010 axial fan (ball bearing recommended)| 1 |
| Omron D2F-L microswitch (cut one off a PCB endstop) | 1 |

Note: The blower shrouds and axial fan can optionally be attached by zip ties instead of screws. This gets rid of four M3x16mm bolts, two M3x10mm bolts, and six M3 lock nuts.

## Z axis
| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| M3x8mm socket head | 4 |
| M3x10mm button head | 14 |
| M3x20mm button head | 1 |
| M5x8mm button head | 32 |
| M5 T nut | 32 |
| M3 nylon lock nut | 15 | 
| 8mm leadscrew (300mm length, 2mm lead) and brass nut | 2 |
| 300mm length 8mm OD smooth rod | 2 |
| 710mm closed loop 2GT belt, 6mm width | 1 |
| 20T 2GT pulley, 8mm bore | 2 |
| 20T 2GT pulley, 5mm bore | 1 |
| LM8LUU bearing | 2 |
| 608 bearing | 4 |
| NEMA 17 pancake stepper (up to 25mm motor body length) | 1 |
| Ender 3 compatible heated bed (235mmx235mm) and leveling hardware | 1 |
| PCB endstop | 1 |

## Power supply
| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| M5x8mm button head | 5 |
| M5 T nut | 5 |
| M4x6mm socket head | 3 |
| M3x10mm button head | 2 |
| M3 nylon lock nut | 2 |
| Meanwell LRS-350-24 power supply | 1 |
| IEC socket with fuse and switch | 1  |
| IEC power cord | 1  |

## Stock extruder (Bowden)
This is pretty much the extruder from the FuseBox2, modified to hang below an extrusion instead of to the side. Can print flexible filament.

| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| M5x8mm button head | 2 |
| M5 T nut | 2 |
| M3x8mm socket head | 3 |
| M3x10mm button head | 1 |
| M3x25mm button head | 1 |
| M3 nylon lock nut | 1 |
| Stiff spring | 1 |
| 625 bearing | 1 |
| MK8 extruder gear | 1 |
| NEMA 17 stepper (60+ oz-in/42+ N-cm preferred) | 1 |
| PC4-M6 Bowden coupler | 1 |

## Controller and LCD

### BTT SKR and TFT24
| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| M5x8mm button head | 5 |
| M5 T nut | 5 |
| M3x25mm button head | 4 |
| M3x10mm button head | 9 |
| M3 nylon lock nut | 5 |
| M3 nylon standoff, 30mm length | 4 |
| BTT SKR 1.3 or 1.4 | 1 |
| BTT TFT24 LCD | 1 |

## Miscellaneous

| Item | Quantity  |
|-----------------------------------------------------------------------------------------|----------|
| 235x235mm print surface (PEI recommended) | 1  |
| Zip ties | Varies  |
| Cable mesh (optional) | Varies  |
| 18AWG wire for AC input | Varies  |
| 14AWG wire for main DC power | Varies  |
| Small binder/bulldog clips for bed | 4  |
| Adhesive felt or rubber feet | 4  |
