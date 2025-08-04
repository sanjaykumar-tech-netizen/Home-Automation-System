Task 2: Home Automation System – Using Wokwi

COMPANY: CODTECH IT SOLUTION

NAME: SANJAY KUMAR M

INTERN ID: CT04DH1577

DOMAIN:Internet Of Things

DURATION:4 WEEKS

MENTOR:Neela Santhosh

DESCRIPTION:

🎯 Objective:

Create a system that can control multiple appliances like:

Light (using LED)

Fan (using another LED or DC motor)


We will simulate app control using the Serial Monitor, sending specific characters to turn ON/OFF devices.


---

🛠️ Step-by-Step Guide (Wokwi)


---

✅ Step 1: Open Wokwi Simulator

Go to https://wokwi.com

Click "New Project"

Select Arduino UNO



---

✅ Step 2: Add Components

Click on the pink “+” button to add:

Arduino UNO

2 x LEDs (representing Light and Fan)

2 x 220Ω Resistors

Breadboard (optional)

Jumper Wires



---

✅ Step 3: Circuit Wiring

Appliance	Arduino Pin	Resistor	Connect To

Light (LED1)	Pin 13	220Ω	GND
Fan (LED2)	Pin 12	220Ω	GND


Wiring Steps:

1. Connect LED1 anode (long leg) → Arduino Pin 13


2. Connect LED1 cathode (short leg) → 220Ω Resistor → GND


3. Connect LED2 anode → Pin 12


4. Connect LED2 cathode → 220Ω Resistor → GND# Home-Automation-System
