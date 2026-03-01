# HELIO-FLEX-SOLAR-AND-KINETIC-POWERED-MOBILE-CHARGER-DASHBOARD
⚡ HELIO FLEX  
## Solar + Kinetic Hybrid Charging Intelligence Dashboard

HELIO FLEX is a futuristic dual-source renewable energy monitoring dashboard designed for a **Solar + Electromagnetic Induction powered mobile charger**.

This repository contains the front-end implementation (`helio-flex.html`) that visualizes:

- Real-time solar power generation
- Real-time kinetic energy harvesting
- Combined output analysis
- Charging efficiency metrics
- Battery estimation and event logs

---

## 🚀 Live Dashboard Features

### ☀ Solar Monitoring
- Photovoltaic output (Watts & mA)
- MPPT-based optimization simulation
- Solar efficiency visualization
- Solar trend analytics

### ⚡ Kinetic Energy Monitoring
- Electromagnetic induction power output
- Neodymium magnet coil simulation
- Frequency-based harvesting analytics
- Kinetic efficiency breakdown

### 🔋 Battery & Charging Intelligence
- Estimated time to full charge
- Battery percentage tracking
- Combined power computation
- Thermal and conversion loss visualization

---

## 📊 Analytics Engine

The dashboard includes:

- 📈 **Line Chart (Trend Analysis)**  
  - Hourly / Daily / Weekly modes  
  - Solar vs Kinetic comparison  

- 🥧 **Doughnut Chart (Energy Split)**  
  - Real-time solar vs kinetic contribution  

- 📊 **Bar Chart (Daily Energy Generation)**  

- 📉 **Efficiency Bars**
  - Solar efficiency
  - Kinetic efficiency
  - Combined system performance
  - Thermal loss
  - Energy retention

---

## 🧠 Real-Time Data Simulation

The dashboard uses an internal `DataEngine` object to simulate real-time fluctuations:

```javascript
const DataEngine = {
  solar: 4.7,
  kinetic: 2.1,
  battery: 73,
  tick() { ... }
}
