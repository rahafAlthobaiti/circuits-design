🔌 Arduino LED Control Project

Bodacious Snicket-Fulffy

🛠️ Components Used:
Arduino Uno R3
Breadboard
Red LED
220Ω Resistor
Jumper Wires
⚡ Circuit Description:
This project demonstrates how to control a red LED using an Arduino Uno. A digital pin on the Arduino sends HIGH or LOW signals to turn the LED on or off. A 220Ω resistor is connected in series with the LED to limit current and protect it from damage.

🔗 Wiring Instructions:
Connect the LED Anode (+) to Digital Pin 8 on the Arduino.
Connect the LED Cathode (−) to one side of the 220Ω resistor.
Connect the other side of the resistor to the GND (Ground) pin on the Arduino.
🧑‍💻 Arduino Code:
void setup() {
  pinMode(8, OUTPUT);  // Set digital pin 8 as an output
}

void loop() {
  digitalWrite(8, HIGH);  // Turn the LED on
  delay(1000);            // Wait for 1 second
  digitalWrite(8, LOW);   // Turn the LED off
  delay(1000);            // Wait for 1 second
}
🧪 How It Works:
The setup() function initializes digital pin 8 as an output.
The loop() function turns the LED on and off repeatedly with a 1-second delay, creating a blinking effect.
💡 Important Notes:
You can change the digital pin number or LED color as needed.
Always use a resistor with your LED to prevent it from burning out due to excessive current.
✅ Simulation:
Test your circuit virtually by clicking the Start Simulation button in Tinkercad and watch the LED blink.

🔗 Project Link on Tinkercad:
https://www.tinkercad.com/things/5m4a4eu9L0o/editel?returnTo=%2Fdashboard
