# Hi, I'm Anastasia Erla 👋

**Industrial & Management Engineering student at the International Hellenic University (IHU)**, Thessaloniki, Greece.
I build low-cost health-monitoring devices that combine embedded hardware, signal processing and on-device AI.

- 🩺 **Health tech & IoT:** wearable-style vital-sign monitoring (heart rate, SpO₂, heart-rate variability)
- 🔌 **Embedded systems:** ESP32, Arduino, optical PPG sensors, I2C and serial communication
- 🤖 **TinyML:** neural networks that run *on* a microcontroller with Edge Impulse, no internet needed
- ☁️ **IoT cloud:** remote monitoring and alerts with Blynk

---

### 🚀 Featured projects

#### [Smart Health Guardian](https://github.com/anastasiagkl18/smart-health-guardian) · *diploma thesis*

A low-cost device (ESP32 + MAX30102) that measures heart rate, blood oxygen and heart-rate variability and runs a small
neural network **on the device itself** to estimate the user's state (relaxed, stressed, active…). When it is not sure,
it answers *"I don't know"* instead of guessing.

- **Accuracy:** heart rate within **−0.2 bpm** and SpO₂ within **−0.2%** of a commercial pulse oximeter (mean difference)
- **Reliability:** from 82 false "arrhythmia" results at rest down to **0**, after fixing lost samples, beat timing and training data
- **TinyML:** Edge Impulse model, **≈ 1.3 ms** per decision on the ESP32, 377 KB Flash
- **Data & analysis:** synthetic training data generated in Python, raw-signal recordings and analysis scripts

<a href="https://github.com/anastasiagkl18/smart-health-guardian">
  <img src="https://raw.githubusercontent.com/anastasiagkl18/smart-health-guardian/main/docs/images/bpm_vs_oximeter.png" alt="Heart rate: device vs. commercial oximeter" width="700">
</a>

#### [Smart Health Monitor](https://github.com/anastasiagkl18/Health-Monitor) · *IoT with Blynk*

An Arduino Mega 2560 with an ESP8266 that measures heart rate, SpO₂, temperature and humidity, shows them on an LCD
with a traffic-light LED, and sends them to the **Blynk Cloud** for remote monitoring, with phone alerts when values go
out of range. Non-blocking code (no `delay()`) keeps the sensor sampling at 400 Hz while the display and cloud update.

---

### 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Languages** | C/C++ (Arduino), Python |
| **Hardware** | ESP32, Arduino Mega 2560, ESP8266, MAX30102 / MAX30105, DHT11, I2C LCD |
| **AI & data** | Edge Impulse (TinyML), NumPy, SciPy, Matplotlib |
| **IoT** | Blynk, WiFi, I2C, UART |
| **Tools** | Arduino IDE, Git & GitHub |

---

### 📫 Contact

<!-- Fill in your own links and remove the lines you don't need -->
[LinkedIn](linkedin.com/in/anastasia-erla-gkikouli-1962a2436) 
