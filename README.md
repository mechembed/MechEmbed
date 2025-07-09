<h1 align="center">🚀 MechEmbed | Embedded Systems & PCB Design Portfolio</h1>

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/219247273?v=4" width="150" alt="MechEmbed Logo" />
</p>

<p align="center">
  <b>Welcome to the official portfolio of <em>Noch Kakada</em></b><br>
  <sub>Embedded Systems Engineer | PCB Designer | Automotive & Industrial Electronics</sub>
</p>

<p align="center">
  <a href="https://github.com/mechembed">
    <img src="https://img.shields.io/github/followers/mechembed?label=Follow&style=social" alt="GitHub Follow" />
  </a>
  <a href="mailto:mechembed@techmail.com">
    <img src="https://img.shields.io/badge/email-mechembed@techmail.com-blue?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/nochkakada">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin" />
  </a>
</p>

---

## 👨‍💻 About Me

Hi, I'm **Noch Kakada**, founder of **MechEmbed**. I create embedded systems that power real-world automotive and industrial solutions — from robust hardware to efficient firmware.

> Passionate about bringing hardware to life through smart design, reliable code, and efficient prototyping.

---

## ⚙️ Skills & Tools

<table>
  <tr>
    <td><strong>🔧 Hardware</strong></td>
    <td>KiCad, Altium Designer, Schematic/Layout Design, Mixed Signal Circuits</td>
  </tr>
  <tr>
    <td><strong>👨‍💻 Firmware</strong></td>
    <td>C/C++, STM32CubeIDE, PlatformIO, FreeRTOS, Embedded Linux</td>
  </tr>
  <tr>
    <td><strong>🌐 Connectivity</strong></td>
    <td>CAN Bus, UART, I2C, SPI, MQTT, Zigbee, BLE, Wi-Fi</td>
  </tr>
  <tr>
    <td><strong>🧰 Other Tools</strong></td>
    <td>Python, Git, VS Code, Logic Analyzer, Serial Debugging</td>
  </tr>
</table>

---

## 🚀 Featured Projects

### ⚡ EV Charger with KHQR Payment & Android Integration  
> Smart EV charging system with contactless QR payment & mobile control

- **ESP32-based charger** with CAN bus to communicate with EVs (OCPP-ready optional)  
- **KHQR** (Cambodia's National QR Standard) for seamless digital payment  
- **Android app** to start/stop charging, show session status, and receive invoices  
- BLE connection to securely pair with the charger and configure parameters  
- **MQTT-based backend** for remote monitoring, usage history, and payment logging  
- Real-time current, voltage, and energy usage tracking with session timeout control

> 🔒 Secure | 📲 Mobile-Friendly | ⚡ Real-Time Control

---

### 🌊 Industrial Water Quality Monitoring  
> Modular IoT system for factory deployment

- pH, turbidity, and temperature sensors  
- Remote calibration and data logging  
- ESP32 + Cloud Sync

---

### ⚙️ STM32 Dual Motor PID Controller  
> Real-time motor feedback with RTOS

- Encoder and gyro-based feedback  
- PID speed control  
- PWM + FreeRTOS task scheduling

---

### 🚗 Engine Signal Simulator  
> For automotive ECU bench testing

- Cam & crank waveform generation  
- Custom RPM and phase controls  
- Signal tuning for diagnostics

---

### 📡 Zigbee Gateway Integration  
> ESP32-C6 + Zigbee radio module

- Sensor-to-gateway messaging  
- Supports mesh routing  
- Plug-in-ready for coordinators

---

## 🧪 Prototypes & Boards

| Product | Description |
|--------|-------------|
| 🧲 **Motor Driver Board** | Dual H-Bridge with current sensing |
| 📟 **Universal Sensor Board** | Li-ion charging, analog + digital sensor inputs |
| 🧼 **Mirror Cleaning Controller** | Automotive wiper motor logic with wash-mist cycle |
| 🌾 **Smart Farm Kit** | Soil moisture, climate sensing, LoRa/IoT ready |

---

## 🖼️ Project Visuals

### 📱 Android App UI

> EV Charger Control App (BLE + KHQR + MQTT)

<p align="center">
  <img src="./assets/app-home.png" width="250" alt="App Home Screen" />
  <img src="./assets/payment-success.png" width="250" alt="Payment Success Screen" />
  <img src="./assets/session-status.png" width="250" alt="Charging Session Screen" />
</p>

---

### 📊 Charging Session Graph

> Real-time voltage, current, and energy tracking via MQTT

<p align="center">
  <img src="./assets/session-graph.png" width="600" alt="Charging Session Graph" />
</p>

- Y-axis: Voltage (V), Current (A), Power (W)  
- X-axis: Time (min)  
- Logs published every 1s via MQTT and rendered on mobile app and web dashboard

---

### 💡 System Architecture Diagram

> Embedded & Android integration for smart charging

<p align="center">
  <img src="./assets/system-architecture.png" width="700" alt="System Architecture" />
</p>

**Includes:**
- ESP32 with CAN transceiver  
- BLE to Android  
- Payment server (KHQR Gateway)  
- MQTT broker for backend monitoring

---

### 🔐 KHQR Payment Flow

> Secure QR-based payment using Cambodian national standard

<p align="center">
  <img src="./assets/payment-flow.png" width="700" alt="KHQR Payment Flow" />
</p>

**Flow Summary:**
1. User connects to charger via Android app (BLE)  
2. App generates KHQR payload and displays QR code  
3. User scans QR via banking app  
4. Server verifies payment and returns secure token  
5. Charger unlocks and session begins

---

## 📫 Contact Me

- 📧 Email: [mechembed@techmail.com](mailto:mechembed@techmail.com)  
- 💻 GitHub: [github.com/mechembed](https://github.com/mechembed)  
- 🔗 LinkedIn: [linkedin.com/in/mech-embed-33667a373](https://www.linkedin.com/in/mech-embed-33667a373)


---

<p align="center">
  <sub>© 2025 MechEmbed | Designed & Built by Noch Kakada</sub>
</p>
