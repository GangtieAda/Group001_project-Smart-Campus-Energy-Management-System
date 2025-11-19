# Smart Campus Energy Management System

Group 001 – Project Summary



## 1. Overview

A campus-wide Smart Energy Management System integrating IoT sensors, cloud analytics, and automated building controls to reduce energy consumption and improve operational efficiency.



## 2. System Architecture
- Sensing Layer: Smart meters, motion/temperature sensors
- Data Layer: GCP (Compute Engine, Storage, BigQuery)
- Analytics: Energy forecasting, anomaly detection
- Control: Siemens Desigo CC via BACnet
- Interface: Dashboard for facility managers



## 3. Core Features
- Real-time energy monitoring
- Predictive modeling for demand optimization
- Automated HVAC and lighting control
- Alerts for abnormal consumption
- Campus-wide usage visualizations



## 4. Technologies

| Layer | Technology |
|---------|----------|
| IoT & Data Ingestion | Python, MQTT, REST APIs |
| Backend | FastAPI / Flask |
| Cloud | Google Cloud Platform (Compute Engine, Storage, BigQuery) |
| Analytics | Python (Pandas, NumPy, Scikit-learn) |
| Interface | React or Streamlit |
| Controls | Siemens Desigo CC + BACnet |




## 5. Cost Summary

Labor - $214,000
- Energy Systems Engineer (800 hrs @ $55/hr): $44,000
- Electrical Contractors (1,200 hrs @ $40/hr): $48,000
- Software Developers – IoT & Dashboard (1,000 hrs @ $60/hr): $60,000
- Data Scientists – Optimization & Analytics (600 hrs @ $60/hr): $36,000
- Project Manager (400 hrs @ $65/hr): $26,000

Supplies & Technology - $87,500
- IoT Sensors (150 units @ $250): $37,500
- Networking Equipment (20 units @ $1,500): $30,000
- Cloud Services (GCP, 1 year: Compute + Storage + Monitoring): $5,000
- Control Software Licenses – Siemens Desigo CC (Base $9,500 + BACnet Integration $4,000 + Maintenance $1,500): $15,000

Miscellaneous - $20,325
- Staff Training & Workshops: $5,000
- Contingency (5%): $15,325

/Total Cost: USD 321,825/

## 6. Repository Structure

```
Group001_project-Smart-Campus-Energy-Management-System/
├── src/                    # Backend core, sensor interfaces & analytics modules
│   ├── sensors/           # Sensor data acquisition & communication
│   ├── analytics/         # Energy data analysis & core algorithms
│   ├── api/               # RESTful API endpoints
│   └── utils/             # Common utility functions
├── dashboard/              # Data visualization frontend application
│   ├── public/            # Static assets (images, favicons)
│   ├── src/               # React/Vue components & frontend logic
│   └── package.json       # Frontend dependencies configuration
├── data/                   # Data storage & audit directory
│   ├── raw/               # Raw datasets from sensors
│   ├── processed/         # Cleaned and processed data
│   └── audit_logs/        # System operations & data audit logs
├── docs/                   # Project documentation
│   ├── project_charter.pdf
│   ├── risk_assessment.md
│   └── project_reports/
├── presentation/           # Project demonstration materials
│   ├── demo_slides.pdf    # Final presentation slides
│   ├── video_walkthrough/ # Screen recording of system demo
│   └── screenshots/       # Key features and UI screenshots
├── methodology/           # Project management artifacts
│   ├── aha_screenshots/  # Product roadmap & feature definitions
│   ├── basecamp_screenshots/ # Project plans, todos & schedules
│   └── critical_path_analysis.md
└── README.md              # Project overview (this file)
```


## 7. Quick Start

```
pip install -r requirements.txt
python src/backend/app.py
streamlit run dashboard/app.py
```


## 8. Versioning
- v1.0 – Initial setup
- v1.1 – Mid-project progress
- v2.0 – Final release
- v2.1 – Final version

 
## 9. Contacts

Group001
- Kayode Babalola
- Qianru Deng
- Priyanka Sharma
