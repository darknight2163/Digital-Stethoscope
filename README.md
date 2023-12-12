# Digital-Stethoscope
Implementation of the digital stethoscope with PCB components

# Abstract
In most of the countries throughout the world, heart disease is the leading cause of mortality. Cardiovascular illnesses caused 17.5 million deaths in 2012, or three out of every ten fatalities. The noises that the heart makes are connected to and constitute the majority of heart diseases. Heart auscultation, often known as hearing the heartbeat, has been a crucial technique for the early detection of cardiac malfunction. Traditional auscultation calls for a strong clinical background and empathetic listening abilities. A new branch of computer-aided auscultation has emerged due to to the development of the electronic stethoscope.
# Problem Statement
Implementation of the digital stethoscope with  components.
# Objective 
A circuit picks up the sound vibrations from the diaphragm of the stethoscope (microphone) and convert it to electronic signals that are then amplified and can be heard through a speaker loud enough that connecting to ears is not required and no sound is missed (even by less experienced practitioners). 
Using the Bluetooth module and arduino, we will then transfer this data to a Bluetooth terminal window. We will build an app which can correctly receive and show audio data from the digital stethoscope.
# Schematic Diagram of Circuit 
![image](https://github.com/darknight2163/Digital-Stethoscope/assets/108399066/b681ae1e-6e8e-41bf-85cf-f3296eadb585)

# Work Plan
|Sl. No.|Task|Task Description|Duration|
|---|---|---|---|
|1|Problem statement analysis| 1. Research different microphone and amplifier designs 2. Research Bluetooth module specifications 3. Identify the components needed|1week|
|2|Microphone and amplifier circuit|1. Create a schematic of the stethoscope's circuit using a computer-aided design (CAD) program 2. Assemble the circuit on breadboard and test it|1week|
|3|Filter and driver circuit|1. Prepare BOM and purchase the necessary components for the circuit 2. Assemble the circuit on breadboard and test it|1week|
|4|PCB Soldering|1. Assemble the PCB board, placing all the components and soldering them in place|2week|
|5|Adding LED to the PCB board circuit|1. Adding LED to the PCB board which will glow in sync with the heartbeat signal|1week|
|6|Final inspection of PCB board|1. Perform a final inspection and test to ensure that the board is functioning properly|1week|
|7|Implementing the wireless (Bluetooth) module to the stethoscope's circuit|1. Connect the Bluetooth module to the stethoscope's circuit 2. Test the stethoscope's Bluetooth functionality|1week|
|8|Develop the mobile app to interface the stethoscope|1. Identify the necessary features of the app 2. Choose a development platform and programming language 3. Design and code the app 4. Testing the app|3week|
|9|Integrate the hardware and software|1. Connect the Bluetooth module to the stethoscope's circuit 2. Test the stethoscope's Bluetooth functionality 3. Ensure that the app can properly receive and display audio data from the stethoscope|1week|
|10|Final testing and quality control|1. Test the stethoscope under various conditions 2. Make any necessary adjustments or repairs|1week|
|11|Final project documentation|1. Prepare final report|1week|

# PCB designed using KiCAD
![image](https://github.com/darknight2163/Digital-Stethoscope/assets/108399066/85acb58c-dce0-4873-b308-a9912765791a)
# PCB routing
![image](https://github.com/darknight2163/Digital-Stethoscope/assets/108399066/8a4de0ad-5c21-4d3e-9d3f-fb86d920c5c9)

# References
Electronic Stethoscope (Circuit Diagram): [circuit](http://www.diy-electronic-projects.com/p236-Electronic-Stethoscope) 
Electronic Stethoscope Article: [diy](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/s2012/myw9_gdd9/myw9_gdd9/)

