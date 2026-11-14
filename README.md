# Box of Beezz: drone synth

Box of Beezz is a drone synth with 9 transistor oscillators. Each oscillator has an LED that flashes with its signal.

<img width="1024" height="680" alt="Box of Beezz" src="https://github.com/user-attachments/assets/e67e8a4f-6b84-4075-bac1-379a7c029af4" />

## Build guide and video

- Step-by-step build guide on Instructables: [Box of Beezz Drone Synth](https://www.instructables.com/Box-of-Beezz-Drone-Synth/)
- Video on YouTube: [Box of Beezz](https://youtu.be/9Q7pgyfTjew)

## How it works

- Each oscillator is a relaxation oscillator. A capacitor charges to a threshold, then a transistor discharges it. This repeats, and makes a sawtooth wave.
- Different capacitor values give different frequencies.
- 9 oscillators together make a rich drone sound.
- A master tone knob changes the sound.
- A control voltage (CV) output lets you connect the synth to a sequencer.

## What you need

- All parts are in the parts list (`Drone Synth - Parts List.xlsx`).
- There are two versions of the PCB:
  - Version 1: the Gerber files are in `Drone Synth V1 - gerber files.zip`. The Eagle files and the schematic are in `Box of Beezz - Drone Synth V1/`.
  - Version 2: the Gerber files, the Eagle files and the schematic are in `Box of Beezz - Drone Synth V2/`.
- There are two front panel designs, with and without a speaker. They are in `Front Panel/`.

## Build it

The Instructables guide shows each step, with photos. In short:

1. Send the Gerber files to a PCB maker.
2. Get the parts in the parts list.
3. Solder the parts to the PCB.
4. Connect the power and test the circuit.

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `Drone Synth V1 - gerber files.zip` | Gerber files for the version 1 PCB, ready to order |
| `Box of Beezz - Drone Synth V1/` | Eagle files and schematic for version 1 |
| `Box of Beezz - Drone Synth V2/` | Gerber files, Eagle files and schematic for version 2 |
| `Front Panel/` | Front panel designs, with and without a speaker (SVG and PDF) |
| `Drone Synth - Parts List.xlsx` | Parts list |

## Credits

- Based on the simple oscillator in the [Circle Drone of Doom](https://www.lookmumnocomputer.com/projects#/circledroneofdoom) by Look Mum No Computer.
- PCB and build: Marcus ([lonesoulsurfer](https://github.com/lonesoulsurfer)).

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

This project uses the [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE) (CERN-OHL-S-2.0). Copyright (c) 2025 Marcus (lonesoulsurfer).

You can make, change and sell boards from these files. If you share or sell a changed design, you must also share the changed design files under the same licence.
