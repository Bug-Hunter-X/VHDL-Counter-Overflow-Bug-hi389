# VHDL Counter Overflow Bug
This repository demonstrates a common error in VHDL: an unbounded counter that can overflow, leading to unexpected behavior.

The `counter_bug.vhdl` file contains a VHDL counter that increments on each rising edge of the clock. However, it lacks a mechanism to prevent overflow when the counter reaches its maximum value (7 in this case).

The solution (`counter_solution.vhdl`) shows how to correctly handle potential overflow issues and prevent unpredictable behavior.