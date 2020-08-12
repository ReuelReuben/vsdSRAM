# SRAM

## SRAM Design
This Project mainly focuses on the design of 4kB SRAM memory using opensource memory compiler **OpenRAM**. For the design of custom memory array, memory compiler takes in SPICE netlists, Layout files of the custom cells designed and few other parameters and generates a SRAM memory array.

SRAM Specs - Memory Size of **4kBytes** with operating voltage of **1.8V** and access time of less than **2.5ns**. 
 
- For a better understanding of working, implementation and applications of SRAM please [click here]()

- For more information on OpenRAM please [click here](https://github.com/VLSIDA/OpenRAM.git)

## Basic Architectural Block Diagram
![](Documentation/BlockDiagram.png)

## Circuit Diagram Of Indivdual Custom Cells

**Note** -Below circuit diagrams have the test input's connected for reference with pre layout input/output waveforms. 

**6T Memory cell**

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/6TMemCell.png)

**Sense Amplifier**

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/SenseAmplifier.png)

**Write Driver**

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/WriteDriver.png)

**Tri-State Buffer**

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/Trigate.png)

**Pre-Charge Circuit**

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/PreCharge.png)


## Pre Layout Input/Output Waveforms Of Indivdual Custom Cells

**6T Memory cell**

**Input Waveform**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/wl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/bl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/blbar.png)

**Output Waveform**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/oq.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/oqbar.png)

Butterfly Curve


Sense Amplifier


Write Driver


Tri-State Buffer


Pre-Charge Circuit


Circuit Diagram Of Integrated Circuit

Pre Layout Input/Output Waveforms Of Integrated Circuit

Author

Acknowlegedgements

Contact Information
