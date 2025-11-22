# Hardware Research — Non-EEG Epilepsy Detection System

---

## 1. ESP32 (Microcontroller)
### ✨ Why ESP32?
- Wi-Fi + Bluetooth built-in
- Dual-core processor (240 MHz)
- Low power consumption
- Perfect for wearable prototype
- Easy to program via Arduino IDE or MicroPython

### Variants:
| Model | Pros | Price |
|-------|------|-------|
| **ESP32 DevKit V1** | Most common, good pin availability | ₹450–₹550 |
| **ESP32 WROOM** | Compact | ₹350–₹450 |
| **ESP32-C3** | Low-power, BLE only | ₹350 |

---

## 2. MPU6050 (IMU Sensor)
Outputs:
- **Accelerometer** → detects shaking, spasms  
- **Gyroscope** → detects rotational jerks  

Why used in seizure detection:
- Generalized tonic-clonic seizures cause rhythmic high-amplitude motion
- IMU helps detect convulsions without EEG

Price: **₹150–₹250**  
Supplier: Robu.in, Amazon, ElectronicsComp

---

## 3. MAX30102 (Heart Rate + SpO2 Module)
Measurements:
- Heart rate
- Blood oxygen saturation
- PPG waveform

Seizure symptoms:
- HR spike before/during seizure  
- Oxygen drop during prolonged seizure

Price: **₹250–₹350**  
Supplier: Robu.in, Amazon

---

## 4. Battery + Power
- Li-ion 3.7V 1000mAh battery
- TP4056 charging module
- Step-up converter (if needed)

Estimated Cost: **₹200–₹300**

---

## 5. Total Estimated Cost (India)

| Component | Price |
|-----------|-------|
| ESP32 | ₹450 |
| MPU6050 | ₹200 |
| MAX30102 | ₹300 |
| Battery + Charger | ₹250 |
| Jumper Wires | ₹60 |
| Breadboard | ₹120 |

**Total: ₹1300–₹1500**

---
