**Name:** Umukamisha Celine  
**ID:** 27400 
## Hospital Appointment Optimization System



---

##  BPMN Diagram

![Hospital Appointment Optimization System - BPMN Diagram](Screenshots/Phase&11.png)

*Business Process Flow showing the complete appointment scheduling workflow across six swimlanes*

---

##  Scope Definition

**Business Process:** Hospital appointment scheduling and patient management workflow from booking to medical record creation.

**MIS Relevance:** Healthcare Management Information System for resource optimization, patient flow management, and regulatory compliance through automated processes and audit trails.

**Objectives:**
- Eliminate double-booking through real-time validation
- Reduce wait times
- Automate restriction checks (holidays/weekends)
- Maintain audit trails
- Integrate all hospital departments

**Expected Outcomes:** 30% reduction in scheduling errors, improved patient satisfaction, complete activity traceability.

---

##  Key Entities & Roles

| Entity | Role |
|--------|------|
| **Patient** | Initiates appointment requests, receives confirmations |
| **Receptionist** | Processes requests, queries database availability, suggests alternatives, confirms bookings |
| **System** | Validates schedules, checks holiday/restriction compliance, creates appointments, logs all activities |
| **Doctor** | Provides medical consultations |
| **Billing** | Generates bills, processes payments |
| **Medical Records** | Creates and maintains patient records |

---

##  Swimlane Structure

Six distinct swimlanes separate human actors (Patient, Receptionist, Doctor) from automated processes (System) and supporting departments (Billing, Medical Records). Clear handoff points shown where responsibility transfers between actors, ensuring accountability at each stage.

---

##  UML/BPMN Compliance

- **Start/End Events:** Green circles marking process boundaries
- **Process Activities:** Blue rounded rectangles for human tasks, purple for system automation
- **Decision Points:** Orange diamonds with YES/NO branches for conditional logic
- **Data Flow:** Black arrows showing sequential progression and dependencies
- **Logical Flow:** Clear start-to-end progression with proper branching for unavailable slots

---

##  MIS Functions

**Real-time Operations:**
- Instant schedule validation
- Automated restriction enforcement

**Data Integration:**
- Cross-department coordination (reception, doctors, billing, records)

**Compliance:**
- Automated holiday/weekend blocking per Phase VII requirements

**Audit & Security:**
- Complete activity logging for accountability and compliance

---

##  Analytics Opportunities

### Operational Intelligence
- Appointment volume trends
- Peak booking times
- Doctor utilization rates
- No-show patterns
- Average wait times

### Strategic Insights
- Resource allocation optimization
- Revenue per appointment type
- Seasonal demand forecasting
- Capacity planning

### Decision Support
- Identify bottlenecks
- Optimize staffing schedules
- Improve patient experience through data-driven decisions

---

##  Organizational Impact

This MIS transforms appointment management from manual, error-prone processes to automated, traceable workflows. It reduces administrative burden, improves resource utilization, enhances patient satisfaction, and provides hospital management with real-time operational visibility for strategic decision-making.

---


**Course:** Database Development with PL/SQL (INSY 8311)  
**Institution:** Adventist University of Central Africa (AUCA)  
**Lecturer:** Eric Maniraguha
