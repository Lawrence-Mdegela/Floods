Flood Prediction and Early Warning System
Overview
This project focuses on applying machine learning models to address the challenge of flood prediction in resource-constrained settings, with a specific case study on the Pangani River Basin in Northern Tanzania. The primary objective is to develop one-day-ahead flood prediction models to improve early warning systems (EWS) and support flood risk management.

In addition to model development, the project includes the deployment of a low-cost data infrastructure using ultrasonic sensors to collect real-time river level data. This data infrastructure aims to bridge the data scarcity gap in developing regions, enabling continuous monitoring, model calibration, and future research.

Key Features
Flood Forecasting Models:
Developed and tested machine learning models, including LSTM and CNN-LSTM with attention mechanisms, for predicting river levels one day in advance.

Real-Time Data Collection:
Deployed ultrasonic sensors at two locations along the Kikuletwa River, providing hourly river level measurements. These sensors continuously monitor river behavior, generating a high-resolution data set that supports model calibration and validation.

Data Integration:
Integrated historical river level data with satellite-derived environmental variables (rainfall, temperature, relative humidity, and soil moisture) to improve model accuracy.

Anomaly Detection:
Implemented LSTM autoencoders and residual analysis techniques to identify anomalies in river level trends, supporting early flood detection.

Open Data Repository:
A portion of the collected data is publicly available on Zenodo to encourage further research and collaboration in flood management.

