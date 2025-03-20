# Assignment-6-Agile-User-Stories-Backlog-and-Sprint-Planning-for-the-System-Objective

# AI-Driven Automated Database Recovery System

## Project Overview

This project involves developing an AI-powered database recovery system for hospitals in the Western Cape. The goal is to automate database recovery processes using machine learning and AI technologies, ensuring efficient and reliable database recovery in case of failures.

## Key Features
- AI-driven database failure prediction
- Automated data recovery from backups
- Real-time system health monitoring and notifications
- Ransomware attack detection and mitigation
- Compliance with data protection regulations (e.g., HIPAA, POPIA)

## Technologies
- AI & Machine Learning algorithms
- Real-time monitoring tools
- Cloud infrastructure (AWS, Docker, VMware)
- Secure backup and recovery mechanisms

## Milestones
- **Sprint 1**: Implement AI-based failure prediction and automated backup system.
- **Sprint 2**: Implement automated data recovery and anomaly detection.
- **Sprint 3**: Full integration and deployment, including compliance features.

## 2 User Stories Table

| **Story ID** | **User Story** | **Acceptance Criteria** | **Priority** |
|-------------|--------------|------------------------|------------|
| **US-001** | As a Database Administrator, I want the system to automatically create backups at predefined intervals so that I can ensure data is not lost due to failures. | Backups must be created at least once every 24 hours; success/failure logs must be generated. | High |
| **US-002** | As an IT Support Staff member, I want the system to predict potential database failures so that I can proactively address issues before they cause downtime. | The system must alert the IT team at least 24 hours before a predicted failure, with 95% accuracy. | High |
| **US-003** | As an IT Support Staff member, I want the system to automatically restore the database from the latest backup in case of failure so that I can minimize downtime and data loss. | Recovery must complete within 30 minutes (RTO), with no data loss exceeding 1 hour (RPO). | High |
| **US-004** | As a Security Officer, I want the system to monitor database activity and detect anomalies so that I can respond quickly to security threats or performance issues. | Alerts must be triggered within 5 minutes of detecting an anomaly, with logs capturing details. | High |
| **US-005** | As a Database Administrator, I want the ability to manually trigger or pause the recovery process so that I can intervene if needed during system failures. | IT staff must be able to initiate or pause recovery via a secure web interface within 10 minutes. | Medium |
| **US-006** | As a Security Officer, I want all backup and recovery processes to use encryption so that patient data remains confidential and secure. | All backup and recovery operations must use AES-256 encryption. | High |
| **US-007** | As a Hospital Manager, I want a dashboard displaying real-time database health metrics so that I can ensure system performance and availability. | The system must display storage utilization, query performance, and transaction logs in real-time. | Medium |
| **US-008** | As a Compliance Auditor, I want an audit trail of all backup and recovery activities so that I can verify compliance with data protection regulations. | Audit logs must be retained for at least 12 months and be accessible for reporting. | High |
| **US-009** | As a Compliance Auditor, I want the system to generate compliance reports so that I can ensure adherence to South Africa’s data protection laws. | Reports must include consent management, data retention policies, and compliance logs. | High |
| **US-010** | As an AI System, I want to update machine learning models periodically so that I can improve the accuracy of failure predictions and recovery strategies. | AI models must be updated at least once every 30 days, with a 95% success rate in predictions. | Medium |

## 3. Product Backlog: Prioritized and Justified

Backlog Justification:

Must-have stories: These stories represent core functionalities needed for system recovery, failure prediction, and monitoring. For instance, failure prediction (US-09) and automated backup (US-01) are essential for the database recovery system.

Should-have stories: While important, they can be deferred if necessary. For example, system scalability (US-12) is important for high transaction volumes but is not critical in the MVP.

Won’t-have stories: Stories such as mobile application (US-18) are out of scope for now, as they add complexity without contributing immediately to the core functionality of the database recovery system.

## 4. Sprint Plan: Goal, Selected Stories, and Tasks
Sprint Goal:
The goal for this sprint is to implement the AI-assisted failure prediction and backup scheduling features. These are critical to the system's core functionality, allowing automated alerts and responses for database failures.

Selected User Stories for Sprint 1:
US-01: AI-assisted troubleshooting for database recovery
US-02: Real-time notifications via email and SMS
US-09: AI-driven failure prediction

## 5. Reflection on Challenges:
As the sole stakeholder in this project, I encountered several challenges in prioritizing and estimating user stories, especially when trying to balance immediate needs with long-term system stability and flexibility.

Prioritization: One of the main struggles was determining the Must-have versus Should-have functionalities. Since this is an AI-driven system, the balance between performance and advanced AI features like failure prediction was tough to get right. While AI failure prediction is critical, it requires a significant amount of time and resources to implement properly. Thus, deciding what to build first—core, operational features like automated backups or AI-driven features—was a matter of ensuring the minimum viable product (MVP) worked as expected while leaving room for advanced functionalities in future sprints.

Estimation: Estimating effort for tasks related to AI models was particularly challenging. Estimating AI development is difficult because the time it takes to train models, handle data, and validate predictions is unpredictable. This made it hard to confidently break down user stories into manageable tasks with accurate hours.

Aligning Agile with Stakeholder Needs: As a single stakeholder, I had to wear multiple hats: user, project manager, and product owner. This lack of external stakeholder perspectives led to difficulty in deciding which user stories were most important for immediate release and which ones could be deferred. The process of dividing tasks between “urgent” AI-driven features and “nice-to-have” features like mobile access (which would be useful but not essential for the MVP) felt like it could easily shift depending on the outcome of initial testing and the flexibility of available resources.

These challenges made the initial phase of backlog grooming and sprint planning difficult, but also more insightful in terms of how prioritization can directly impact the MVP’s final usability and functionality.

## Conclusion
This Agile Planning Document outlines all aspects of planning, including the backlog, sprint goals, and reflection on the challenges of Agile methodology. The careful alignment between user stories, technical tasks, and stakeholder needs ensures the project stays on track while maintaining flexibility for future iterations and improvements.