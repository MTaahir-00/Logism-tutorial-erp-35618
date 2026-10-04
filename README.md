# ExampleSignalGen_01

Logisim-evolution (v3.4.5) signal generator circuit.

## Contents
- `ExampleSignalGen_01.circ` - the circuit file

## How to open
1. Install [Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution) (built with v3.4.5).
2. File > Open > `ExampleSignalGen_01.circ`.
3. Go to Simulate > Ticks Enabled (or Ctrl+K) to start the clock.

## What it contains
- 4-bit counter driven by a clock
- 5 comparators against constants 0x0, 0x2, 0xA, 0x5, 0xA
- 2 J-K flip-flops
- 3 buzzers (0x215, 0x320, 0x42A) and a digital oscilloscope
- Binary-to-BCD converter with three 7-segment displays
