# Project-Space-Cyber-Watchdog-Real-time-Satellite-Log-Monitoring-n8n-
Real-time satellite log monitoring and anomaly alerting using n8n automation workflows.


Space-Cyber Watchdog is a no-code automation system built using **n8n** to monitor satellite telemetry and system logs in real time. The workflow detects anomalous or suspicious log patterns and triggers alerts, enabling early identification of potential cyber threats in space systems.

---

##  Problem Statement
Modern satellites generate large volumes of operational and security logs. Manual monitoring is impractical and delays detection of cyber anomalies, misconfigurations, or intrusions. There is a need for automated, real-time monitoring and alerting.

---

##  Solution Overview
This project uses an **n8n workflow** to ingest satellite log data, evaluate it against predefined security rules, and flag abnormal behavior. The system acts as a cyber watchdog, continuously observing logs and responding instantly to suspicious events.

---

##  Workflow Architecture
Log Source → n8n Workflow → Rule Evaluation → Alert Trigger

---

##  Key Workflow Components
- **Trigger / Webhook Node** – Receives satellite log data
- **Processing Nodes** – Parse and normalize logs
- **Switch / Function Nodes** – Apply anomaly detection logic
- **Alert Node** – Sends alerts when thresholds are violated

---

##  Screenshots
See the `screenshots/` folder for:
- Workflow canvas
- Log processing logic
- Sample alert output

---

##🛠️ Tools Used
- n8n (No-code automation)
- JavaScript (Function nodes)
- Rule-based anomaly detection
- Webhooks / simulated log inputs

---

##  Key Takeaways
- Demonstrates real-time cyber monitoring for space systems
- Shows how no-code tools can solve security-critical problems
- Focuses on automation, reliability, and system safety

---

##  Author
Harshit Vaish
