# EBS-Board v4.0

> **Custom Arduino Nano-compatible microcontroller board** same pinout, same feature set, compact square form factor. Designed from scratch in KiCad, manufactured via JLCPCB.

---

## Overview

EBS-Board v4.0 is a custom-designed microcontroller development board functionally identical to the Arduino Nano but built on a square PCB designed and laid out entirely from scratch.

Rather than using an off-the-shelf Nano, this board provides full control over the hardware: component placement, form factor, and future iteration. Same peripherals, same I/O, custom geometry.

---

## Features

- ATmega328P microcontroller (Arduino Nano-equivalent)
- Same digital/analog pin layout as Arduino Nano
- USB serial (CH340 or equivalent) for programming and serial monitor
- Onboard voltage regulation (5V rail)
- Square compact form factor custom footprint
- Arduino IDE compatible (no driver changes needed)

---

## Tools & Process

| Stage | Tool |
|-------|------|
| Schematic | KiCad |
| PCB Layout | KiCad |
| 3D Verification | KiCad 3D Viewer |
| Manufacturing | JLCPCB (Gerber export) |

---

## Repository Contents

```
/schematics   → KiCad schematic files (.sch)
/pcb      → PCB layout files (.kicad_pcb)
/gerbers    → Production-ready Gerber files
/bom      → Bill of materials
```

---

## Skills Demonstrated

`KiCad` `PCB Layout` `Schematic Design` `ATmega328P` `Embedded Hardware` `Gerber Export` `PCB Manufacturing`

---

## Status

✅ **v4.0 design complete · Manufactured and tested**
