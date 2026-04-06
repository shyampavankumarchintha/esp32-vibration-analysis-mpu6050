# Vibration Analysis using MPU6050 and ESP32

## 📌 Overview

This project detects abnormal vibrations using MPU6050 sensor and ESP32, and analyzes the signal using Python.

## ⚙️ Components

* ESP32
* MPU6050
* Wokwi Simulator
* Python (Google Colab)

## 📊 Methodology

1. Collected vibration data (normal & abnormal)
2. Plotted time-domain signals
3. Computed vibration magnitude
4. Performed FFT analysis
5. Compared RMS values

## 📈 Results

* Normal signal is smooth
* Abnormal signal shows spikes
* FFT shows higher frequency components in abnormal condition

## 📁 Files

* normal.csv → Normal data
* abnormal.csv → Fault data
* analysis.ipynb → Python analysis

## 🚀 Conclusion

This system can detect machine faults using vibration analysis techniques.
# esp32-vibration-analysis-mpu6050
Vibration signal analysis using MPU6050 and ESP32 with time-domain and frequency-domain (FFT) techniques in Python.
