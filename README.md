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

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/9645b2cbeb3f19618a3a982d6b3e3c347e47c76f/Screenshot%20from%202025-01-31%2014-31-44.png)

CTS (Clock Tree Synthesis)- Clock Tree Synthesis (CTS) is the technique of balancing the clock delay to all clock inputs by inserting buffers/inverters along the clock routes.

After CTS we need the Placement and Routing of the chip. placement, involves deciding where to place all electronic components, circuitry, and logic elements in a generally limited amount of space. This is followed by routing, which decides the exact design of all the wires needed to connect the placed components.The detailed routing is called TritonRoute and detailed routing is better because 
it has has a proper detailed routing of wires.



LABS
![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/4341811310dc93d2e5bc7c0169d72f5d3c15f2f2/Screenshot%20from%202025-01-31%2010-27-59.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/aa63bf3a71ccccd912e694ecb7fa6ff6cb5658a3/Screenshot%20from%202025-01-31%2010-31-44.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/fc68c442c9828d232eae90b74cfbb4a9f5be768d/Screenshot%20from%202025-01-31%2010-37-13.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/638c6f0100cacc627b7fd6d7ab64dbe53e6c2318/Screenshot%20from%202025-01-31%2010-37-20.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/c0af0b46d2abc88e8c2a6dbf6cac7c7e7ea13cd5/Screenshot%20from%202025-01-31%2010-37-25.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/a1799d7759766b76aa20c38f2a6c64fac8aac7bd/Screenshot%20from%202025-01-31%2010-39-25.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/0a84f45419f09f545a12218324eb8d1f1041d33a/Screenshot%20from%202025-01-31%2010-41-45.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/af196879a36f254cd980c749e80b2e43a1a692da/Screenshot%20from%202025-01-31%2010-41-47.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/5bda2497eb097b0c0cfa6bb0b18add6ab56f039d/Screenshot%20from%202025-01-31%2010-51-34.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/74bf936a5290d286f1b7406817a15ecc1a206fac/Screenshot%20from%202025-01-31%2011-04-16.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/922bf482c7329575c7a0b46c35a5cc089287a0cf/Screenshot%20from%202025-01-31%2011-16-06.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/04ff8d8adb5f9dfedcde44e8141cc9d6b5831355/Screenshot%20from%202025-01-31%2011-16-06.png)

![image alt](https://github.com/Ahtesham18112011/vsd-iat/blob/9029f6c72b421d9be83f9de78316e31405c08b2f/Screenshot%20from%202025-01-31%2011-16-15.png)

![image alt]()

![image alt]()

![image alt]()

![image alt]()

![image alt]()

![image alt]()

![image alt]()
