# 1S Li-ion Battery Protection PCB

## Overview

A 2-layer PCB design for a 1S Li-ion battery protection circuit developed in KiCad. The design uses a DW01A battery protection IC and back-to-back AO3400A N-channel MOSFETs for battery protection.

## Features

- 1S Li-ion battery protection
- DW01A protection IC
- Back-to-back AO3400A MOSFETs
- Overcharge, overdischarge and overcurrent protection
- 2-layer PCB layout
- ERC/DRC validation
- Gerber and drill file generation
- KiCad 3D PCB visualization

## Hardware

- DW01A
- AO3400A × 2
- 470 Ω resistor
- 2 kΩ resistor
- 100 nF capacitor
- JST PH connectors

## Design Tools

- KiCad
- PCB Layout & Routing
- Schematic Capture
- ERC/DRC
- Gerber Generation

## Project Status

PCB design completed and validated in KiCad.

Physical fabrication and hardware testing have not yet been performed.

## Project Structure

```text
KiCad/          → Schematic, PCB and project files
Gerbers/        → Manufacturing files
Documentation/  → Project images and screenshots
