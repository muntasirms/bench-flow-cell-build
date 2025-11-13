# Bench-scale Flow Cell Build
Build your own flow cell, for use in standardized flow battery and slurry electrode experimental systems. Can use electrolyte chamber for half cell measurements or two of the same for full cell measurements. 

## Bill of Materials 
### In this repo:
- 1 "Inlet" type plate fabricated per "half cell" tested (i.e. for half cell measurements, only 1 inlet plate required)
- 1 "Cell Channel" type plate fabricated per "half cell" tested. Can adjust cell thickness to resolution of your print.
- 1 "Non conductive plate" type plate fabricated per "half cell tested", unless machining current collector directly
- For half cell measurements, 1 electrolyte chamber
### To purchase
- Separator material (chemistry specific - I typically use a size exclusion/non-ion selective separator. For example a [polypropylene size exclusion separator](https://celgard.shop/collections/all)
- Gasket sheet (I use [silicone](https://www.mcmaster.com/8525T41/). Will need to cut 
- [M4 threaded rods](https://www.mcmaster.com/94185A145/) (or bolts if preferred). Nonconductive material if using graphite plate or metal plate current collector.
- [M4 nuts](https://www.mcmaster.com/94150A335/), I typically use flange nuts but their diameter may be too large for some of the inlet channels.
- IDEX fittings and associated tubing
- 1/8" EPDM O-ring (or material of choice)
- Graphite foil or graphite plate if machining current collector
- Glue (superglue works well, conductive glue would be better)
### Tools
- Hand drill or drill press
- Bench vice
- 1/4"-28 Bottom Tap

## (Non-comprehensive) Instructions
1. Print parts as per the bill of materials.
    - Note filament materials - make sure your printed materials resist your chosen electrolyte materials. In general, PP is resistant to most aqueous electrolytes across a broad range of pHs, but is much more mercurial to print. PLA works fine for most acidic/mild pH electrolytes but will hydrolyze in concentrated base. 
2. Into the printed inlet plate, use the bottom tap to create threading for IDEX fittings
3. Place 1/8" O-rings into threaded holes
    - sometimes the threads will leak even with the IDEX ferrules due to print lines not sitting flush with the ferrule. The O-rings seem to consistently fix this issue even relatively high flowrates/pressure.
4. Cut gasket sheeting
    - can use a vectorized version of the cell channel model to cut using a cutting tool like a Cricut. I usually just use a printed cell channel part and use it as a stencil to cut the same shape out of the gasket sheet. For holes, a typical hole punch works and accommodates M4 bolts well.
5. Cut strip of separator material such that it covers the entire with of the cell channel but fits within the total width between two of the bolts.
6. Taking non-conductive plate print, glue graphite foil to cover at least the portion of the non-conductive plate exposed to the cell channel, and 

# Fine Print

## License Summary
CC BY-NC-SA 4.0
- **Attribution (BY)**: Please give appropriate credit.
- **Non-Commercial (NC)**: Usage is limited to research, educational, and personal applications.
- **Share-Alike (SA)**: Any derivatives must be shared under the same license.

## Allowed Uses
- Personal projects
- Educational or research purposes
- Non-commercial open-source projects
- Modifying and sharing designs under the same license

## Disallowed Uses
- Selling the files or any product derived from them
- Using the designs in a commercial project without explicit permission
- Removing attribution or license information
