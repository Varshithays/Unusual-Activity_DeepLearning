# Unusual-Activity_DeepLearning

# ATM Unusual Activity Detection using YOLOv8

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![YOLOv8](https://img.shields.io/badge/Model-YOLOv8-green.svg)](https://ultralytics.com/)
[![Computer Vision](https://img.shields.io/badge/Field-Banking%20Security-red.svg)]()

## 📌 Project Overview
This repository contains a deep learning-based surveillance system designed to identify suspicious behaviors in ATM kiosks. By leveraging the **YOLOv8** architecture and custom-trained datasets, the system provides real-time anomaly detection and automated security alerts, significantly reducing the response time for banking security teams.

## 🚀 Key Features
* **Real-time Anomaly Detection:** Identifies activities such as unauthorized entry, robbery attempts, and suspicious loitering.
* **High Precision:** Optimized for the low-light and high-contrast environments typical of ATM kiosks.
* **Automated Alert System:** Integrated notification module that triggers a security email the moment a threat is detected.
* **End-to-End Pipeline:** Covers everything from video frame pre-processing to model inference and alert dispatch.

## 📊 Model Performance & Accuracy
The model was fine-tuned on custom datasets representing specific banking threats. It achieved a near-perfect accuracy rate, ensuring minimal false alarms.

### Performance Metrics Table


> **<img width="604" height="448" alt="image" src="https://github.com/user-attachments/assets/7fc47739-1f42-4c4e-9675-5a9cb21c1f60" />
**
> *Figure 1: Training metrics and accuracy results from the Jupyter Notebook.*

## ✉️ Security Notification System
A core feature of this project is the real-time alerting system. When the model detects an unusual activity with a confidence score above a set threshold, it automatically sends a detailed security alert via email.

### Alert Example
> **<img width="547" height="562" alt="image" src="https://github.com/user-attachments/assets/1e460de1-d190-438f-bb00-cc456518e9d5" />
**
> *Figure 2: Example of the automated security alert sent by the system.*

## 🛠️ Tech Stack
* **Algorithm:** YOLOv8 (You Only Look Once)
* **Language:** Python
* **Tools:** OpenCV, Ultralytics, Jupyter Notebook
* **Libraries:** Matplotlib, NumPy, SMTPlib (Email Integration)

## 📂 Repository Structure
* `ATM_Robbery_Detection.ipynb`: Main source code containing training and inference logic.
* `README.md`: Documentation and project details.

## 🏁 Conclusion
This project demonstrates the power of Computer Vision in FinTech security. By automating the monitoring process, banks can ensure 24/7 protection for their customers and assets with high reliability.

