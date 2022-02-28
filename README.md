# Full-Adder-CMOS-design-Using-28nm-pdk

# Introduction
CMOS stand for Complementary Metal Oxide Semiconductor. CMOS is the semiconductor technology used to manufacture transistor. CMOS use two MOS which include PMOS and NMOS in which NMOS act as discharging Capacitor while PMOS act as charging Capacitor. This paper present basic design of Full adder using 28 transistor which include implementation of basic gate using transistor. 

# Circuit Details
Full adder is basic circuit which takes 3 input which include Input 1(A) and Input 2(B) a Carry (Cin). It performs addition and produce 2 output Sum and Carry. Since these are 2-bit digital Signal so can be 0 or 1.
The above Boolean expressions is: 
sum = A XOR B XOR Cin                                            (1)
carry = AB + BCin + ACin                                         (2)

# Tools Used:
• Synopsys Custom Compiler:
 The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

• Synopsys Primewave:
 PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

• Synopsys 28nm PDK:
 The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# Implentation of circuit Design
  ![image](https://user-images.githubusercontent.com/63257137/155872846-db274d6b-f825-4f64-9e70-121f68f3badf.png)
# Gate level implimentation
  ![image](https://user-images.githubusercontent.com/63257137/155872864-394458a2-8345-44e7-bf99-12d98ea13411.png)
# Testing Circuit
 ![image](https://user-images.githubusercontent.com/63257137/155872907-bc1fbc40-eaf1-4bb9-a696-3b82e7ea3bf0.png)

# FINAL WAVEFORM AND ESTIMATION
 ![image](https://user-images.githubusercontent.com/63257137/155872913-27e592a7-a415-4e14-9637-5077e16b51ae.png)
 
# Acknowledgements:
Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
Cloud Based Analog IC Design Hackathon
Synopsys India VLSI System Design (VSD) Corp. Pvt. Ltd India 
Chinmay panda, IIT Hyderabad
Sameer Durgoji, NIT Karnataka

# REFERENCES
[1]	K. D. Shinde and J. C. Nidagundi, "Design of fast and efficient 1-bit full adder and its performance analysis," 2014 International Conference on Control, Instrumentation, Communication and Computational Technologies (ICCICCT), 2014, pp. 1275-1279, doi: 10.1109/ICCICCT.2014.6993157.

[2]	Geeek for Geeks - Digital Full Adder logic

[3]	Design A 1Bit Low Power Full Adder Using Cadence Tool

[4]	Inderjit Singh Dhanjal – Youtube Channel


