---
title: "Implemention of a 12-Hour Clock System on an FPGA Board using Verilog"
excerpt: "<br/><img src='/images/FPGA12hourClockGithub.jpg' style='width: 400px;'>"
collection: portfolio
---

The aim of this project was to design and implement a 12-hour clock system on an FPGA board using Verilog. The system was required to accurately count time and display it on the seven-segment display in a user-friendly manner.
The project involved the development of Verilog code to create a 12-hour clock. This code encompassed functionalities essential for time counting and managing the display on the seven-segment display.
Utilizing the resources of the FPGA board, the project focused on synchronizing clock signals, efficiently managing time counters, and interfacing with the seven-segment display to ensure smooth operation of the clock system.
One significant challenge encountered was coordinating the activation of different seven-segment displays based on the current time. This was successfully addressed by dynamically enabling/disabling display segments to depict the appropriate digits at each time interval, ensuring accurate time representation.
<div style="display: flex; justify-content: center;">
    <figure style="margin-right: 20px;">
        <img src='/images/read_curve_Si.png' style="width: 100%;">
        <figcaption style="text-align: center;">Read Noise Margin Calculation</figcaption>
    </figure>
    <figure>
        <img src='/images/write_curve_Si.png' style="width: 100%;">
        <figcaption style="text-align: center;">Write Noise Margin Calculation</figcaption>
    </figure>
</div>
