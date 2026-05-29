# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**

<img width="802" height="698" alt="image" src="https://github.com/user-attachments/assets/63baf6e7-4942-4524-8bff-f207edbeacf9" />

**To measure RTh or RN**

<img width="807" height="494" alt="image" src="https://github.com/user-attachments/assets/23473f2f-a821-4037-9877-b75130b7f39e" />


**To measure IN or Isc**

 <img width="790" height="431" alt="image" src="https://github.com/user-attachments/assets/6c27ab27-ed5e-4c8e-a7f6-799492388148" />

**Thevenin’s equivalent circuit**

<img width="798" height="396" alt="image" src="https://github.com/user-attachments/assets/7ba9647f-765a-4a27-ae92-da6240808f0f" />

**Norton’s equivalent circuit**
<img width="671" height="517" alt="image" src="https://github.com/user-attachments/assets/7b3ac2c7-6fe3-42c5-a20e-39ad0eac314d" />


**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure I L
<img width="617" height="190" alt="image" src="https://github.com/user-attachments/assets/d0c8d32c-ea06-42d5-944b-807fca3115cc" />


**TABULAR COLUMN:2**

To measure RTh or RN

<img width="551" height="222" alt="image" src="https://github.com/user-attachments/assets/72ae2c7b-bcf9-462b-9794-87c435da7421" />


**TABULAR COLUMN:3**

To measure IN or Isc

<img width="578" height="209" alt="image" src="https://github.com/user-attachments/assets/7e2c4c42-2a34-4aa5-9a24-e8f2101e78e4" />

	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 <img width="678" height="803" alt="image" src="https://github.com/user-attachments/assets/b87728bf-13eb-4251-8a6b-647dbca5d202" />

<img width="712" height="607" alt="image" src="https://github.com/user-attachments/assets/7ed6c33b-16cc-4fe6-9235-5c3652b4f5da" />

<img width="475" height="581" alt="image" src="https://github.com/user-attachments/assets/877540cc-3634-4240-a4cb-e49482d04eb2" />

**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
