# mini-usbc-led-desk-light

A compact USB-C powered LED desk light project for studying and desk work.

## Project Goal
Design and build a small, practical desk light that:
- Uses USB-C power
- Includes an on/off switch
- Supports adjustable brightness
- Stays compact for student desk use

## What makes it mine
My version focuses on a compact study-light form factor with simple controls, clean wiring, and practical everyday use on a student desk.

## Planned Hardware
- USB-C 5V power input
- LED array (warm/cool white depending on test results)
- Brightness control (PWM dimming with microcontroller, or analog dimmer fallback)
- Power switch
- Current-limiting and protection components (resistors, optional fuse/protection)
- Compact custom enclosure

## Design Decisions to Document
- LED type, count, and placement
- Brightness range and dimming method
- Thermal handling for long study sessions
- Enclosure size, tilt/angle, and cable routing
- Tradeoffs between simplicity, cost, and brightness quality

## Build and Test Plan
1. Prototype the power + LED circuit on breadboard.
2. Verify safe current draw from USB-C 5V supply.
3. Implement and test brightness control levels.
4. Validate switch behavior and startup state.
5. Run 30-60 minute thermal and stability checks.
6. Finalize compact enclosure and retest usability.

## Improvement Log
Track updates during the project:
- v0.1: Initial concept and requirements
- v0.2: First working circuit
- v0.3: Brightness control tuning
- v0.4: Enclosure refinement and long-run testing

## Notes
This repository will be used to document components, design choices, testing results, and improvements through each iteration.
