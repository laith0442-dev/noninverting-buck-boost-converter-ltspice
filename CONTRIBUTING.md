# Contributing to Closed-Loop Non-Inverting Buck-Boost Converter LTspice Project

Thank you for your interest in contributing! This open-source power electronics project aims to provide clean, rigorous, and verified simulation models for education, research, and industrial power supply prototyping.

## How to Contribute

1. **Reporting Issues & Bugs**:
   - If you encounter convergence anomalies, unexpected simulation behavior, or library discrepancies across LTspice versions (e.g., LTspice XVII vs LTspice 24), please open an issue describing:
     - LTspice version and operating system.
     - Simulation command and convergence parameters used.
     - Observed waveform vs expected waveform.

2. **Suggesting Enhancements**:
   - Topology extensions (e.g., 4-switch synchronous buck-boost with transition control).
   - Alternative compensation schemes (e.g., Type-III error amplifier, Peak Current Mode Control).
   - Thermal and loss estimation scripts (MATLAB / Python).
   - PCB layout and hardware prototypes.

3. **Submitting Pull Requests**:
   - Fork the repository and create a descriptive branch: `git checkout -b feature/type3-compensation`.
   - Make sure your `.asc` schematic is clean, properly aligned, and uses standard built-in LTspice components where possible.
   - Remove any generated simulation artifacts (`.raw`, `.log`, `.op.raw`) before committing.
   - Provide screenshots of schematic changes and simulated waveforms in your PR description.
   - Adhere to clear commit messages.

## Code of Conduct

Please maintain a respectful, constructive, and collaborative tone when opening issues or participating in discussions.
