# Make XY Plotter Drawing Machine with mXY Board
In this project we gonna make XY Plotter Drawing machine with mXY Board. With Drawing Robot you can draw images on wall, panel or A4 paper. You can print pictures or print text. The machine is a simple device, that draws picture using a normal pen, some motors and some string. All required hardware for this project are listed below. We will learn how to install and use the Polargraph program for drawing control. </br>
![](mXY_img_02.png) </br>
# About mXY Board
My goal was to design the mXY board to make low budget the XY plotter drawing machine. So I designed a board that makes it easier for those who want to make this project. In the previous project, while using 2 pcs Nema17 stepper motors, this board uses 2 pcs 28YBJ-48 DC 5V 4 Phase 5 Wire Stepper Motors. Also in the previous project, Arduino Uno R3 was used as microcontroller and Adafruit Motor Shield as motor driver. This board uses Atmega328P and ULN2003 stepper driver. So you will be able to make this project with a single board. A 5V 1A adapter or powerbank is sufficient for this project to power consumption. The maximum current was observed as 0.4A when both motors were running.</br>

<b> Get the PCB - Schematic - Gerber files :</b> https://bit.ly/2ZWZJ7u </br>
<b> Get the mXY Assembled Board from PCBWayer Bazaar :</b> https://bit.ly/3dmsU89 </br>

The board shown in the video is the test version, the updated and upgraded version of the board is at the link below. Also, for those who do not want to solder, the mXY board will be sold at PCBWay Bazaar with all components assembled. Many thanks to PCBWay for this support.</br>
![](shared_updated_version.png) </br>
# Required Components for PCB: </br>
- **1x ATmega328P-PU with Bootloader:** https://bit.ly/2U9iwJw </br>
- **2x ULN2003 DIP16:** https://bit.ly/3dtexif
- **2x 28YBJ-48 5V 5 Wire Stepper Motor:** https://bit.ly/3gHHxVs
- **1x CH340G SOP16:** https://bit.ly/2TZXNaC
- **Type B USB Socket:** https://bit.ly/2WBSQqw </br>
- **DIP Socket 28/16 Pins:** https://bit.ly/2UahQDK </br>
- **12/16 MHz Crystal:** https://bit.ly/33FNTyL </br>
- **L7805 TO-220:** http://bit.ly/2N5WnYG </br>
- **10uF Capacitor:** https://bit.ly/2U98JTU </br>
- **22pF/0.1uF/10nF Ceramic:** https://bit.ly/2WCuQ6Y </br>
- **LED:** http://bit.ly/37OajhS </br>
- **Resistor 10K/ 1K:** https://bit.ly/2WFsNPl </br>
- **Power Jack Socket:** http://bit.ly/2QAzFdp </br>
- **2 Pin Terminal Block:** http://bit.ly/2lEgy58 </br>
- **Male Pin Header:** https://bit.ly/3ab5h0w </br>
- **2x JST B5B-XH Connector:** https://bit.ly/2yXfJeI </br>
- **1x MG90S Servo Motor:** https://bit.ly/2XWWytT </br>
- **GT2 Pulley 16 Teeth Set:** https://bit.ly/36Wfayk </br>
- **GT2 Rubber Belt (5M):** https://bit.ly/2XTgbTT </br>
- **3 in 1 Jumper Wire:** http://bit.ly/2J6de9E </br>
- **Soldering Tools:** http://bit.ly/2PEiyVx </br>
# Connections: </br>
![](mXY_connection.png) </br></br>
An extension wire will be required for stepper motors and servos. </br>
- **5M Extension Wire Cable:** https://bit.ly/3gMZMJa </br></br>
# Gondola & Bracket: </br>
![](mXY_img_03.png) </br></br>
You can find gondola and stepper motor mounting bracket 3D models in the ZIP file '**Gondola_Bracket_Models**'</br>
JGAURORA A5S 3D printer was used for 3D models. </br>
- **JGAURORA A5S 3D Printer:** https://bit.ly/2QH6GUP </br>
# polargraphcontroller: </br>

- It works fine in **Arduino IDE v1.8.5** https://www.arduino.cc/en/Main/OldSoftwareReleases#previous </br>
- Download and install the **Arduino IDE v.1.8.5**
