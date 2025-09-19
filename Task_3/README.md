# 🌟 Task 3: Average Intensity Tracking System  

This project builds upon the light monitoring framework by introducing **long-term average intensity tracking**.  
In addition to real-time monitoring, the system features a **dedicated seven-segment display** that shows the **average light intensity** measured over a configurable time window of **300–900 seconds**.  

To improve flexibility, the design also includes a **manual reset option**, allowing users to clear the previous average and start fresh tracking instantly.  

---

## 🔧 Features  
- ⏱ **Adjustable Averaging Period**: Configure averaging duration from **300–900 seconds**.  
- 📟 **Dual Display**:  
  - First seven-segment display → **Real-time light intensity (0–7)**  
  - Second seven-segment display → **Average light intensity (0–7)**  
- 🔄 **Reset Functionality**: Instantly clears stored average data for a fresh calculation cycle.  
- ⚖️ **Stable Monitoring**: Smooths out fluctuations to highlight long-term light behavior.  

---

## 📂 Repository Contents  
- `circuit3.txt` → Falstad circuit export file (open in [Falstad Circuit Simulator](https://www.falstad.com/circuit/))  

---

## ▶️ How to Run the Circuit  
1. Open [Falstad Circuit Simulator](https://www.falstad.com/circuit/).  
2. Go to **File → Import**.  
3. Copy-paste the contents of `circuit3.txt`.  
4. Set the **averaging period (300–900s)** as required.  
5. Run the simulation to observe both **real-time intensity** and **average intensity tracking**.  
6. Use the **reset control** to clear stored averages and restart tracking.  

---

## 📸 Preview (Optional)  
  
<img width="1913" height="920" alt="Screenshot 2025-09-19 105956" src="https://github.com/user-attachments/assets/062603a0-ede3-4122-beaf-b6a1ed578669" />

