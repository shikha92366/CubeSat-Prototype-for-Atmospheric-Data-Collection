<!-- HEADER -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=900&height=100&duration=4000&lines=CubeSat+Prototype+for+Atmospheric+Data+Collection+🛰️" />
</h1>

<h3 align="center">🚀 Designed for Atmospheric Research & Sensor Telemetry</h3>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1ddd5e78-e540-4a87-a175-9882584f0132" width="420" alt="CubeSat Prototype Image">
      <br>
      <em>View1</em>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/861da29a-c240-452a-8f0e-388848a82ee2" width="420" alt="CubeSat Prototype Second View">
      <br>
      <em>View2</em>
    </td>
  </tr>
</table>

---

<p align="center">
  <a><img src="https://img.shields.io/badge/Platform-Arduino-blue?style=for-the-badge"></a>
  <a><img src="https://img.shields.io/badge/Communication-LoRa%20SX1278-green?style=for-the-badge"></a>
  <a><img src="https://img.shields.io/badge/Wiring-Zero%20PCB-orange?style=for-the-badge"></a>
  <a><img src="https://img.shields.io/badge/Category-CubeSat%20Prototype-red?style=for-the-badge"></a>
</p>

---

## 🛰️ About the Project

This is a **miniaturized CubeSat prototype** developed for atmospheric data collection and wireless telemetry.

It features:
- **Zero-PCB internal wiring** (compact internal structure like real CubeSats)
- **Atmospheric + air quality sensor suite**
- **LoRa SX1278** based long-range transmission

The goal was to simulate a real CubeSat environment on ground with **sensor fusion + wireless telemetry**.

---

## 🔧 Hardware Components Used

| Component | Purpose |
|----------|---------|
| **BMP180** | Pressure + temperature (altitude detection) |
| **MQ-4** | Methane gas detection |
| **MQ-135** | Air quality / pollutant sensing |
| **IMU Module** | Orientation & motion tracking |
| **DS1307 RTC** | Timestamp logging |
| **LoRa SX1278** | Wireless telemetry |
| **Battery + Buck Converter** | Power regulation and distribution |

---

## ⚙️ System Architecture

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Courier&size=22&center=true&vCenter=true&width=700&height=70&duration=3800&lines=Sensor+Data+-->+MCU+-->+LoRa+Transmission" />
</p>

```
[Sensors: BMP180 + MQ4 + MQ135 + IMU]
                 ↓
              [MCU]
                 ↓
     [LoRa SX1278]  →  Ground Station Receiver
                 ↑
   [Battery + Buck Converter + DS1307 RTC]
```

---

## 🌐 Features

✅ Zero-PCB wiring (raw prototyping approach like in early CubeSat R&D)  
✅ Real-time atmospheric + air quality telemetry  
✅ Low power, modular design  
✅ Compact internal structure  

---

## 📊 Data Measured

| Sensor Data | Parameter |
|------------|-----------|
| BMP180 | Altitude / Pressure / Temperature |
| MQ-135 | Air Quality Index |
| MQ-4 | Methane Concentration |
| IMU | Roll-Pitch-Yaw Orientation |
| DS1307 | Timestamp Logging |

Data packets were transmitted via **LoRa SX1278** to the ground station.

---

## 🚀 Future Scope

- Custom PCB instead of zero-wiring prototype
- GPS integration for geo-tracking
- Weather balloon deployment for high-altitude testing

---

## 👨‍🚀 Developed By

[Shikha](https://www.linkedin.com/in/shikha2006/)
[Rahul](https://www.linkedin.com/in/rahul-kumar-rk212004/?lipi=urn%3Ali%3Apage%3Ad_flagship3_detail_base%3BTlsFkM0%2FT%2FGMmACkCoS%2F9Q%3D%3D)
[Arya](https://www.linkedin.com/in/arya-mishra-43307525a/?lipi=urn%3Ali%3Apage%3Ad_flagship3_detail_base%3BTlsFkM0%2FT%2FGMmACkCoS%2F9Q%3D%3D)
 

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Curiosity%20%26%20Soldering-orange?style=for-the-badge">
</p>

---

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=30&center=true&vCenter=true&width=700&height=70&duration=4000&lines=Exploring+Beyond+Boundaries+🌌;From+Prototypes+to+Space+Dreams+🚀" />
</h1>
