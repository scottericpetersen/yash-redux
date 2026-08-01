# YASH Remix — Bill of Materials

Based on `yash_redux.kicad_sch`.

## ICs

| Ref | Part | Notes |
|---|---|---|
| U1 | LF398_DIP8 | Sample & hold |
| U2 | TL082 | Dual op-amp — side A: noise gain/bias stage; side B: portamento buffer |
| U3 (+U3A) | 4093 | Trigger osc, sample-rate osc, hold-logic buffer |
| U4 | 4093 | Test oscillator |

## Transistors / Diodes

| Ref | Part | Notes |
|---|---|---|
| Q1–Q4 | 2N3904 | Q1 = trigger stage; Q2–Q4 = white noise |
| D1 | 1N4148 | |
| D2 | LED | |

## Resistors

| Value | Qty | Refs |
|---|---|---|
| 1MΩ | 2 | R6, RV1 |
| 470kΩ | 2 | R8, R11 |
| 100kΩ | 2 | R9, R12 |
| 47kΩ | 1 | R14 |
| 22kΩ | 1 | R17 |
| 10kΩ | 5 | R7, R10, R13, R15, R18 |
| 5.7kΩ | 1 | R16a |
| 5.6kΩ | 1 | R4 |
| 4.7kΩ | 1 | R2 |
| 2.2kΩ | 3 | R1, R3, R16b |
| 2kΩ | 1 | R5 |

Note: R16 in the schematic is drawn as 1 resistor (7.9k). This is actually two resistors:  R16a 5.7k + R16b 2.2k = 7.9k combined.

## Capacitors

| Value | Qty | Refs |
|---|---|---|
| 10µF | 1 | C3 |
| 4.7µF | 1 | C9 |
| 0.1µF | 4 | C1, C6, C7, C8 |
| 470nF | 3 | C2, C4, C5 |

## Potentiometers

| Value | Qty | Refs |
|---|---|---|
| 1MΩ | 1 | RV1 |
