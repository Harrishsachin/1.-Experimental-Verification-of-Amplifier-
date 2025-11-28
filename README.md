#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-11-28 at 22 48 41_bc2d6fff](https://github.com/user-attachments/assets/7352aef1-2c3c-4697-8e89-cc77d7f11f6d)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-28 at 22 49 22_406d4ce9](https://github.com/user-attachments/assets/94adad4b-8d14-4fbe-bd30-040f405113a7)


MODEL GRAPH 

![WhatsApp Image 2025-11-28 at 22 49 59_02ac8138](https://github.com/user-attachments/assets/7b670a9b-4823-4e38-8b85-90733068e987)



DESIGN:

Inverting amplifier:

![WhatsApp Image 2025-11-28 at 22 51 13_3f4e6e08](https://github.com/user-attachments/assets/c67147a2-8786-481c-9f25-3f46781d319a)


PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![WhatsApp Image 2025-11-28 at 22 50 43_dcf8d595](https://github.com/user-attachments/assets/7e72d197-01a7-49c0-987b-2fe83aa44c9f)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 22 51 42_42e07117](https://github.com/user-attachments/assets/93a78998-0b42-4aba-9878-0b3664b65fd8)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 22 52 27_8ca34183](https://github.com/user-attachments/assets/81b31e40-30ce-454d-9acd-2af4f7b029a7)


---

## MODEL GRAPH

![WhatsApp Image 2025-11-28 at 22 53 00_50643f11](https://github.com/user-attachments/assets/8b61db67-913a-4011-b3ee-f76343612bf6)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![WhatsApp Image 2025-11-28 at 22 54 17_db470eb6](https://github.com/user-attachments/assets/b4f64c28-0d47-411f-9033-a9ed3bb001f3)
![WhatsApp Image 2025-11-28 at 22 53 32_aa17bf44](https://github.com/user-attachments/assets/f0054665-3e18-4ea3-bfd9-78088977b104)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 22 54 44_9214ac3f](https://github.com/user-attachments/assets/a3e4b0a2-ead3-47e3-b31b-02467c34f469)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 22 55 23_d678633b](https://github.com/user-attachments/assets/34abac6d-6935-4d95-b0e3-c5e20ea34de9)


## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 22 56 26_9ec9e380](https://github.com/user-attachments/assets/da2aa5e5-0843-4678-b8d5-e1af69788a18)


---

## DESIGN


### **Differential Amplifier**

![WhatsApp Image 2025-11-28 at 22 56 56_22fda3e8](https://github.com/user-attachments/assets/e72eb193-6ec8-48fc-938a-097bd66a25a0)




## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-28 at 22 57 13_cea374c1](https://github.com/user-attachments/assets/910267cf-946e-4f4a-a314-e8e3f8ffe040)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 22 57 32_0a285ae4](https://github.com/user-attachments/assets/49aa8484-fd51-43f0-ba74-3c4c1e833aed)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-11-28 at 23 00 06_6e2f6c78](https://github.com/user-attachments/assets/78254bd1-fbdd-419f-bd88-c46949b18cc2)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-11-28 at 23 00 39_f990d56b](https://github.com/user-attachments/assets/197ea6be-38bb-4549-bcf8-21f6c91c1ea5)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 23 00 59_ec3302ee](https://github.com/user-attachments/assets/b61734b1-cbd9-4a26-bd7f-ca336057b537)

---
## RESULT
![WhatsApp Image 2025-11-28 at 23 01 46_23f56fda](https://github.com/user-attachments/assets/6a0d93b4-329b-4c3c-9869-11a940887299)

