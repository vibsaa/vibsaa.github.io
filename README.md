Vibhanshu Sharma
======

#### Strong engineering professional with a Master of Technology - focused in Embedded Systems and VLSI from Netaji Subhas Institute of Technology. Experienced Engineer with a demonstrated history of working with AVR microcontrollers, FPGA's, RTL, Application-Specific Integrated Circuits (ASIC), and Communication protocols. Currently working with AMD as design verification engineer.
###### [ [Github@vibsaa](https://github.com/vibsaa) ] . [[ vibhanshusharma04@gmail.com ](vibhanshusharma04@gmail.com)] . [[ LinkedIn ](https://www.linkedin.com/in/vibhanshu-sharma-201462140/)]

Projects
--------
**[*Interrupt controller with APB interface*](https://github.com/vibsaa/OpenSource_verilog/tree/main/Master/14_Interrupt_controller_with_APB_Interface)** (Nov 21- Nov 21)
- Interrupt is a mechanism used by peripherals(slaves- usually slower than the processor) to get processor attention.
- An interrupt controller with functionality of coding priority register as per need is implemented, this coding of the priority register by processor is done using APB interface(APB signals-pclk, penable, pready, prdata, pwrdata, pwrite, etc.)
- the interrupt mechanism is implemented using 3 state fsm.

**[*Synchronous and Asynchronous FIFO design*](https://github.com/vibsaa/OpenSource_verilog/tree/main/Master/13_FIFO)** (Oct 21- Oct 21)
- During data transfers there is a possibilty where one component can produce data at a much faster rate than the other component that consumes it, this creates bottleneck in the chip operation. In such cases we use a buffer/FIFO, which will make both components work at their own speed. (Asynchronous FIFO).
- Parametrized FIFO is designed .
- As there are two clocks of different frequency, signals in one domain need to be synchronized into other domain to make condition checking possible. one stage synchronizer is used for this.
- the problem of intermediary stages is solved using gray code encoding of the signals that needed to be synchronized .
- implemented various testcase to check working.
- Vim is used as editor & ModelSim is used for RTL simulation.

**[*Memory Verilog implementation to check both frontdoor & backdoor access*](https://github.com/vibsaa/OpenSource_verilog/blob/main/Master/7_memory_access/memory2_tb2.v)** (Oct 21- Oct 21)
- implemented reusable memory using parameters.
- implemented Testbench using task and functions.
- implemented various testcase to check frontdoor and backdoor access.
- Vim is used as editor & ModelSim is used for RTL simulation.

**[*Custom clock generation*](https://github.com/vibsaa/OpenSource_verilog/tree/main/Master/4_clock_variety)** (Oct 21- Oct 21)
- implemented clock generator in verilog that can generate clock of user provided frequency, duty cycle and jitter.
- A logic to display frequency values in terminal is also implemented.

**[*Condition Monitoring of Industrial & Commercial Refrigeration Systems using IoT*](https://prezi.com/view/4bmIZZe6mSGPyPI7kJwv/)** (Feb 21 - May 21)

- ESP-32 and Embedded C is used for implementing the Hardware-Software
Education.
- Design and Development of a real-time monitoring system based on the 4-layer architecture of IoT, which will help in condition monitoring of these refrigerators and support the facilitation of condition-based maintenance.

**[*Support systems for visually impaired*](https://github.com/vibsaa/vibsaa.github.io/blob/b99437c01090826877c5a50e624f96b329303d39/Images&Credentials/NCERT_Certi.jpeg)** (Jan 21- Mar 21)

- ESP-32 and Embedded C is used for implementing the Hardware-Software.
- Various systems are developed by a group of students to make it possible for visually impaired people to perform elementary science experiments like speed calculation, optics experiments, knowledge of flower parts, etc.
- All the projects are developed for & with NCERT under the title "Development of Tactile Kit manual in science at upper primary stage"

**[*Double Dice Game*](https://github.com/vibsaa/OpenSource_verilog)** (Jan 20- Jan 20)
- Spartan-6 FPGA and Verilog is used for implementing the Hardware-Software.
- The system is equipped with 7-segment displays and Buttons to provides an interactive interface for the user to roll the dice and see the outcome.
- Xilinx ISE & open-source tools like iVerilog and GTKwave are used for designing the system.

**_Two terminal device characterization system_** [v1](https://github.com/vibsaa/pearning) & [v2](https://github.com/vibsaa/CURVE_TRACER_V2) (Sep 19- Dec 19)
- AVR Atmega16 microcontroller & Embedded C (AVR Studio) for v1 and ESP-32 & Embedded C (Arduino IDE) for v2 are used for implementing the Hardware-Software.
- v1 is capable of providing the Input-Output characteristics for any two-terminal device under 5 seconds diode and resistance under 5 seconds whereas v2 comes with added functionality of providing the Input-Output characteristics for any two-terminal device (e.g. diode, resistance, capacitor, inductor, etc.) under 5 seconds. 
- The project comes with a GUI created using Python-Tkinter and the obtained characteristics are displayed on a computer screen. NumPy, Matplotlib, and File Handling is used for data manipulation and visualization.
- Eagle CAD is used for designing the schematic and PCB for the system.

Work Experience
---------------
[*Silicon Design Engineer-II, AMD (Feb'21- Present)*]

- Formal verification engineer in the core power management team (Bangalore)

[*Teaching Assistant, NPTEL-IITD*] ([Jul 20](https://github.com/vibsaa/vibsaa.github.io/blob/ff0b005349e6f41335d7c8cd20487f1c3887e541/Images&Credentials/NPTEL-July20.pdf)- [Jul21](https://github.com/vibsaa/vibsaa.github.io/blob/ff0b005349e6f41335d7c8cd20487f1c3887e541/Images&Credentials/NPTEL-Jan21.pdf))

- Created course material from PPT's to Final Question Papers, Managed Discussion Forum for the course which has 25k+ students Registered on each run.

Skills & Proficiency
---------------------
- *Low Power VLSI Design*- Low power design techniques, Multi Vth, DVFS, CMOS Power dissipation, Power, Area & Performance trade-offs.
- [*Digital System Design*](https://github.com/vibsaa/OpenSource_verilog)- Expertise in Digital Electronics, Datapath (FSM-D), Control Path Design (FSM), Static timing Analysis (Theoretical), Combinational and Sequential block design, Designing of Memory Blocks and writing testbenches using [Verilog](https://hdlbits.01xz.net/wiki/Special:VlgStats/1A32B85E42B70142).
- *Python*- Data structures (lists, dictionaries, array, linked lists, Trees), OOPS Concepts, NumPy-Curve fitting, UI design using Tkinter, Python scripting
Matplotlib, SciPy & Pandas- Data plotting using Matplotlib, SciPy- generating signals and obtaining transforms, Exploratory data analysis using Pandas.
- [*PCB design*](https://www.udemy.com/certificate/UC-20f2bbce-dd7b-40df-9eef-3ed496faa1e3/)- Single layer PCB design and Fabrication, Double-layer PCB design, ERC, DRC.
- [*Embedded Communication Protocols*](https://www.udemy.com/certificate/UC-d6baa40e-e3f3-4cd9-8c12-4a60e2205fba/)- Serial/Parallel communication, synchronous/asynchronous, UART, SPI, I2C & CAN.
- *Analog IC*- Design & Simulation of CMOS Op-Amp circuits, knowledge of MOS, FGMOS & QFGMOS Transistors.
- *Device Physics and Analog Electronics*- Semiconductor Physics, Fermi level, p-n Junction, various diodes, BJT, MOS Capacitor, Fabrication process, Small Signal Models- BJT, MOS.

Publication
------------
- [V. Sharma and D. V. Gadre, "Condition Monitoring of Industrial & Commercial Refrigeration Systems Using IoT," 2021 9th International Conference on Reliability, Infocom Technologies and Optimization (Trends and Future Directions) (ICRITO), 2021, pp. 1-6, doi: 10.1109/ICRITO51393.2021.9596504.](https://ieeexplore.ieee.org/document/9596504)
 
Education
----------
- **_Embedded Systems and VLSI, Master of Technology_**  
Netaji Subhas University of Technology, (2019-21)  
*CGPA-8.2*

- **_Electronics and Communication, Bachelor of Technology_**  
Maharaja Agrasen Institute of Technology, (2015-19)  
*CGPA-8.92* & *GATE’19 Rank- 6797* 

Engineering Technology
-----------------------
|S.No| *Languages & OS* | *Hardware* | *Dev tools* |
| --- |--- | --- | --- |
|1| Python & C++ | Spartan 6 FPGA | Xilinx Vivado, Questa Sim |  
|2| Verilog & System Verilog | AVR Controllers | Eagle CAD | 
|3| Embedded C | MSP430 | Proteus |
|4| Windows & Linux | ESP-32 | AVR & Arduino Studio |
|5| Perl, awk, grep & sed |  | LT-Spice|
|6| SVA & Coverage | | Synopsys Verdi |

Internships
-------------
- **_Telecom Engineering centre, DOT_**, Delhi (May 18- Jul 18)  
A Research to investigate the effect of electromagnetic (EM) radiation from Mobile Phones on Human health. Measured SAR values for a Mobile phone using state of an art measurement setup -SPEAG DASY-5 consisting of a Robotic probe and a human body and tissue simulating part.
- **_Solid State Physics Laboratory, DRDO_** Delhi (Jun 17- Jul 17)  
Characterization of high-frequency Power Amplifiers by obtaining their s-parameters and power output for different Frequency ranges. The characterization data is obtained using VNA and Load pull method.
