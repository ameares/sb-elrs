# Drone ELRS

A small ExpressLRS PCB module for an FPV drone.

## Board

| Front | Back |
|-------|------|
| ![Board Front](docs/images/board-front.png) | ![Board Back](docs/images/board-back.png) |

## Schematic

📄 [Schematic PDF](docs/schematic.pdf)

## Development

Documentation is auto-generated on every `git commit` via the Makefile:
- PCB renders (front and back) are updated from the latest board file
- Schematic PDF is exported from the root schematic
- DRC and ERC checks are run and results saved to `docs/`