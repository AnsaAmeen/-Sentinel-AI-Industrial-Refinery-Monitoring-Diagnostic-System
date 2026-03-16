**Sentinel-AI: Industrial Refinery Monitoring & Diagnostic System**

Sentinel-AI is a high-precision autonomous framework designed to transform raw industrial sensor data into actionable intelligence. By bridging the gap between Real-Time Data Acquisition and Generative AI Diagnostics, it ensures 24/7 overwatch for critical refinery operations.

**System Architecture & Workflow Phases**

The system is architected into four intelligent operational phases, ensuring data integrity and rapid response:

**Phase 1: Data Ingestion & Screening**

Automated Pulse: Monitors every 60 seconds via a Schedule Trigger.
Dynamic Retrieval: Fetches real-time telemetry (Temp, Vibration, Pressure) via REST APIs.
Data Normalization: Custom JavaScript Logic processes and sanitizes JSON payloads for downstream analysis.

**Phase 2: Intelligent Routing (Predictive Engine)**

Threshold Logic: An advanced IF Node structure evaluates data against safety compliance standards.
Dynamic Pathing: * Emergency: Triggers immediate AI Diagnostic & high-priority alerts.
Warning: Logs cautionary data for maintenance review.
Normal: Continues routine monitoring with zero-alarm interference.

**Phase 3: AI Diagnostics & Multi-Channel Dispatch**

Cognitive Analysis: The LLM Agent (Gemini) interprets correlations between multiple sensor spikes to predict potential mechanical failures.
Instant Alerting: Dispatches professional reports and instant notifications via Slack (Engineering) and Gmail (Management).
Visual Reporting: Generates human-readable HTML summaries for rapid decision-making.

**Phase 4: Archival & System Integrity**

Audit Trail: Every incident is logged into Google Sheets for trend analysis and regulatory compliance.
Fail-Safe Integrity: Integrated a dedicated Error Trigger flow. In case of a node failure, the system automatically alerts the admin, ensuring the monitoring remains active.

**Technical Hurdles & Resolutions**

Cloud Infrastructure: Successfully deployed and managed the n8n environment on AWS EC2 using Docker.
Resource Management: Overcame disk storage constraints (No space left on device) through Docker image optimization.
Connectivity: Debugged and resolved complex CORS and Secure Cookie issues to allow secure remote access via Public IP.
Logic Optimization: Designed a 28-node sequence that balances high-speed processing with deep AI analysis.

**Business Use Cases**

Preventive Maintenance: Reducing unplanned downtime in refineries by 30%.
Safety Compliance: Automated logging for environmental and safety audits.
Unmanned Operations: AI-driven monitoring for remote industrial sites.

**Future Roadmap**

Integration of a real-time visual dashboard using Grafana.
Adding Predictive Maintenance models based on historical Google Sheets data.
Multi-language support for global engineering teams.

**Tech Stack**

Automation: n8n
AI Brain: Google Gemini 1.5 Pro
Cloud: AWS EC2 (Ubuntu), Docker
Tools: Slack API, Google Sheets, JavaScript

**👤 Author**

Ansa AI Automation & Industrial IoT Engineer
