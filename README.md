# Digital-Alarm-Clock

Tech Stack: Cadence, RTL Synthesis, PuTTY, Xming


Designed a fully functional digital alarm clock in Verilog HDL with modular blocks for time counting (HH:MM:SS), reset logic and alarm triggers.

Simulated behavioral timing using a testbench (1 clock edge = 1 simulated second) to validate state transitions across all functional parameters.

Implemented a user-configurable reset mechanism allowing hour and minute override via input bits and an alarm system that activates an alarm_flag at a pre-set time and holds it high for exactly 60 seconds, verified through timing diagram analysis in Cadence.

Synthesized the design using slow.lib and fast.lib standard cell libraries in Cadence to analyze power, gate count, and area.
