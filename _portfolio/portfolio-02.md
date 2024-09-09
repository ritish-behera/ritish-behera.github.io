---
title: "Implemention of a 12-Hour Clock System on an FPGA Board using Verilog and GDS Layout Generation of the Design"
excerpt: "NIT Warangal<br/><img src='/images/FPGA12hourClockGithub.jpg' style='width: 400px;'>"
collection: portfolio
---

The aim of this project was to design and implement a 12-hour clock system on an FPGA board using Verilog. The system was required to accurately count time and display it on the seven-segment display in a user-friendly manner.

Utilizing the resources of the FPGA board, the project focused on synchronizing clock signals, efficiently managing time counters, and interfacing with the seven-segment display to ensure smooth operation of the clock system.

One significant challenge encountered was coordinating the activation of different seven-segment displays based on the current time. This was successfully addressed by dynamically enabling/disabling display segments to depict the appropriate digits at each time interval, ensuring accurate time representation.

Afterwards, I have moved to use the design for tapeout through open-source Sky130nm technology node with complete RTL to GDS flow, via a project called "Tiny Tapeouts" which takes the RTL code to tapeout ready design to be fabricted on their custom board.

Find the design files [here](https://drive.google.com/drive/folders/1LUMGoMlJ5kE5TtMGXvKBaiLcMPR9-IhW?usp=sharing).

Check out the GDS layout and cell information below. For a 3D view of the design please visit- [https://gds-viewer.tinytapeout.com/?model=https://ritish-behera.github.io/Tiny_Tapeout_12HourClock/tinytapeout.gds.gltf](https://gds-viewer.tinytapeout.com/?model=https://ritish-behera.github.io/Tiny_Tapeout_12HourClock/tinytapeout.gds.gltf)

<figure style="margin-right: 20px;">
        <img src='/images/FPGA12HourClock.jpg' style="width: 100%;">
        <figcaption style="text-align: center;">12 Hour Digital Clock on SSD of FPGA Board</figcaption>
</figure>

<figure style="margin-right: 20px;">
        <img src='/images/12HourClockTapeOutChipLayout.png' style="width: 100%;">
        <figcaption style="text-align: center;">3D GDS Layout</figcaption>
</figure>

<figure style="margin-right: 20px;">
        <img src='/images/CellUsed.png' style="width: 100%;">
        <figcaption style="text-align: center;">Report of Cell Used in the Design</figcaption>
</figure>
