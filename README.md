# mobile-detector
MOBILE DETECTOR USING IC LM358

Scope of the project:A mobile detector can detect the activation of a mobile such as, incoming and outgoing Phone calls, messages and things in that nature. Whenever the phone is on silent mode, the detector detects various things from a mobile device. And it can be used as prevention of use of mobile phones in prisons, classrooms, etc.

Objectives:  
1	Mobile detector can be used for spying on someone and for unauthorized video transmission. 
2	It is useful where use of mobiles are prohibited, 
•	Hospitals  
•	Gas station  
•	Examination hall 
•	Military bases 
•	Religious places 
•	Historical places 
•	Spying and unauthorized video transmission 
•	Conferences 
Mobile detector is widely used in the above mentioned areas. Specially in hospitals, military areas and examination hall the use of mobile is prohibited. Because it is not always possible to check every person entering sensitive places, the use of a mobile detector is important. 

Working Principle:   The basic principle behind the mobile detector circuit is to detect the RF (Radio Frequency) signals. When a mobile phone is active, it radiates RF signal that passes through nearby space. The signal contains electromagnetic RF radiations from the mobile phone. Capacitor C1 is used in the circuit to detect the RF signal from the mobile phone. When the mobile phone radiates energy in the form of RF signal, C1 absorbs it and passes on to the inputs of IC. This is indicated by the flashing of LED. Preset Trimmer (50K) is used to vary the range of the circuit. Transistor T1 is used to amplify the signal obtained at PIN1 of IC. The circuit is applicable for 2G networks and GPRS. 

1. Connect the components on the bread board according to the circuit diagram. 4.5V 
power source is used in this circuit (5V mobile charger can also be used).
2. Transistor connections:
 Place the transistor (BC547/548) on the bread board.
 Connect one of 1K resistor to positive 4.5V and another to transistor.
Connect positive end of LED to emitter (BC547/548) and negative end to GND.
Connect resistors and capacitors according to the circuit diagram.

3. LM358 IC Connections:
 Place a LM358 IC on the bread board.
 Connect the PIN-8 of the IC to positive 4.5V.
 Connect PIN-4 of IC to ground (GND).
 Connect PIN-1 of IC with base of transistor.
 Connect 50K trimmer to PIN-1 and PIN-2 of IC.
 Connect Antenna to PIN-2 of LM358.
4. After connections bring the active mobile near the device, the LED will flash till the 
mobile is ringing.

Parts and its purpose:
1. LM358 IC (1 unit): It is used as an amplifier in the circuit. It eliminates the need for 
a dual power supply and simplifies the design.
Department of Electronics and Communication Engineering –AITM-Belagavi-09 4
2. BC547/BC548 NPN Transistor (1 unit): These are used to switch electronic signals 
and electrical power.
3. Resistors - 1K, 100K, 220K (1 each): Each resistor is used to control the current 
throughout the circuit.
4. Capacitors – 1uF (2 units), 100uF(1 unit): Each capacitor is used to store energy 
and provide the circuit with energy when it is necessary.
5. LED (Light Emitting Diode) (1 unit): It is used to provide light for the signal 
output.
6. Antenna (1 unit): It is used to capture the RF signal when a mobile receives call.
7. 50 K Trimmer: It is a variable resistor used to tweak settings on the circuit that will 
not needed to be changed of trimmer.
8. Breadboard: It is used to construct the circuit.
9. 4.5 DC Source: It is used to provide proper amount of voltage to the circuit.
10. Connecting Wires: Wires are used to the components.

12. Expected Outcome of the project: The expectation of this project is to detect the presence of an activated mobile from the 
distance of one and half meters. A circuit should detect and give the indication of an active 
mobile by glowing LED, according to the receiving frequency. The LED should be glowing 
until the signal ceases.

Application of the project:
1. Industry.
2. Health.
3. Societal.
4. Education.
 
