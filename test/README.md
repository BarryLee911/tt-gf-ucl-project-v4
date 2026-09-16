# Interface tests

Run `make` for RTL or use the official GF workflow for gate-level tests.
The tests use external pins only, an independent 2048-sample area queue, and a peak candidate model.
Levels 0, 1, and 5 use real 80 MHz clocks and the default 80,000-clock handoff.
All output pins are checked from the first reset edge; X/Z fails.
The GF testbench connects VPWR/VGND. Functional simulation and physical timing are checked separately.
