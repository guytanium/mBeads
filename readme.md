mBeads is a 12hp remix of [Mutable Instruments' Beads](https://pichenettes.github.io/mutable-instruments-documentation/modules/beads/) by Emilie Gillet.

Available to purchase [from PATCHPARTY](https://patchparty.shop/products/mi-mbeads-beads-remix) or from [Reverb](https://reverb.com/au/item/104091533-mi-mbeads-granular-texture-synthesizer-eurorack-mutable-instruments-beads-remix-in-12hp).![Image of module](images/mbeads.jpg)

Like the OG, this PCB is designed around 0402 passives, however with some work I believe it could be converted to the more diy-friendly 0603. So for now the existing gerbers and BOM is available while I re-work the pcb.

## Changes:

- Eagle files imported into KiCad.
- Single PCB split into two narrower PCBs, using pin headers as board-to-board connectors with m3 standoff for strength.
- Both PCBs only require single sided PCBA for SMD parts.
- BOM changes:
  - THT LEDs swapped for SMD using panel translucency (or light pipes).
  - LP4OA1PBCT* illuminated switch swapped for PB6149L* style.
  - Broadcom ASMB-KTF0-0A306 switched to OSRAM LRTBGVSR* RGB LED.
  - New LEDs require resistor changes.
  - SMD tact switches now standard THT parts.
  - Most footprints changed from Eagle to KiCad standard library.
  - Many passives (resistors, caps, inductors, diodes, etc) have had footprints changed due to availability.
  - TODO: Swap all 0402 passives for 0603.
  - TODO: Add correct resistor values for LEDs.

License
-------

[cc-by-sa-3.0](https://creativecommons.org/licenses/by-sa/3.0/)

