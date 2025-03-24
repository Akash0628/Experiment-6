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
#### For 1:1

##### DC Analysis



#### For 1:2

##### DC Analysis



#### Case-1
| Parameters | M1 | M2| M3 |
|------------|----|---|----|
| Model      |PMOS | PMOS | NMOS |
| Length      | 180nm | 180nm |180nm |
| Width      | 20um | 20um |20um |
| Expected Current | 0.277mA |0.277mA | 0.277mA |

##### DC Analysis

![CM 11 DC](https://github.com/user-attachments/assets/c8d182d2-2a26-4010-ad27-3d6aa4f5dcfa)

#### Case-3
| Parameters | M1 | M2| M3 |
|------------|----|---|----|
| Model      |PMOS | PMOS | NMOS |
| Length      | 500nm | 500nm |500nm |
| Width      | 33um | 33um |33um |
| Expected Current | 0.277mA |0.277mA | 0.277mA |

##### DC Analysis

![CM 500nm dc](https://github.com/user-attachments/assets/8de236d7-c3d2-423e-86f1-5b561723c0b1)

#### Case-2 
| Parameters | M1 | M2| M3 |
|------------|----|---|----|
| Model      |PMOS | PMOS | NMOS |
| Length      | 1um | 1um |1um |
| Width      | 33um | 33um |33um |
| Expected Current | 0.277mA |0.277mA | 0.277mA |

##### DC Analysis 

### Differential amplifier with current mirror

##### DC Analysis 

##### AC Analysis 

##### Transient Analysis 

### Inference 

