# Digital VLSI SoC Design & Planning
VLSI (Very Large Scale Integration) is the process of designing and manufacturing Integrated Circuits (ICs) that integrate thousands to billions of transistors onto a single silicon wafer. These transistors are interconnected to form highly complex circuits that perform specific functions, ranging from simple arithmetic operations to advanced data processing.
### VLSI design flow
 The VLSI design flow is a structured methodology for developing integrated circuits efficiently and effectively. It guides designers through key stages, including specification, design entry, synthesis, verification, layout, and fabrication. The flow aims to minimize design time while ensuring high-quality and reliable products. By breaking the process into manageable tasks, it helps focus on specific design aspects at each stage. This approach streamlines the workflow, reduces errors, and boosts team productivity.
<details>
  <summary>Typical design flow</summary>

  <p align="center">
    <img src="https://github.com/user-attachments/assets/94bce051-0617-4c82-b17e-9c460a3ca3e8" width="250" />
  </p>

  1. **Design Specification**: Defines the functional and performance requirements of the design, including target performance and design constraints.
  2. **Behavioral Description**: Describes the system's functionality at a high level, focusing on what the system should do without detailing its hardware implementation.
  3. **RTL Description (HDL)**: Specifies the design using Hardware Description Language (HDL), detailing the logic and structure in a synthesizable form.
  4. **Functional Verification and Testing**: Ensures the design behaves as expected by simulating the RTL code and checking for correctness.
  5. **Logic Synthesis**: Transforms the RTL code into a gate-level representation, optimizing the design for area, power, and speed.
  6. **Gate-Level Netlist**: Produces a collection of logic gates and their interconnections, representing the synthesized design.
  7. **Logical Verification and Testing**: Verifies the gate-level design by running functional tests to check its correctness against the original specification.
  8. **Floor Planning, Automatic Place & Route**: Determines the physical placement of components on the chip and routes the interconnections to meet timing and area constraints.
  9. **Physical Layout**: Generates the final layout design, specifying the exact physical locations and connections for all components.
  10. **Layout Verification**: Ensures that the physical layout adheres to design rules and checks for issues such as signal integrity and manufacturability.
  11. **Implementation**: Finalizes the design for manufacturing by preparing the GDSII file, which is used in the fabrication process.

</details>

## Content
- [Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK](#day-1---inception-of-open-source-eda-openlane-and-sky130-pdk)
- [Day 2 - Good floorplan vs bad floorplan and introduction to library cells](#day-2---good-floorplan-vs-bad-floorplan-and-introduction-to-library-cells)
- [Day 3 - Design library cell using Magic Layout and ngspice characterization](#day-3---design-library-cell-using-magic-layout-and-ngspice-characterization)
- [Day 4 - Pre-Layout timing analysis and importance and good clock tree](#day-4---pre-layout-timing-analysis-and-importance-and-good-clock-tree)
- [Day 5 - Final steps for RTL2GDS using tritonRoute and openSTA](#day-5---final-steps-for-rtl2gds-using-tritonroute-and-opensta)
## Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
## Day 2 - Good floorplan vs bad floorplan and introduction to library cells
## Day 3 - Design library cell using Magic Layout and ngspice characterization
## Day 4 - Pre-Layout timing analysis and importance and good clock tree
## Day 5 - Final steps for RTL2GDS using tritonRoute and openSTA
