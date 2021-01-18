# FAIO Multiplexer Wireless

FAIO Multiplexer Wireless is an open-source Assistive technology wing for Adafruit Feather boards which enables those with limited or no hand movement to use Adaptive switches as input to operate in multiple input modes.

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Resources/Images/faio_multiplexer_1.png" width="50%" height="50%" alt="FAIO Multiplexer 1"/>
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Resources/Images/faio_multiplexer_2.png" width="50%" height="50%" alt="FAIO Multiplexer 2"/>
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Resources/Images/faio_multiplexer_3.png" width="50%" height="50%" alt="FAIO Multiplexer 3"/>
</p>

FAIO Multiplexer Wireless supports following switch modes:

* Switch Access Mode ( HID Keyboard ) : Teal Led
* Morse Keyboard Mode ( HID Keyboard ) : Purple Led
* Morse Mouse Mode ( HID Mouse ) : Pink Led
* Settings Mode : Orange Led

How to change the mode?

You can change the mode by holding switch number 4 or D for 2 seconds.

# Downloads 

These are all the files and documentation associated with the FAIO Multiplexer Wireless project.

 <table style="width:100%">
  <tr>
    <th>Resource</th>
    <th>Version</th>
    <th>Format</th>
    <th>Link</th>
  </tr>
    <tr>
    <td>FAIO Multiplexer Wireless All</td>
    <td>1.1</td>
    <td>ZIP</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/archive/master.zip">FAIO_Multiplexer_Wireless-master.zip</a></td>
  </tr>
  <tr>
    <td>FAIO Multiplexer Wireless Instructions Assembly Manual</td>
    <td>Version 1.1</td>
    <td>PDF</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Documentation/Build_Manuals/FAIO_Multiplexer_Wireless_Instructions_Manual.pdf">FAIO_Multiplexer_Wireless_Instructions_Manual.pdf</a></td>
  </tr>
   <tr>
    <td>FAIO Multiplexer Wireless User Manual</td>
    <td>Version 1.1</td>
    <td>PDF</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Documentation/User_Manuals/FAIO_Multiplexer_Wireless_User_Manual.pdf">FAIO_Multiplexer_Wireless_User_Manual.pdf</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer Switch BOM (csv)</td>
    <td>July 24, 2020</td>
    <td>CSV</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Components/FAIO_Multiplexer_Wireless_BOM.csv">FAIO_Multiplexer_Wireless_BOM.csv</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer_Wireless Switch Software</td>
    <td>1.0</td>
    <td>Ino</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/raw/master/Software/FAIO_Multiplexer_Wireless_Software/FAIO_Multiplexer_Wireless_Software.ino">FAIO_Multiplexer_Wireless_Software.ino</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer_Wireless Switch Board Layout</td>
    <td>1.0</td>
    <td>BRD</td>
    <td><a href="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Hardware/PCB_design/FAIO_Multiplexer.brd">FAIO_Multiplexer.brd</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer_Wireless Switch Board Schematic</td>
    <td>1.0</td>
    <td>SCH</td>
    <td><a href="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Hardware/PCB_design/FAIO_Multiplexer.sch">FAIO_Multiplexer.sch</a></td>
  </tr>
   <tr>
    <td>FAIO_Multiplexer_Wireless Battery Holder enclosure</td>
    <td>1.1</td>
    <td>STL</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Hardware/Housing_design/STL/FAIO_Multiplexer_Body_Battery_Holder.stl">FAIO_Multiplexer_Body_Battery_Holder.stl</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer_Wireless Bottom enclosure</td>
    <td>1.1</td>
    <td>STL</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Hardware/Housing_design/STL/FAIO_Multiplexer_Body_Bottom.stl">FAIO_Multiplexer_Body_Bottom.stl</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer_Wireless Bottom enclosure with camera mount threaded screw hole</td>
    <td>1.1</td>
    <td>STL</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Hardware/Housing_design/STL/FAIO_Multiplexer_Body_Bottom_With_Mount.stl">FAIO_Multiplexer_Body_Bottom_With_Mount.stl</a></td>
  </tr>
  <tr>
    <td>FAIO_Multiplexer_Wireless Top enclosure</td>
    <td>1.1</td>
    <td>STL</td>
    <td><a href="https://github.com/milador/FAIO_Multiplexer_Wireless/blob/master/Hardware/Housing_design/STL/FAIO_Multiplexer_Body_Top.stl">FAIO_Multiplexer_Body_Top.stl</a></td>
  </tr>
</table> 

# Usage

The FAIO Multiplexer Wireless switch interface can operate in 4 modes and switch D is used to switch between them.The RGB Led blinks 2 times to indicate the current mode.

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Resources/Images/faio_multiplexers.png" width="50%" height="50%" alt="FAIO Multiplexer boards"/>
</p>

## USB or Bluetooth Switch mode

 <table style="width:100%">
  <tr>
    <th>Mode Number</th>
    <th>Mode</th>
    <th>Color</th>
  </tr>
    <tr>
    <td>1</td>
    <td>Keyboard Switch</td>
    <td>Teal</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Morse Keyboard</td>
    <td>Purple</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Morse Mouse</td>
    <td>Pink</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Settings</td>
    <td>Orange</td>
  </tr>
</table> 

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO_Multiplexer_Wireless/master/Resources/Images/faio_multiplexer.png" width="50%" height="50%" alt="FAIO Multiplexer board"/>
</p>


## Software Setup Instructions

  1. Install the required libraries 
  
  1.1. Install Neo Pixels: https://github.com/adafruit/Adafruit_NeoPixel

  1.2. Install EasyMorseBlue: https://github.com/milador/EasyMorseBlue
  
  1.3. Install StopWatch: https://github.com/RobTillaart/Arduino/tree/master/libraries/StopWatch
  
  1.4. Install FlashStorage if using Feather M0 Board : https://github.com/cmaglie/FlashStorage

  1.5. Install Bluefruit library: https://learn.adafruit.com/adafruit-feather-32u4-bluefruit-le
  
  2. Download the firmware: https://github.com/milador/FAIO_Multiplexer_Wireless/raw/master/Software/FAIO_Multiplexer_Wireless_Software/FAIO_Multiplexer_Wireless_Software.ino
  
  3. Setup Arduino IDE for your feather board according to the instructions on Adafruit website
  
  4. Verify and upload firmware code to your Feather Board
