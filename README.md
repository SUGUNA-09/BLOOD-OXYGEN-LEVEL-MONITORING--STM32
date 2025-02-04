ML-Based SpO2 Monitoring System




This project focuses on the development of a machine learning-based SpO2 monitoring system using the MAX30100 sensor, an STM32 microcontroller, and Random Forest Regression for accurate and continuous blood oxygen saturation (SpO2) measurement. The system is designed for real-time, portable, and efficient remote health monitoring applications.

Features

Continuous SpO2 and heart rate monitoring

Noise reduction using a Kalman filter

Machine learning-based prediction using Random Forest Regression

Real-time data acquisition via STM32

FPGA-based USB communication for fast data transfer

Improved accuracy over traditional pulse oximeters

Compact and cost-effective design

Hardware Components

MAX30100 - Pulse oximetry and heart rate sensor

STM32 Microcontroller - Processes real-time sensor data

FPGA-based USB Interface - Enables high-speed data transfer

Power Supply & Supporting Components

Software & Libraries Used

STM32CubeIDE - Embedded firmware development

Python (for ML model training and testing)

Scikit-learn - Machine learning library

Kalman Filter - Noise filtering technique

USB Communication Drivers - For interfacing with the host system

System Workflow

The MAX30100 sensor captures raw SpO2 and heart rate data.

The STM32 microcontroller processes the sensor data and applies a Kalman filter to reduce noise.

The filtered data is sent to a Random Forest Regression model, which predicts more accurate SpO2 values.

Data is transmitted via FPGA-based USB communication to a host system.

The host system visualizes and analyzes the real-time SpO2 readings.

Installation & Setup

1. Clone the Repository
