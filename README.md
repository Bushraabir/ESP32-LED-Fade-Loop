# 🌈 PWM LED Fader – ESP32 Multi-Color Light Sequence

Smooth multi-color LED fading using PWM on an ESP32. This sketch drives 5 LEDs with a wave-like fading animation using high-frequency PWM for precise control.

## 📹 Demo Video

[🎬 Watch on YouTube]((https://youtu.be/lbiYOHHvpB0))

---

## 🔌 GPIO Pin Mapping

| LED Color | GPIO Pin | ESP32 Label | Resistor | Notes                          |
|-----------|----------|-------------|----------|--------------------------------|
| Red       | GPIO 2   | G2          | 220Ω     | Anode (+) to GPIO pin          |
| Yellow    | GPIO 4   | G4          | 220Ω     |                                |
| Green     | GPIO 5   | G5          | 220Ω     |                                |
| Blue      | GPIO 15  | G15         | 220Ω     |                                |
| White     | GPIO 18  | G18         | 220Ω     | Can be used for IR or blink    |

---

## 🛠️ Setup Instructions

1. Place 5 LEDs on your breadboard.
2. Connect a **220Ω resistor** between each GPIO pin and the **anode (+)** of each LED.
3. Connect all LED **cathodes (–)** to the **GND rail** on the breadboard.
4. Connect the **GND rail** to any **GND pin** on the ESP32.
5. Upload the `PWM_5LEDs.ino` sketch using Arduino IDE.
6. Enjoy the smooth fading color wave!

---
