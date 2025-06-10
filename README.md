# 💡 Automatic Light Control System  

A **hardware-based automation project** that controls lights based on door activity, developed for my university's electronics lab. Uses a 555 Timer IC and LM741 comparator to trigger lighting only when needed, promoting energy efficiency.  
**Circuit designed and simulated using NI Multisim.**  

## 🛠️ Hardware Components  
- **Core ICs**:  
  - LM741 Comparator (Detects door state)  
  - 555 Timer IC (Monostable mode for timed activation)  
- **Design Tools**: NI Multisim (Circuit simulation & validation)  
- **Sensors**: Normally Closed (NC) Door Switch  
- **Power**: Dual supply (5V for logic, 12V for relay/light)  

## ⚙️ Key Features  
- **Energy Efficient**: Lights activate **only** when door opens  
- **Simulation-Proven**: Design validated in NI Multisim before hardware implementation  
- **Adjustable Timing**: Customize light duration via RC components (`T = 1.1 × R2 × C3`)  

## 🔌 Circuit Setup  
1. **Simulation**: Prototyped in NI Multisim 
2. **Door Switch**: Mount where door fully opens (e.g., wall contact)  
3. **Comparator**: Reference voltage vs. switch voltage  

## 📝 Notes  
- **Academic Project**: Demonstrates analog/digital circuit integration  
- **Tools Used**: NI Multisim (Design), PCB Fabrication Tools (Implementation)  
- **Future Upgrades**:  
  - Add LDR for ambient light detection  
  - IoT integration (ESP8266 for remote alerts)  
