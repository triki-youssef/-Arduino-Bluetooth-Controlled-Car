
 
<h1> 🚗 Arduino-Bluetooth-Controlled-Car</h1>

<h2> ✅ Description</h2>
This project demonstrates how to build an Arduino-based RC car that can be controlled using any generic Bluetooth controller app such as “Bluetooth RC Controller” (by “Next Prototypes”, available on the Google Play Store). The app connects to the car via the HC-05 Bluetooth module and sends simple single-character commands.

The Arduino interprets these characters and controls the movement of the car via the L298N motor driver.

<h2> 🧠 Key Features:</h2>

📱 Wireless Control via Bluetooth and mobile app

🔁 Commands: Forward, Backward, Left, Right, Stop

🔋 Battery-powered and mobile

🔧 Easy to build, fully open-source
<br />


<h2> ⚙️ Components and Tools Used</h2>


<h3>Hardware Components:</h3>

<h4> - Microcontroller:</h4> Arduino Uno



<h4> - Motors:</h4> DC motors with motor driver module , L298N for robot movement







<h4> - Wireless Module:</h4> HC-05 ( Bluetooth Module)

<h4> - Power Supply:</h4> 11.1V, 3000mAh 

<h4> - Chassis:</h4> Robot base frame with wheels





<h4> - Software and Utilities:</h4>

<h5> - Arduino IDE:</h5> For programming the microcontroller firmware

<h2>📲 App Used : </h2>
<h2>App Name: Bluetooth RC Controller</h2>

<h4>Developer: Next Prototypes</h4>
</h3>Default Commands from App Buttons:</h3>
App Button	Sent Character
Forward  	F
Backward	B
Left    	L
Right   	R
Stop	    S



<h2>Robot-Program walk-through:</h2>

<p align="center">
🔧  Pins & Variable Declarations  <br/>
<img src="https://i.imgur.com/1mJOuJw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Start serial communication with HC-05 & Set motor pins as outputs <br/>
<img src="https://i.imgur.com/OsZ4gyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check if Bluetooth has sent a command & Choose action based on received command <br/>
<img src="https://i.imgur.com/3BedpY8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
🚗  Movement Functions <br/>
<img src="https://i.imgur.com/mXos71n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Wiring Diagram </h2>
<p align="center">
<img src="https://i.imgur.com/LcY5gBo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


