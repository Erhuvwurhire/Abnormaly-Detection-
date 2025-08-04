## Industrial Sensor Network – Anomaly Detection 
Detecting faults before failure: This project involved the use of unsupervised learning for predictive maintenance in manufacturing systems. 
Project Overview
The project implements unsupervised anomaly detection on high-dimensional sensor data from an industrial process. Using the SECOM dataset (real-world semiconductor manufacturing data), we identify abnormal patterns in sensor readings that could indicate faults, process drifts, or system failures.

## 📊 Dataset
Source: UCI Machine Learning Repository – SECOM Dataset
Description:

1567 samples (instances)

590 features (sensor measurements)

Missing values present (cleaned in preprocessing)

Originally used for semiconductor manufacturing process monitoring

## ⚙️ Project Structure
Industrial_Anomaly_Detection/
│
├── Industrial_Anomaly_Detection_SECOM.ipynb   # Main notebook (Colab compatible)
├── secom.data                                 # Raw dataset file
├── README.md                                  # Project overview
└── assets/                                    # Optional: image outputs or visualizations

## 🚀 How It Works
Data Loading: Raw .data file is loaded and cleaned (missing values handled).

Preprocessing: All columns are converted to numeric, missing values imputed with mean.

Visualization: Sensor trends are plotted for exploratory analysis.

Modeling: An unsupervised Isolation Forest model is trained to detect outliers.

Anomaly Scoring: Each instance is classified as either normal or anomalous.

Evaluation: Results are visualized to interpret sensor behavior and flagged anomalies.

