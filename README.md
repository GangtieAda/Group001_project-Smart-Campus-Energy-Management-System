# Smart Campus Energy Management System

Group 001 – Project Summary

------------------------------------

## 1. Overview

A campus-wide Smart Energy Management System integrating IoT sensors, cloud analytics, and automated building controls to reduce energy consumption and improve operational efficiency.



## 2. System Architecture
	•	Sensing Layer: Smart meters, motion/temperature sensors
	•	Data Layer: GCP (Compute Engine, Storage, BigQuery)
	•	Analytics: Energy forecasting, anomaly detection
	•	Control: Siemens Desigo CC via BACnet
	•	Interface: Dashboard for facility managers



## 3. Core Features
	•	Real-time energy monitoring
	•	Predictive modeling for demand optimization
	•	Automated HVAC and lighting control
	•	Alerts for abnormal consumption
	•	Campus-wide usage visualizations



## 4. Technologies

Python • FastAPI • Streamlit • MQTT
Google Cloud Platform • BigQuery
Siemens Desigo CC (BACnet)



## 5. Cost Summary

Desigo CC Integration – $15,000
	•	Base license: $9,500
	•	BACnet integration: $4,000
	•	Maintenance (10–15%): $1,500

GCP Cloud Services – $5,000/year
	•	Compute Engine, Storage, BigQuery, monitoring



## 6. Repository Structure

```
src/        # Backend, sensors, analytics
dashboard/  # Visualization UI
data/       # Audit + sensor datasets
docs/       # Charter, risks, reports
```


## 7. Quick Start

```
pip install -r requirements.txt
python src/backend/app.py
streamlit run dashboard/app.py
```


## 8. Contacts

Group001
Kayode Babalola • Qianru Deng • Priyanka Sharma
