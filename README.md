# PCB-Design-Application
# Aim
To prepare the pcb-design application for the given circuit.

# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory
The circuit you sent me is a simple sound reactive LED circuit. It uses the speaker to pick up ambient sounds and convert them into electrical signals which are then amplified by the transistors, which in turn light up the LEDs. 1.The speaker works as a microphone in this circuit. Sound waves cause the speaker cone to vibrate. This vibration induces a small voltage across the speaker terminals. 2.The capacitors (C1 and C2) block the DC voltage from the power supply from entering the circuit, but allows the AC signals from the speaker to pass through. 3.The 1N4148 diodes act as clippers or voltage limiters. They clip off the negative voltage halves of the AC waveform from the speaker, leaving only the positive voltage portions. This process is called half-wave rectification. 4.The resistors (1kΩ) limit the current from the speaker to the transistors (Q1-Q5). 5.The transistors (Q1-Q5) amplify the rectified signal from the speaker. When sound is picked up by the speaker, the transistors are turned on, which allows current to flow through the LEDs, lighting them up. The louder the sound, the brighter the LEDs will glow.

This is a basic circuit, and there are many variations of it online. You can experiment with different values of resistors and capacitors to change the sensitivity of the circuit and the way the LEDs respond to sound.


## Working 

The circuit you sent me is a simple sound reactive LED circuit. Here are the steps on how to build it:

Collect your parts. You will need:

LEDs (any color) 1N4148 diodes (4) 1k resistors (6) 470uF capacitors (2) Speaker 9V battery Breadboard Jumper wires Connect the positive lead of the battery to the positive rail of the breadboard. Connect the negative lead of the battery to the negative rail of the breadboard.

Connect one of the 470uF capacitors to the positive rail and the other to the negative rail.

Connect the positive leg of the speaker to the positive rail of the breadboard. Connect the negative leg of the speaker to one of the 1k resistors.

Connect the other leg of the 1k resistor to the negative leg of one of the 1N4148 diodes.

Connect the positive leg of the same 1N4148 diode to an LED. Connect the negative leg of the LED to the negative rail of the breadboard.

Repeat steps 4-6 four more times so that you have a total of four LEDs and four 1N4148 diodes connected in the same way.

Now you can adjust the sensitivity of the circuit by changing the value of the resistor connected between the speaker and the positive rail. A lower value resistor will make the circuit more sensitive.




# Circuit Diagram
![image](https://github.com/Beatricethomas/PCB-Design-Application/assets/140035214/e735f9da-345b-44ab-9a9c-40b45563af9d)



# Output

## Schematic diagram

![image](https://github.com/Beatricethomas/PCB-Design-Application/assets/140035214/e02a2452-d816-4a74-8401-a8a74059db3a)



## Layout diagram

![image](https://github.com/Beatricethomas/PCB-Design-Application/assets/140035214/5f744f9f-6365-46f0-ae9a-21a735429795)


# Result

Therefore PCB Design was successfully completed.
