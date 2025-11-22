# Algorithm Research — Non-EEG Seizure Detection

---

## 1. Key Biomarkers for Seizure Detection
### Motion-based:
- Sharp accelerometer spikes
- Repetitive oscillatory motion
- High angular velocity
- Loss of balance patterns

### Heart-rate-based:
- Sudden HR increase (tachycardia)
- HR variability drop
- Post-seizure HR depression

### SpO2-based:
- Drop in oxygen saturation during prolonged seizures

---

## 2. Feature Extraction (IMU + PPG)
### From MPU6050:
- Mean, variance
- Peak amplitude
- RMS energy
- FFT frequency bands
- Jerk (derivative of acceleration)

### From MAX30102:
- HR peaks per minute
- HRV (Heart Rate Variability)
- SpO2 slope + drops

---

## 3. Machine Learning Approaches
### Basic Models:
- **Random Forest**
- **SVM**
- **KNN**
Best for small datasets.

### Deep Learning Models:
- **1D CNN** for motion patterns
- **LSTM** for temporal sequences
Helps identify rhythmic seizure motion.

### Fusion Models:
Combine IMU + PPG features:
- Concatenate features
- Train single classifier

---

## 4. Final Algorithm Pipeline
1. Collect IMU + PPG data  
2. Extract features  
3. Train ML model  
4. Deploy to ESP32 / PC  
5. Real-time seizure alert

