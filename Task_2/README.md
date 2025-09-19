# 🌟 Task 2: Stability Control in Light Monitoring System  

This project introduces a **Stability Control Mechanism** to enhance the reliability of light intensity monitoring.  
Unlike direct real-time outputs, the system validates the sensor readings by ensuring that the **light level remains stable** for a **user-defined duration (30–300 seconds)** before updating the display.  

This approach eliminates **false triggers** and **fluctuations** caused by sudden light changes, delivering **consistent and trustworthy data**.  

---

## 🔧 Features  
- ⏱ **Configurable Stability Period**: User can set stability duration anywhere between **30–300 seconds**.  
- ⚖️ **Reliable Output**: Output updates only after the input light level has stayed constant during the set time window.  
- ❌ **Noise & Fluctuation Reduction**: Filters out sudden spikes or drops in light intensity.  
- 📟 **Seven-Segment Display Output**: Shows the stable light intensity level from `0` (lowest) to `7` (highest).  

---

## 📂 Repository Contents  
- `circuit2.txt` → Falstad circuit export file (open in [Falstad Circuit Simulator](https://www.falstad.com/circuit/))  

---

## ▶️ How to Run the Circuit  
1. Open [Falstad Circuit Simulator](https://www.falstad.com/circuit/).  
2. Go to **File → Import**.  
3. Copy-paste the contents of `circuit2.txt`.  
4. Adjust the **stability control timer (30–300s)** as required.  
5. Run the simulation to see how output is displayed **only after stable light levels are maintained**.  

---

## 📸 Preview (Optional)  
<img width="1913" height="927" alt="Screenshot 2025-09-19 105223" src="https://github.com/user-attachments/assets/9101be2b-ee35-40c3-a2b8-c59c57434122" />
  


