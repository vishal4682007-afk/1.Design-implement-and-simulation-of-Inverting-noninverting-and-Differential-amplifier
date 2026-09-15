# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="899" height="1599" alt="WhatsApp Image 2026-09-15 at 6 55 49 PM" src="https://github.com/user-attachments/assets/11ea2211-61f9-4524-8d8a-3b674ac262b9" />


**INVERTING AMPLIFIER:**
<img width="899" height="1599" alt="WhatsApp Image 2026-09-15 at 6 56 22 PM" src="https://github.com/user-attachments/assets/1503b6d6-c287-4ecd-a6e6-62787409e8cd" />

  **CIRCUIT DIAGRAM**
  <img width="899" height="1599" alt="WhatsApp Image 2026-09-15 at 6 56 35 PM" src="https://github.com/user-attachments/assets/e2e0eeda-8bed-48c0-a027-4c589e06071c" />



  **MODEL GRAPH:**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/e18811de-a362-4a18-b1f4-0a1245fdac58" />



  **TABULATION:**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/a83d1345-081a-4d3a-a52c-5292abbac309" />

 

**MODEL CALCULATION:**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/4a9dc24a-d5ec-4673-a81b-f12a04c9b242" />


**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/1f7295d0-17b6-45de-af29-5b519f7cc69c" />



  **MODEL GRAPH:**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/fb2f2d6d-51a9-4580-b2a5-21e88a744dcf" />



  **TABULATION:**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/f93ba5a8-fbcd-457a-8b2a-db67c7abf26d" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/6103f2ae-195d-40a9-a43c-0ef5361097a5" />



  **MODEL GRAPH:**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/0e51ca5a-d904-435d-84f7-dd83765269c5" />



  **TABULATION:**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/c17070c6-fe87-4a10-af47-ce192edd2c08" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/36163114-25a6-44e1-b121-ab205e3cb96f" />

  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






