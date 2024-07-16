---
title: "Physical Design Optimization and Timing Analysis of RISC-V Processor Using OpenLane"
excerpt: "VSD Workshop <br/><img src='/images/VSD_PD_Github.png' style='width: 400px;'>"
collection: portfolio
---
<figure style="margin-right: 20px;">
    <img src='/images/VSD_PD_Github1.png' style="width: 100%;">
    <figcaption style="text-align: center;">Picorv32a RISC-V SoC Model</figcaption>
</figure>

The following workshop involved the complete RTL to GDSII design flow of a RISC-V processor architecture considering all the design steps starting from
RTL synthesis, STA, DFT, floorplan, placement, CTS, routing, physical verification as well as sign-off of the chip through the openLANE ASIC design flow
with the Skywater 130nm PDK libraries. Moreover, this involved integration of a characterized custom cell into the design and hence place&route operation 
were performed while verifying the timing constraints.

The github repo can be viewed [here](https://github.com/ritish-behera/VSD-PhysicalDesign).


<figure style="margin-right: 20px;">
    <img src='/images/VSD_PD_Github11.png' style="width: 100%;">
    <figcaption style="text-align: center;">Floorplan Results</figcaption>
</figure>

<figure>
    <img src='/images/VSD_PD_Github2.png' style="width: 100%;">
    <figcaption style="text-align: center;">Placement Results</figcaption>
</figure>

<figure style="margin-right: 20px;">
    <img src='/images/VSD_PD_Github3.png' style="width: 100%;">
    <figcaption style="text-align: center;">Custom Cell (Inverter)</figcaption>
</figure>

<figure>
    <img src='/images/VSD_PD_Github4.png' style="width: 100%;">
    <figcaption style="text-align: center;">Post-Placement Results after Integration</figcaption>
</figure>

<figure style="margin-right: 20px;">
    <img src='/images/VSD_PD_Github5.png' style="width: 100%;">
    <figcaption style="text-align: center;">Post-Routing Results1</figcaption>
</figure>

<figure>
    <img src='/images/VSD_PD_Github6.png' style="width: 100%;">
    <figcaption style="text-align: center;">Post-Routing Results2</figcaption>
</figure>


