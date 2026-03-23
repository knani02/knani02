<!-- ╔══════════════════════════════════════════════════════╗ -->
<!-- ║   README — Dhafer Knani · Electronics & Automation  ║ -->
<!-- ╚══════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25&height=280&section=header&text=Dhafer%20Knani&fontSize=72&fontColor=ffffff&fontAlignY=40&desc=Electronics%20%26%20Automation%20Engineer%20%7C%20Embedded%20%7C%20IoT%20%7C%20Space%20Tech%20🛰️&descSize=18&descAlignY=62&descColor=a0e4ff&animation=fadeIn" width="100%"/>

</div>

<div align="center">

<a href="https://readme-typing-svg.demolab.com">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&pause=1200&color=00E5FF&center=true&vCenter=true&width=680&lines=🛰️+CubeSat+ADCS+%7C+Kalman+Filter+%7C+Sensor+Fusion;⚡+Embedded+C+%7C+STM32+%7C+FreeRTOS+%7C+Bare-Metal;🔌+PCB+Design+%7C+KiCad+%7C+Altium+%7C+Altium+Designer;🏭+PLC+%7C+SCADA+%7C+TIA+Portal+%7C+Industrial+IoT;📡+ESP32+%7C+LoRa+%7C+MQTT+%7C+Grafana+%7C+AWS+IoT;🎓+École+Polytechnique+de+Sousse+%7C+Tunisia+🇹🇳" alt="Typing SVG"/>
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dhafer%20Knani-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhafer-knani-b363b72a6/)
[![Gmail](https://img.shields.io/badge/Gmail-dhaferknani02-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhaferknani02@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-knani--dhafer-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/knani-dhafer)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=knani-dhafer&color=00e5ff&style=flat-square&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/knani-dhafer?style=flat-square&color=00e5ff&label=Followers)

</div>

---

<img align="right" width="360" src="https://github-readme-stats.vercel.app/api?username=knani-dhafer&show_icons=true&theme=tokyonight&bg_color=0d1117&border_color=00e5ff&title_color=00e5ff&icon_color=79c0ff&text_color=c9d1d9&count_private=true&include_all_commits=true&hide_border=false"/>

### 👨‍🔬 About Me

🎓 **Final-year student** @ École Polytechnique de Sousse  
🏛️ Degree: **Electronics & Automatic Engineering** *(in progress)*  
📍 **Sousse, Tunisia** 🇹🇳  
🛰️ Current research: **CubeSat Attitude Determination** @ CRMN  
🧠 I live at the intersection of **hardware + firmware + control theory**  
⚡ I turn datasheets into working systems  

```yaml
name        : Dhafer Knani
role        : Electronics & Automation Engineer
school      : École Polytechnique de Sousse
research    : CubeSat ADCS — Sensor Fusion of MEMS sensors
supervisor  : Prof. Mounir Ben Ali @ CRMN, Sousse
languages   : [C, C++, Python, MATLAB, Ladder Logic, ST, VHDL]
interests   : [Embedded Systems, Space Tech, Industrial IoT, Control Theory]
currently   : "Building a Kalman Filter that runs in orbit 🛰️"
```

<br clear="right"/>

---

## 🛰️ Flagship Project

<div align="center">

| | |
|:---:|:---|
| **Title** | Attitude Determination of a CubeSat using Sensor Fusion of MEMS Sensors |
| **Objective** | Determine real-time 3D orientation of a CubeSat using low-cost inertial MEMS sensors |
| **Algorithms** | Extended Kalman Filter · Complementary Filter · AHRS (Madgwick / Mahony) |
| **Sensors** | IMU (Accel + Gyro) · Magnetometer · Barometer |
| **Target HW** | STM32 — bare-metal C, real-time execution on CubeSat OBC |
| **Simulation** | MATLAB / Simulink — filter validation before hardware deployment |
| **Supervisor** | Prof. Mounir Ben Ali |
| **Institution** | CRMN — Centre de Recherche en Microélectronique et Nanotechnologie, Sousse 🇹🇳 |
| **Status** | 🔄 In progress · `[████████░░]` · Publishing soon |

</div>

> *Sensor fusion pipeline:* **Raw IMU → Bias removal (Allan variance) → EKF prediction/update → Quaternion attitude → Euler angles**

---

## 🔧 Technical Stack

<details open>
<summary><b>⚙️ Embedded Systems & Firmware</b></summary>

<br/>

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4EAA25?style=flat-square&logo=freertos&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/RPi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-FF7F00?style=flat-square&logo=platformio&logoColor=white)

</div>

| MCU Platform | Toolchain | Applications |
|---|---|---|
| **STM32 F1 / F4 / H7** | STM32CubeIDE · HAL · LL · CMSIS | Motor control · DSP · ADCS · Real-time |
| **ESP32 / ESP8266** | ESP-IDF · Arduino Core | IoT nodes · OTA · WiFi/BLE gateways |
| **Arduino / AVR** | PlatformIO · bare metal | Prototyping · education |
| **PIC 16/18/32** | MPLAB X · XC8/XC16/XC32 | Industrial retrofitting |
| **Raspberry Pi** | Linux · Python · GPIO | Edge computing · HMI · vision |
| **TI MSP430** | Code Composer Studio | Ultra-low power sensor nodes |

**Firmware expertise:**
`Bare-metal C` · `FreeRTOS` (tasks, queues, semaphores, SW timers) · `DMA / TIM / ADC / PWM / UART / SPI / I2C / CAN` · `Bootloader & OTA` · `Low-power optimization (µA profiling)` · `Unity/Ceedling testing`

</details>

<details open>
<summary><b>🔌 PCB Design & Hardware</b></summary>

<br/>

<div align="center">

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-900000?style=flat-square&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-1BA3DD?style=flat-square&logoColor=white)

