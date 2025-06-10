# automatic-light-control-system

An energy-efficient automatic light control system using 555 Timer IC &amp; LM741 comparator | Detects door activity to trigger lighting | Hardware project with circuit design.

# 💡 Automatic Light Control System  

A **hardware-based automation project** that controls lights based on door activity, developed for my university's electronics lab. Uses a 555 Timer IC and LM741 comparator to trigger lighting only when needed, promoting energy efficiency.

## 🛠️ Hardware Components  
- **Core ICs**:  
  - LM741 Comparator (Detects door state)  
  - 555 Timer IC (Monostable mode for timed activation)  
- **Sensors**: Normally Closed (NC) Door Switch  
- **Power**: Dual supply (5V for logic, 12V for relay/light)  
- **Output**: 12V Light Bulb + Buzzer (optional)  
- **Passive Components**: Resistors, Capacitors (See [report](#) for values)  

## ⚙️ Key Features  
- **Energy Efficient**: Lights activate **only** when door opens  
- **Adjustable Timing**: Customize light duration via RC components (`T = 1.1 × R2 × C3`)  
- **Low-Cost Design**: Uses affordable, widely available components  
- **Scalable**: Can integrate motion/light sensors for advanced automation  

## 📋 How It Works  
1. **Door Opens** → NC switch breaks circuit  
2. **LM741 Comparator** detects voltage change → Triggers 555 Timer  
3. **555 Timer** (Monostable mode) keeps light ON for fixed duration  
4. **System resets** when door closes  

## 🔌 Circuit Setup  
1. **Door Switch**: Mount where door fully opens (e.g., wall contact)  
2. **Comparator**: Reference voltage vs. switch voltage  
3. **Timer**: Configure `R2` and `C3` for desired light duration (e.g., 1.1ms for `R2=1kΩ, C3=1µF`)  
4. **Relay**: Connect to 12V light bulb  

## 🏆 Applications  
- **Home Automation**: Wardrobes, refrigerators, entryways  
- **Security**: Alerts for unauthorized door openings  
- **Industrial**: Machine enclosure monitoring  

## 📝 Notes  
- **Academic Project**: Demonstrates analog/digital circuit integration  
- **Future Upgrades**:  
  - Add LDR for ambient light detection  
  - IoT integration (ESP8266 for remote alerts)  

