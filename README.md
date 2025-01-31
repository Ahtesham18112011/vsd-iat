#PHYSICAL DESIGN USING OPENLANE/SKY130

Physical design flow

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/479f28a0b95dda97856e9f78be94fc9961798c5b/Screenshot%20from%202025-01-31%2015-34-36.png)

Specification- tells what the chip have to do 

Synthesis- The stage where the RTL code is converted into a gate-level netlist

Physical design- a critical phase in the integrated circuit design process, responsible for transforming a circuit's logical description into a layout that can be fabricated on a silicon wafer.

Sign-off timing analysis - breaks down the design into various timing paths, meticulously calculating signal propagation delays and checking for violations of timing constraints, such as setup and hold times.

Physical verification - a process whereby an integrated circuit layout design is verified via EDA software tools to ensure correct electrical and logical functionality and manufacturability.

GDSII Tapeout- GDSII files are usually the final output product of the IC design cycle and are handed over to IC foundries for IC fabrication.

OPENLANE- OpenLane is an innovative silicon implementation platform that supports open-source tools such as Yosys, OpenROAD, Magic ETC.


After synthesis we need to design a floorplan for the cells. It estimates chip areas, delay, and congestion caused by wiring, providing crucial feedback for the design process.

CMOS - the small amount of memory on a motherboard that stores the BIOS settings, including system time and hardware configuration. It is made up of PMOS and NMOS.

![image alt](