</div>

```
Concept → Schematic → Layout → DRC/ERC → Gerber → Fabrication → Bring-up → Test
```

| Domain | Details |
|---|---|
| **Analog design** | Op-amp circuits · active/passive filters · ADC/DAC signal conditioning |
| **Power electronics** | Buck/Boost converters · LDO regulators · motor gate drivers (H-bridge, MOSFET) |
| **RF & Antenna** | Impedance matching · SMA/U.FL connectors · controlled-impedance traces (50 Ω) |
| **Signal integrity** | Length matching · via stitching · GND pour · layer stack-up planning |
| **EMC / EMI** | TVS protection · ferrite beads · decoupling strategy · ESD guard rings |
| **Layout complexity** | Up to 6 layers · 0402 / QFP / QFN / BGA passives · custom footprint libraries |

</details>

<details open>
<summary><b>🌐 IoT & Wireless Systems</b></summary>

<br/>

```
[SENSOR] ──► [MCU / SBC] ──► [PROTOCOL] ──► [BROKER] ──► [CLOUD] ──► [DASHBOARD]
  MEMS           STM32             MQTT         Mosquitto    AWS IoT      Grafana
  Temp/Hum       ESP32             HTTP/REST     Node-RED     Azure IoT    Home Asst.
  Gas / Light    Raspberry Pi      WebSocket     EMQX         InfluxDB     Custom UI
```

| Protocol | Range | Best for |
|---|---|---|
| **LoRa / LoRaWAN** | 2–15 km | Remote low-power sensor networks |
| **WiFi 802.11 b/g/n** | ~100 m | High-bandwidth IoT nodes |
| **BLE 5.0** | ~50 m | Wearables, beacons, mesh |
| **RS-485 / Modbus** | ~1.2 km | Industrial field devices |
| **Zigbee 802.15.4** | ~100 m | Mesh home & factory automation |
| **NB-IoT / LTE-M** | Cellular | Wide-area, battery-operated |

</details>

<details open>
<summary><b>🏭 Industrial Automation & PLC</b></summary>

<br/>

<div align="center">

