# 🛡️ Sentinel-AI: Industrial Refinery Monitoring & Diagnostic System

---

## An Autonomous AI-Driven Industrial Oversight & Alerting System

The **Sentinel-AI** is a modern, production-ready automation framework designed to monitor refinery health in real-time. It transforms raw sensor telemetry (Temperature, Pressure, Vibration) into intelligent, human-readable diagnostics and instant alerts—ensuring industrial safety and operational continuity without manual supervision.

---

## 📽️ Project Overview & Logic

The automation is implemented using **n8n** with a modular, scalable architecture. Each stage of the workflow is clearly separated to improve readability, debugging, and future extensibility. The system bridges the gap between raw data ingestion and high-level AI analysis.

### 🖼️ Workflow Architecture
https://github.com/AnsaAmeen/-Sentinel-AI-Industrial-Refinery-Monitoring-Diagnostic-System/blob/main/Workflowpng.png
https://github.com/AnsaAmeen/-Sentinel-AI-Industrial-Refinery-Monitoring-Diagnostic-System/blob/main/Google%20sheet%20record.png
https://github.com/AnsaAmeen/-Sentinel-AI-Industrial-Refinery-Monitoring-Diagnostic-System/blob/main/Email%20response.png

---

## 💎 Core Features

* 🤖 **AI-Powered Diagnostics**
    Uses **Google Gemini AI** to interpret complex sensor correlations and identify potential mechanical failures before they occur.
* 📡 **Real-Time Telemetry Processing**
    Automated data retrieval via REST APIs every 60 seconds, ensuring zero-latency monitoring.
* 🚀 **Multi-Channel Alerting**
    Instant notification dispatch via **Slack (Engineering)** and **Gmail (Management)** for critical threshold breaches.
* 📊 **Automated Audit Logging**
    Seamless integration with **Google Sheets** for long-term data archival and regulatory compliance.
* 🛡️ **Fail-Safe Integrity**
    Built-in error handling with a dedicated **Error Trigger** to notify administrators of any system downtime.

---

## 🛠️ Infrastructure & Tech Stack

* **Automation Engine:** n8n (Hosted on AWS EC2)
* **AI Model:** Google Gemini 1.5 Pro
* **Environment:** Docker & Ubuntu Linux
* **Languages:** JavaScript (for data normalization)
* **Integrations:** Slack API, Gmail SMTP, Google Sheets API

---

## 👤 Contributor

* **Ansa Ameen** — *AI Automation & Industrial IoT Engineer*
