# Backend Automation, IoT & AI Engineering Portfolio

**Real-world integration case studies by Luis David Ducuara Cadavid**  
Backend & Automation Developer · Mechatronics Engineering Student

I design systems that connect business processes, legacy platforms, payment services, cloud infrastructure, data, and physical devices. My engineering priorities are reliability, traceability, secure integration, and maintainable automation.

![Automation, IoT and AI systems connected through cloud APIs](docs/assets/automation-iot-ai-hero.jpg)

*Sanitized portfolio visualization reconstructed from approved project references. It contains no production data, customer branding, personal information, or functional codes.*

> These case studies summarize professional work developed at Ingeniot S.A.S. at a portfolio-appropriate level. Proprietary source code, production endpoints, credentials, customer data, contractual figures, and confidential implementation details are intentionally excluded.

## Portfolio at a glance

| Case study | Engineering problem | What it demonstrates |
| --- | --- | --- |
| [Healthcare self-service automation](#case-study-1-healthcare-self-service-kiosk-automation) | Coordinate appointments, legacy workflows, payments, and transactional evidence | APIs, RPA, webhooks, payment gateways, workflow state, auditability |
| [Environmental monitoring and HVAC automation](#case-study-2-environmental-monitoring-and-hvac-automation) | Monitor distributed environments and react safely to changing conditions | IoT telemetry, edge integration, alerts, reporting, control rules |
| [Access control analytics with AI](#case-study-3-access-control-analytics-with-natural-language-ai) | Make operational event data easier to query without exposing unrestricted database access | Event ingestion, controlled SQL, LLM integration, authorization, audit logs |

---

## Case Study 1: Healthcare Self-Service Kiosk Automation

### Challenge

High-volume service locations depend on several disconnected systems for appointment validation, arrival confirmation, payment collection, and transaction evidence. Repetitive manual steps can create queues and make end-to-end traceability difficult.

### Solution

A self-service workflow that coordinates authorized APIs, RPA actions, payment integrations, webhooks, and transactional records from a patient-facing kiosk.

![Healthcare kiosk, mobile services and cloud integration workflow](docs/assets/healthcare-self-service-automation.jpg)

*Reconstructed and anonymized portfolio visual. Screens, identities, brands, and data are illustrative.*

### Architecture

```mermaid
flowchart TD
    A["Kiosk application"] --> B["Automation backend"]
    B --> C["Scheduling API"]
    B --> D["RPA worker"]
    B --> E["Payment gateway"]
    C --> F["Audit and transaction records"]
    D --> F
    E --> F
```

### Main capabilities

- Same-day appointment validation through an authorized API.
- Automated arrival confirmation in a legacy operational system.
- Retrieval of applicable service fees.
- QR-based payment initiation and webhook-based confirmation.
- Receipt and transaction evidence generation.
- Explicit workflow states, retries, timeouts, and assisted fallback paths.
- Auditable coordination between customer-facing and back-office systems.

### My contribution

- Backend and automation design with NestJS, Node.js, Python, and n8n.
- REST API, webhook, RPA, and payment gateway integrations.
- PostgreSQL transaction tracking and operational traceability.
- Dockerized services and AWS-based components.
- Technical planning and coordination for a four-person development team.

### Technology profile

`NestJS` · `Node.js` · `Python` · `n8n` · `PostgreSQL` · `REST APIs` · `Webhooks` · `RPA` · `Docker` · `AWS`

---

## Case Study 2: Environmental Monitoring and HVAC Automation

### Challenge

Distributed facilities require continuous temperature and humidity supervision in operationally sensitive areas. Manual checks provide limited coverage and make it difficult to react quickly or evaluate environmental and energy patterns.

### Solution

An IoT monitoring platform that captures thermohygrometer measurements at regular intervals, centralizes telemetry, produces alerts and reports, and supports automated HVAC control rules.

![Wireless thermohygrometer connected to telemetry dashboards and HVAC automation](docs/assets/environmental-monitoring-iot.jpg)

*Reconstructed and anonymized portfolio visual. Measurements and dashboard states are illustrative.*

### Architecture

```mermaid
flowchart TD
    A["Thermohygrometer sensors"] --> B["Edge controller"]
    B --> C["Telemetry API"]
    C --> D["Data and reporting"]
    C --> E["Alerts and HVAC rules"]
```

### Main capabilities

- Continuous temperature and humidity monitoring.
- Five-minute telemetry collection intervals.
- Multi-location device visibility and health status.
- Threshold, connectivity, and device-status alerts.
- Historical reports and operational traceability.
- Scheduled and condition-based HVAC automation.
- Safe behavior during connectivity or sensor failures.

### My contribution

- IoT architecture and component integration.
- Backend services for telemetry, alerts, device status, and reporting.
- Control rules based on schedules and environmental thresholds.
- Field implementation planning and technical documentation.
- Evaluation of operational and energy-efficiency opportunities.

### Technology profile

`IoT Sensors` · `Edge Computing` · `Embedded Controllers` · `Backend APIs` · `PostgreSQL` · `Cloud Services` · `Automation Rules`

---

## Case Study 3: Access Control Analytics with Natural-Language AI

### Challenge

Access-control platforms generate large volumes of event records. Operational teams often need technical database knowledge or manually built reports to answer simple questions about entries, exits, schedules, devices, and unusual activity.

### Solution

A conversational analytics layer that allows authorized users to ask operational questions in natural language and receive structured answers based on access-control records.

![Biometric access terminal connected to a mobile dashboard and controlled AI analytics](docs/assets/smart-access-control-ai.jpg)

*Reconstructed and anonymized portfolio visual. Identities and access events are fictional.*

### Architecture

```mermaid
flowchart TD
    A["Access devices"] --> B["Event ingestion service"]
    B --> C["Access records database"]
    C --> D["Authorized AI query service"]
    D --> E["Conversational dashboard"]
```

### Example questions

- How many access events were recorded today?
- Which time ranges had the highest entry volume?
- Which devices reported communication problems?
- Show access activity for an authorized date range.
- Summarize unusual operational patterns for review.

### Engineering controls

- Role-based access to queries and results.
- Read-only, validated database operations.
- Restricted query scope and parameterized filters.
- Audit trail for prompts, generated queries, and responses.
- Protection of identity and access-event information.
- Clear separation between AI-generated summaries and verified source records.

### Technology profile

`Python` · `NestJS` · `SQL/PostgreSQL` · `LLM APIs` · `REST APIs` · `Access Control Integration` · `Audit Logging`

---

## Core engineering strengths

| Area | Demonstrated experience |
| --- | --- |
| Backend | APIs, microservices, validation, integration services |
| Automation | n8n, RPA, webhooks, retries, stateful workflows |
| Data | PostgreSQL, telemetry, transactions, reconciliation, audit trails |
| Cloud | AWS Lambda, API Gateway, RDS, event-driven services |
| IoT | Sensors, edge controllers, alerts, device health, actuator integration |
| AI | Natural-language operational queries with controlled data access |
| Delivery | Technical planning, documentation, and coordination of a four-person team |

## Confidentiality and visual integrity

This repository contains architectural summaries and reconstructed portfolio visuals. It does **not** contain production code, real patient or employee data, biometric information, API credentials, functional QR codes, internal URLs, or customer-specific documentation. Visuals are explicitly labeled so they are not mistaken for production screenshots.

## Related public projects

- [Employability Platform](https://github.com/LuisDa87/Empleabilidad)
- [TechHelpDesk API](https://github.com/LuisDa87/prueba-nest)
- [Financial Operations Dashboard](https://github.com/LuisDa87/financiera)

## Contact

[GitHub](https://github.com/LuisDa87) · [LinkedIn](https://www.linkedin.com/in/luisdavidd/)
