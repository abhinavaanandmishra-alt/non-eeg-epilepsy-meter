# 9-Week Project Timeline — Non-EEG Epilepsy Detector

---

## 🗓 WEEK 1 — Setup & Planning
- Create GitHub repo
- Install Python environment
- Create Streamlit basic simulator
- Begin hardware research
- Create Trello/Notion task board

---

## 🗓 WEEK 2 — Dataset Collection
- Download small seizure datasets (1–5GB)
- Explore CHB-MIT, Kaggle datasets
- Extract sampling rate, annotations, seizure labels

---

## 🗓 WEEK 3 — Data Preprocessing
- Convert EEG data to usable ML format
- Extract motion-like features from EEG for simulation
- Create CSV files for ML training

---

## 🗓 WEEK 4 — Hardware Finalization
- Select ESP32 version (NodeMCU vs DevKit)
- Finalize sensors: MPU6050 + MAX30102
- Bill of Materials (BOM) + pricing + suppliers

---

## 🗓 WEEK 5 — Algorithm Research
- Study seizure biomarkers:
  - Accelerometer spikes
  - Gyroscope oscillations
  - Heart rate elevation
  - SpO2 fluctuations
- Select ML approach (SVM, RF, CNN, LSTM)

---

## 🗓 WEEK 6 — ML Model (Prototype)
- Implement baseline classifier
- Train on simulated sensor data
- Evaluate accuracy, F1-score

---

## 🗓 WEEK 7 — Hardware Integration
- ESP32 + Sensor wiring
- Test I2C communication
- Read IMU + PPG data in Python

---

## 🗓 WEEK 8 — System Integration
- Send sensor data ESP32 → PC
- Live Streamlit visualization
- Combine ML model with real data feeds

---

## 🗓 WEEK 9 — Final Testing & Documentation
- End-to-end testing
- Prepare demo
- Complete GitHub documentation
- Submit project report
