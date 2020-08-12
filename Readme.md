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

## 6T Memory cell

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/wl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/bl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/blbar.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/oq.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/oqbar.png)

**Note**-The Noise in above output waveforms will be reduced by parasitic capacitance. 

**Butterfly Curve**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/6TMemCell/Screenshot%20from%202020-08-02%2018-01-50.png)

The **Signal to Noise Margin(SNM)** for SRAM Cell = **0.63** 

## Sense Amplifier

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/bl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/blbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/se.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/od.png)

## Write Driver

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/en.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/enbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/data.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/databar.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/obl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/oblbar.png)


## Tri-State Buffer

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/en.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/enbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/in.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/oout.png)

## Pre-Charge Circuit

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/PreChargeCell/pclk.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/PreChargeCell/obl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/PreChargeCell/oblbar.png)

## Circuit Diagram Of Integrated Circuit

## Pre Layout Input/Output Waveforms Of Integrated Circuit

## Author

## Acknowlegedgements

## Contact Information
