
---
title: "Physical Design Optimization and Timing Analysis of RISC-V Processor Using OpenLane"
excerpt: "VSD Workshop <br/><img src='/images/Hybrid6TSRAMLayout3D.png' style='width: 400px;'>"
collection: portfolio
---
<div style="display: flex; justify-content: center;">
    <figure style="margin-right: 20px;">
        <img src='/images/MoS2_Si_SRAMGithub.png' style="width: 100%;">
        <figcaption style="text-align: center;">Hybrid 6T SRAM Schematic</figcaption>
    </figure>
    <figure>
        <img src='/images/2D_SRAM_LayoutGithub.png' style="width: 100%;">
        <figcaption style="text-align: center;">2D Layout Model</figcaption>
    </figure>
</div>

The following workshop involved the complete RTL to GDSII design flow of a RISC-V processor architecture considering all the design steps starting from
RTL synthesis, STA, DFT, floorplan, placement, CTS, routing, physical verification as well as sign-off of the chip through the openLANE ASIC design flow
with the Skywater 130nm PDK libraries. Moreover, this involved integration of a characterized custom cell into the design and hence place&route operation 
were performed while verifying the timing constraints.

The github repo can be viewed [here](https://github.com/ritish-behera/VSD-PhysicalDesign).
