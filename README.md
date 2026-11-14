# Folded-Cascode-Operational-Amplifier

This repository contains the schematic design and simulation data for a PMOS-input CMOS folded cascode operational amplifier, developed and verified using Cadence Virtuoso and Spectre. The core architecture relies on strictly internal resistor-based biasing to ensure that all transistors operate continuously in deep Region 2 saturation. This approach provides a highly stable 610.89 mV DC output bias for the circuit.

Comprehensive performance simulations demonstrate a 42.0 dB open-loop gain paired with an 88.53 degree phase margin to guarantee high stability across operations. The design was heavily optimized for a strong balance of speed and power efficiency, achieving an 86 V/us slew rate while maintaining a sub-milliwatt power footprint of just 0.911 mW. Furthermore, the amplifier delivers a 65.61 dB CMRR, a 42.09 dB VDD PSRR, and supports a 0.50 V linear input common-mode range and output swing span. 🌮

The report for Phase 1 of this project is located in ece51214_phase_1_project_report.pdf.