# Locomotive-Telemetry-Predictive-Maintenance-Hub
A full-stack SAP Cloud Application Programming (CAP) model application to monitor BNSF locomotive fleet health, automating the detection of critical engine status based on historical telemetry and model performance.

**Technical Stack:**

Backend: Node.js (SAP CAP Framework)

Database: SAP HANA / Core Data Services (CDS)

Frontend: SAP Fiori Elements (OData V4)

Development Environment: SAP Business Application Studio (BAS)

**Key Features & Logic:**

Automated Risk Modeling: Engineered a Node.js event handler in the service layer that scans incoming telemetry. For specific engine models (e.g., GE ES44C4), the system automatically flags the "Health Status" as Critical, simulating a predictive maintenance risk model.

Data Architecture: Designed a normalized schema in HANA to handle Locomotive master data, Telemetry logs, and Maintenance Alerts.

Enterprise UI: Built a Fiori Elements List Report with integrated filtering, enabling maintenance managers to instantly drill down into high-risk fleet segments.

Scalable Service Layer: Implemented custom OData actions to handle simulated high-temperature triggers, proving the system's ability to integrate with real-world IoT sensors.
