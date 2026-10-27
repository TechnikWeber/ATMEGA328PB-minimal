# ATmega328PB minimal board

<p>
  <img alt="MCU: ATmega328PB" src="https://img.shields.io/badge/MCU-ATmega328PB-blue">
  <img alt="PCB: KiCad" src="https://img.shields.io/badge/PCB-KiCad-informational">
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-green"></a>
</p>

A minimal breakout board for the ATmega328PB (TQFP-32): just what the chip needs to run,
be programmed and talk to a PC — a starting point for small AVR projects.

![ATmega328PB minimal board, rendered in KiCad](docs/board-3d.png)

## What is on it

| Part | Purpose |
|---|---|
| ATmega328PB-A (TQFP-32) | The microcontroller, on its internal oscillator |
| 2×3 ISP header | Programming with any AVR ISP programmer (USBasp, AVRISP mkII, …) |
| 1×6 header for an FTDI TTL-232R-3V3 cable | Serial connection and 3.3 V power from a USB-UART cable; DTR/RTS allows auto-reset for a bootloader |
| RESET and USER buttons | Reset, and one button for your own firmware |
| LED with 220 Ω | Status LED |
| 3 × 100 nF, 10 kΩ reset pull-up | Decoupling and reset |

## Files

- `ATMEGA328PB_Minimal.kicad_sch` / `.kicad_pcb` — schematic and PCB (KiCad)

<img width="688" alt="Board layout" src="https://github.com/user-attachments/assets/f492bd5b-7b2d-4ec0-a15a-2f61fd1acfb3" />

## License

[MIT](LICENSE).