![Siemens](https://img.shields.io/badge/Siemens-009999?style=flat-square&logo=siemens&logoColor=white)
![Allen Bradley](https://img.shields.io/badge/Allen--Bradley-FF0000?style=flat-square&logoColor=white)
![Schneider](https://img.shields.io/badge/Schneider%20Electric-3DCD58?style=flat-square&logo=schneiderelectric&logoColor=white)

</div>

| Vendor | Hardware | Software |
|---|---|---|
| **Siemens** | S7-300 / S7-1200 / S7-1500 | TIA Portal · WinCC · PLCSIM |
| **Allen-Bradley** | CompactLogix / MicroLogix | Studio 5000 · FactoryTalk |
| **Schneider Electric** | Modicon M340 / M580 | Unity Pro · EcoStruxure |

**IEC 61131-3 languages:** `Ladder (LD)` · `Function Block (FBD)` · `Structured Text (ST)` · `Statement List (STL)` · `Sequential Function Chart (SFC)`

**Industrial fieldbus:** `PROFIBUS DP/PA` · `PROFINET IO` · `Modbus RTU/TCP` · `EtherNet/IP` · `OPC-UA` · `AS-Interface`

</details>

<details>
<summary><b>🧮 Control Theory & Signal Processing</b></summary>

<br/>

```python
control_toolkit = {
    "classical"  : ["PID (Ziegler–Nichols, IMC, Cohen-Coon)", "Bode/Nyquist", "Root locus"],
    "modern"     : ["State-space", "LQR / pole placement", "Luenberger observer"],
    "estimation" : ["Extended Kalman Filter (EKF)", "Complementary Filter",
                    "AHRS — Madgwick / Mahony", "Allan variance · bias estimation"],
    "digital_sp" : ["IIR / FIR filter design", "FFT & spectral analysis",
                    "Discretization: ZOH, Tustin/bilinear"],
    "simulation" : ["MATLAB / Simulink", "Hardware-in-the-Loop (HIL)", "co-simulation"],
}
```

![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Python](https://img.shields.io/badge/SciPy%20%7C%20NumPy%20%7C%20Matplotlib-3776AB?style=flat-square&logo=python&logoColor=white)

</details>

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=knani-dhafer&layout=compact&theme=tokyonight&bg_color=0d1117&border_color=00e5ff&title_color=00e5ff&text_color=c9d1d9&langs_count=8"/>
&nbsp;&nbsp;
<img height="170" src="https://streak-stats.demolab.com?user=knani-dhafer&theme=tokyonight&background=0d1117&border=00e5ff&stroke=00e5ff&ring=00e5ff&fire=ff9900&currStreakLabel=00e5ff&sideLabels=79c0ff&currStreakNum=ffffff&sideNums=ffffff&dates=555e7a"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=knani-dhafer&bg_color=0d1117&color=00e5ff&line=79c0ff&point=00e5ff&area_color=0d2137&area=true&border_color=00e5ff&custom_title=Contribution+Activity" width="96%"/>

<br/>

[![trophy](https://github-profile-trophy.vercel.app/?username=knani-dhafer&theme=tokyonight&column=7&margin-w=8&no-bg=true&no-frame=false)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📜 Credentials

| 🏅 Credential | 🏢 Institution | 📅 |
|---|---|---|
| **Internship Certificate** — CubeSat ADCS Research | CRMN Sousse · Prof. Mounir Ben Ali | 2025/2026 |
| **Diplôme d'Ingénieur** — Electronics & Automatic Engineering | École Polytechnique de Sousse | In progress |

---

## 🔭 What's Next

```bash
$ cat ~/roadmap.txt

  [████████░░]  cubesat_adcs/       → Finalizing EKF on STM32 · publishing soon
  [████░░░░░░]  fpga_learning/      → Xilinx Artix-7 · VHDL · digital design
  [███░░░░░░░]  tinyml_stm32/       → TensorFlow Lite · anomaly detection on MCU
  [██░░░░░░░░]  ros2_robot/         → ROS2 + Nav2 · autonomous mobile platform
  [█░░░░░░░░░]  digital_twin/       → Simulink + Factory I/O · virtual commissioning

  Learning queue → FPGA · ROS2 · Edge AI · Functional Safety (IEC 61508)
```

---

## 🤝 Let's Build Something

<div align="center">

I'm actively looking for **internship opportunities**, **research collaborations**, and **open-source projects** in:

`Embedded Systems` · `CubeSat / Aerospace` · `Industrial IoT` · `PCB Hardware` · `Control Systems`

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhafer-knani-b363b72a6/)
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhaferknani02@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25&height=130&section=footer&text=Soldering%20by%20day%20·%20Committing%20by%20night%20⚡&fontSize=16&fontColor=a0e4ff&fontAlignY=65" width="100%"/>

<sub><b>Dhafer Knani</b> · Electronics & Automation Engineer · Sousse, Tunisia 🇹🇳</sub>

</div>
