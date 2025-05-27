
# Anomaly Detection in Load Forecasting Using ARIMA and Autoencoder

This repository contains the code and data for the research paper:

"Anomaly Detection in Load Forecasting Using ARIMA and Autoencoder" 
Authors: Arun Abhishek I, Dafinny Thanigaivel  
Published in the **2023 IEEE Fifth International Conference on Advances in Electronics, Computers and Communications (ICAECC)** — [Paper PDF](Anomaly_detection_in_load_forecasting_using_ARIMA_and_Autoencoder copy.pdf)

---

## Overview

Accurate short-term load forecasting is essential for power system planning and operation. This project compares two forecasting techniques — the classical **ARIMA** model and a deep learning **Autoencoder** model — to predict electrical load and detect anomalies caused by cyberattacks on load data. We evaluate model performance on real ISO New England load data and simulate cyberattacks such as pulse, scaling, ramping, and random attacks. Anomaly detection is based on a Gaussian 3-sigma statistical rule applied to forecast errors.

---

## Features

- Load forecasting using ARIMA and Autoencoder models  
- Detection of anomalies introduced by cyberattack scenarios  
- Performance evaluation with metrics including MAPE, precision, recall, and F1-score  
- Visualization of forecasting results and confusion matrices  
- Code and dataset provided for replication and further research  

---

## Dataset

- Hourly load data from ISO New England, January – June 2022  
- Training data: Jan 1 – Jun 20, 2022  
- Testing data: Jun 21 – Jun 30, 2022  
- Dataset file: `important1.csv`

---

## Getting Started

### Prerequisites

- Python 3.x  
- Jupyter Notebook or JupyterLab  
- Python packages:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow pmdarima
