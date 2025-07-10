# 🔌 Arduino LED Control Project  
## Bodacious Snicket-Fulffy

---

### 🛠️ Components Used:
- Arduino Uno R3  
- Breadboard  
- Red LED  
- 220Ω Resistor  
- Jumper Wires  

---

### ⚡ Circuit Overview:
Here’s a simple and fun way to make a red LED blink using an Arduino Uno. The Arduino sends ON/OFF signals through a digital pin to light up the LED. A 220Ω resistor keeps the current safe so your LED won’t fry.

---

### 🔗 How to Wire It:
- Connect the **LED’s positive leg (Anode)** to **Digital Pin 8** on the Arduino.  
- Connect the **LED’s negative leg (Cathode)** to one side of the **220Ω resistor**.  
- Connect the other side of the resistor to **GND** on the Arduino.

---

### 🛠️ How to Build the Project Step-by-Step:
1. **Place the Arduino Uno** on your workspace or breadboard setup.  
2. **Insert the LED** on the breadboard. Make sure the longer leg (Anode) is connected towards the Arduino pin 8.  
3. **Attach one end of the 220Ω resistor** to the shorter leg (Cathode) of the LED.  
4. **Connect the other end of the resistor** to the GND rail on the breadboard.  
5. **Use jumper wires** to connect the Arduino Digital Pin 8 to the LED Anode row on the breadboard.  
6. **Connect the GND pin on Arduino** to the breadboard’s ground rail where the resistor connects.  
7. Double-check all connections for correctness and firmness.

---

### 💻 The Code:

```cpp
void setup() {
  pinMode(8, OUTPUT);  // Set pin 8 as output
}

void loop() {
  digitalWrite(8, HIGH);  // LED ON
  delay(1000);            // Wait 1 second
  digitalWrite(8, LOW);   // LED OFF
  delay(1000);            // Wait 1 second
}

