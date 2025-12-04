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
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

![WhatsApp Image 2025-12-04 at 19 39 04_a16e32a5](https://github.com/user-attachments/assets/ede6a7db-1a89-458e-93bb-14b595960f6d)


MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



DESIGN:
![WhatsApp Image 2025-12-04 at 19 39 08_6f054906](https://github.com/user-attachments/assets/10c7170c-b7e9-4cc6-9446-0b1dcb7526a7)


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

![WhatsApp Image 2025-12-04 at 19 39 05_e8ef1ec8](https://github.com/user-attachments/assets/a8f13773-db96-4854-8bbf-7da4e1f5e8d1)
			
 ## CALCULATION

 ![WhatsApp Image 2025-12-04 at 19 39 06_e689fc9e](https://github.com/user-attachments/assets/7f94a02e-e186-4e3b-a3dd-91f5179e1e8f)



---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-04 at 19 39 07_f1df902e](https://github.com/user-attachments/assets/26b84fe8-cc51-47e5-a063-cf6fecc16c80)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-12-04 at 19 47 18_0cc81e5c](https://github.com/user-attachments/assets/00f3176b-17ed-48ac-a4fb-c703355f87ee)


---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

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

![WhatsApp Image 2025-12-04 at 19 47 44_2bdb385d](https://github.com/user-attachments/assets/d00a2f1f-c648-4f17-85c5-deb4ee7077d3)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-04 at 19 47 58_2fa9b226](https://github.com/user-attachments/assets/3f1991bb-0ccb-423d-ad3f-5a7c85a683a7)



---
## DESIGN 

![WhatsApp Image 2025-12-04 at 19 48 08_2d6df4d8](https://github.com/user-attachments/assets/4f871f58-065f-4ab4-9511-50a2975b44e9)

## CALCULATION

![WhatsApp Image 2025-12-04 at 19 47 32_8dfc4564](https://github.com/user-attachments/assets/da79388f-d1a2-40ee-bdd1-9e4afde6f8a7)


## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="706" height="522" alt="image" src="https://github.com/user-attachments/assets/917f2544-3735-4a23-a9b7-1264966d0d20" />

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



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

| S.No | V1 (V) | V2 (V) | Vo = (-Rf/R1)(V1 - V2) (V) | Theoretical | Practical |
|------|---------|---------|-----------------------------|--------------|------------|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |

---
## OUT PUT WAVEFORM AND DISCUSSION 


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1006" height="1087" alt="image" src="https://github.com/user-attachments/assets/636c08f9-7940-470e-a89e-4891d57a9ac7" />

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

| S.No | V1 (V) | V2 (V) | Vo = (Rf / R1) [1 + (2R’ / R)] (V2 – V1) (V) | Theoretical | Practical |
|------|---------|---------|----------------------------------------------|--------------|------------|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |

---
## OUT PUT WAVEFORM AND DISCUSSION 


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
