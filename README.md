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
### For 1:1

#### DC Analysis

![CM 11 DC](https://github.com/user-attachments/assets/c8d182d2-2a26-4010-ad27-3d6aa4f5dcfa)

### For 1:2

#### DC Analysis

![CM 12](https://github.com/user-attachments/assets/db7bcc1f-1fc4-4aba-befb-c3891f853488)

### Case-1
| Parameters | M1 | M2| M3 |
|------------|----|---|----|
| Model      |PMOS | PMOS | NMOS |
| Length      | 180nm | 180nm |180nm |
| Width      | 20um | 20um |20um |
| Expected Current | 0.277mA |0.277mA | 0.277mA |

#### DC Analysis

![CM 11 DC](https://github.com/user-attachments/assets/c8d182d2-2a26-4010-ad27-3d6aa4f5dcfa)

#### AC Analysis

![CM 180nm ac](https://github.com/user-attachments/assets/2516a570-a30c-4801-be40-92edf9860c3c)

#### Transient Analysis

![CM 180nm T](https://github.com/user-attachments/assets/192de565-27a8-45d3-b096-faf7ca446847)

### Case-2
| Parameters | M1 | M2| M3 |
|------------|----|---|----|
| Model      |PMOS | PMOS | NMOS |
| Length      | 500nm | 500nm |500nm |
| Width      | 33um | 33um |33um |
| Expected Current | 0.277mA |0.277mA | 0.277mA |

#### DC Analysis

![CM 500nm dc](https://github.com/user-attachments/assets/8de236d7-c3d2-423e-86f1-5b561723c0b1)

#### AC Analysis

![CM 500nm Ac](https://github.com/user-attachments/assets/d582df43-b81f-4852-a3a6-de325535f502)

#### Transient Analysis

![CM 500nm T](https://github.com/user-attachments/assets/d1e1df72-8fbd-4b20-b4a3-8dff4621f8c6)

### Case-3
| Parameters | M1 | M2| M3 |
|------------|----|---|----|
| Model      |PMOS | PMOS | NMOS |
| Length      | 1um | 1um |1um |
| Width      | 33um | 33um |33um |
| Expected Current | 0.277mA |0.277mA | 0.277mA |

#### DC Analysis 

![CM 1um dc](https://github.com/user-attachments/assets/76f8707a-34c9-45be-9501-f19da85736b4)

#### AC Analysis

![CM 1um Ac](https://github.com/user-attachments/assets/8dbbc00d-9760-4933-9fb7-5debd5a5ade2)

#### Transient Analysis

![CM 1um T](https://github.com/user-attachments/assets/af887d94-5b69-4d46-b349-1d2eb97e4c05)

## Differential amplifier with current mirror

### Circuit Diagram :-

![Differential CM](https://github.com/user-attachments/assets/abc141c4-3f68-4b94-a212-9812b3e4ba20)

#### DC Analysis 

![differential CM DC](https://github.com/user-attachments/assets/f0ac6504-0c61-4177-96a8-b4f47a9d0dc2)

#### AC Analysis 

![Screenshot_24-3-2025_103043_private-user-images githubusercontent com](https://github.com/user-attachments/assets/b0668371-3352-468b-a624-4c57070c78ec)

#### Transient Analysis 

![Screenshot_24-3-2025_104328_web whatsapp com](https://github.com/user-attachments/assets/139039c7-708e-451f-a906-95745a59f8ef)

### Inference 

The Differential Amplifier with Current Mirror experiment demonstrates how a current mirror improves the performance of a differential amplifier. By using a current mirror as an active load, the circuit achieves higher gain, better stability, and improved common-mode rejection. The current mirror ensures that both transistors in the differential pair receive a stable and equal current, reducing mismatches and enhancing signal amplification. This setup also increases the output resistance, leading to better voltage gain. Overall, the experiment highlights the advantages of using a current mirror to improve the efficiency and accuracy of differential amplifiers.
