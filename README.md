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
<img width="1599" height="641" alt="image" src="https://github.com/user-attachments/assets/9084af13-ce3c-4358-ac0c-02765a1c362d" />


**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1379" height="826" alt="image" src="https://github.com/user-attachments/assets/10d46db4-385b-48e4-9a5c-109e235d9da0" />


  **MODEL GRAPH:**
<img width="1600" height="1459" alt="image" src="https://github.com/user-attachments/assets/0f994050-c423-44f1-ad56-a424d6f5c839" />


  **TABULATION:**
 <img width="1600" height="886" alt="image" src="https://github.com/user-attachments/assets/f0fec1ec-0c81-4c1f-87ce-71ce19a2f6bd" />


**MODEL CALCULATION:**
<img width="1562" height="662" alt="image" src="https://github.com/user-attachments/assets/45d83fc0-caf9-40e9-8cd3-9494a5b809a1" />


**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="788" height="1308" alt="image" src="https://github.com/user-attachments/assets/db8572ba-683d-449b-b723-e02fc1637ff6" />

  **MODEL GRAPH:**
<img width="1550" height="1038" alt="image" src="https://github.com/user-attachments/assets/95eab4a4-f7ad-47c7-96b8-f5d68bb8ff15" />


  **TABULATION:**
<img width="1600" height="1002" alt="image" src="https://github.com/user-attachments/assets/468d23b0-5ba2-427e-b880-2b8cf91d10e0" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1347" height="988" alt="image" src="https://github.com/user-attachments/assets/3f489598-b669-4a5d-9026-09c045cf58cd" />


  **MODEL GRAPH:**
<img width="1600" height="842" alt="image" src="https://github.com/user-attachments/assets/9a98a91e-552c-4b2a-a62f-4bd8a6058528" />


  **TABULATION:**
  <img width="1454" height="978" alt="image" src="https://github.com/user-attachments/assets/74497a6f-5a7e-49c1-855c-8f9c74e47593" />


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
  <img width="1005" height="1600" alt="image" src="https://github.com/user-attachments/assets/43370743-0266-44c9-829b-5e5f6c1e3bf7" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






