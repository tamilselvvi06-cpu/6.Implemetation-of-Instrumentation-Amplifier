# 6.Implemetation-of-Instrumentation-Amplifier
**Aim:**
To implement Instrumentation-Amplifier-using-Op-amp

**APPARATUS REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	2
4.	Op-Amp	µA741	3
5.	Bread Board		1
6.	Resistors	1K,10K,2.2K	1,4,2
7.	Connecting wires and probes	As required	

**THEORY:**

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
            Vo = RF/R1[1+ 2R’/R][V2-V1]
 

  
**PROCEDURE:**

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet.


  **CIRCUIT DIAGRAM**

<img width="1600" height="1426" alt="image" src="https://github.com/user-attachments/assets/13837f4c-04ef-4c0e-85f1-0bf031570eea" />

  **MODEL GRAPH:**

<img width="1600" height="1295" alt="image" src="https://github.com/user-attachments/assets/4b87bd36-7225-4aa7-b791-c17561700d7a" />


  **TABULATION:**
 
<img width="1400" height="623" alt="image" src="https://github.com/user-attachments/assets/5c9ba084-1762-441c-afcd-b05b0d7d216a" />

**MODEL CALCULATION:**

<img width="1600" height="615" alt="image" src="https://github.com/user-attachments/assets/759a0274-e102-4b68-8b07-6479878813cb" />


**RESULT:**
Thus a Instrumentation Amplifier was implemented using op-amp IC 741.
 

