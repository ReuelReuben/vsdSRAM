# SRAM

## SRAM Design
This Project mainly focuses on the design of 4kB SRAM memory using opensource memory compiler **OpenRAM**. For the design of custom memory array, memory compiler takes in SPICE netlists, Layout files of the custom cells designed and few other parameters and generates a SRAM memory array.

SRAM Specs - Memory Size of **4kBytes** with operating voltage of **1.8V** and access time of less than **2.5ns**. 
 
- For a better understanding of working, implementation and applications of SRAM please [click here]()

- For more information on OpenRAM please [click here](https://github.com/VLSIDA/OpenRAM.git)

# Basic Architectural Block Diagram
![](Documentation/BlockDiagram.png)

# Circuit Diagram Of Indivdual Custom Cells

**Note** -Below circuit diagrams have the test input's connected for reference with pre layout input/output waveforms. 

## 6T Memory cell

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/6TMemCell.png)

## Sense Amplifier

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/SenseAmplifier.png)

## Write Driver

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/WriteDriver.png)

## Tri-State Buffer

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/Trigate.png)

## Pre-Charge Circuit

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/PreCharge.png)


## Pre Layout Input/Output Waveforms Of Indivdual Custom Cells

## 6T Memory cell

For Reference Circuit Diagram please [click here](https://github.com/ReuelReuben/SRAM#6t-memory-cell)

For Pre Layout Simulation please [click here]()

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

For Reference Circuit Diagram please [click here]()

For Pre Layout Simulation please [click here]()

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/bl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/blbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/se.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/SenseAmpCell/od.png)

## Write Driver

For Reference Circuit Diagram please [click here]()

For Pre Layout Simulation please [click here]()

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/en.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/enbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/data.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/databar.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/obl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/WriteDriverCell/oblbar.png)


## Tri-State Buffer

For Reference Circuit Diagram please [click here]()

For Pre Layout Simulation please [click here]()

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/en.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/enbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/in.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/TrigateCell/oout.png)

## Pre-Charge Circuit

For Reference Circuit Diagram please [click here]()

For Pre Layout Simulation please [click here]()

**Input Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/PreChargeCell/pclk.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/PreChargeCell/obl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/PreChargeCell/oblbar.png)

# Circuit Diagram Of Integrated Circuit

![](https://github.com/ReuelReuben/SRAM/blob/master/CircuitDiagram/IntegratedCircuit.png)

# Pre Layout Input/Output Waveforms Of Integrated Circuit

For Reference Circuit Diagram please [click here]()

For Pre Layout Simulation please [click here]()

**Input Waveforms**

Wordline in 6T Memory Cell

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/wl.png)

Pre-Charge Enable

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/pclk.png)

Write Driver Data In

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/data.png)

Write Driver Enable

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/en.png)

Sense Amplifier Enable

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/se.png)

**Output Waveforms**

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/obl.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/oblbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/oq.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/oqbar.png)

![](https://github.com/ReuelReuben/SRAM/blob/master/Waveforms/IntegratedCircuit/od.png)

## Contributors

- Reuel Reuben
- Kunal Ghosh
- Philipp Gühring

## Acknowlegedgements

- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd.
- Philipp Gühring, Software Architect, LibreSilicon Assocation

## Contact Information

- Reuel Reuben, Undergraduate Student, BVPCOE reuel992000@gmail.com
- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd. kunalghosh@gmail.com
- Philipp Gühring, Software Architect, LibreSilicon Assocation pg@futureware.at
