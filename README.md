# Experiment-6
## Current Mirror
Current mirroring in differential amplifiers is a technique used to accurately replicate a reference current in another transistor, ensuring stable and precise current control. This is crucial for maintaining the linearity, high gain, and low distortion of the amplifier. A current mirror typically involves two matched transistors: one acting as the reference and the other as the output, where the output transistor mirrors the current set by the reference. Current mirrors are used in differential amplifiers to provide a stable tail current and active load, ensuring high performance despite variations in temperature, supply voltage, or transistor mismatches. Various types, such as simple, Wilson, and cascode current mirrors, offer different levels of accuracy and output impedance, with the cascode mirror providing the highest precision. This technique improves common-mode rejection ratio (CMRR) and ensures the amplifier operates efficiently, reducing errors and distortion. However, it relies on transistor matching, voltage headroom, and can be affected by thermal variations.

### Given Parameters :-
power=1mw, Vdd=1.8v, Av>10v/v
### Aim :-
1. Design for current mirror ratio 1:1, 1:2 and do the DC analysis.
2. Vary the current mirror ratio in differnt cases and analyze DC, AC and Transient analysis.
3. Design the differential amplifier with current mirror circuit and perform DC, AC and Transient analysis.

### Calculation :-

Itotal=power/Vdd
Itotal=1mw/1.8=0.55mA
Itotal=Iref + Ix
Iref=0.55ma/2=0.277mA

## Circuit Diagram :-

![CM ckt](https://github.com/user-attachments/assets/88a34dcf-90f5-474a-a6de-2aa47ed16d45)

#### Case-1 1:1
| Parameters  |
------------------------------------
|             |
|             |
|
|
|
|







