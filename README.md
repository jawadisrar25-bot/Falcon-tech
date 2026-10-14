# Falcon Tech — OHSS Digital Management System

A complete 250-screen front-end OHSS management platform organized around Falcon Tech's enterprise requirements. All styles, scripts, and screen inventory are included locally. No installation or server required.

## Overview

Falcon Tech OHSS is a professional browser-runnable application spanning 250 navigable screens across 19 OHSS modules. It implements complete record management workflows including create, edit, delete, approval flows, and status tracking — all within the browser using localStorage.

## Accessibility

All 250 screens are accessible via hash navigation (`#/screen/1` through `#/screen/250`). The left sidebar provides expandable navigation groups with search functionality. Global search (Ctrl/⌘+K) filters screens by title and group. Each screen displays relevant content based on its module type.

## Screen Modules (19 total)

1. **Core Dashboards & Workspace** — Executive Dashboard, OHSS Operations Dashboard, Personal Workspace, My Tasks, My Approvals, Notifications Center, Global Search, Project Portfolio Overview, Project Details, Organization Overview, Activity Timeline, My Profile
2. **Occupational Health & Clinic** — Occupational Health Dashboard, Employee Health Registry, Employee Health Profile, Electronic Medical Records, Medical Visit Details, Register Medical Visit, Medical Surveillance Dashboard, Medical Surveillance Programs, Pre-Placement Assessments, Periodic Health Assessments, Return-to-Work Assessments, Exit Medical Assessments
3. **Industrial Hygiene** — Industrial Hygiene Dashboard, Exposure Monitoring Registry, Worker Exposure Profile, Similar Exposure Groups, SEG Details, Exposure Sampling Plans, Sampling Results, Occupational Exposure Limits, Exposure Exceedance Alerts, Industrial Hygiene Risk Assessments, Noise Monitoring, Silica & Dust Monitoring, Bayesian Sampling Analysis, Industrial Hygiene Reports
4. **Construction Safety** — Construction Safety Dashboard, Safety Observation Registry, Submit Safety Observation, Safety Observation Details, Site Inspections, Inspection Checklist, Lifting Operations Management, Scaffolding Safety Management, Traffic Safety Dashboard, Road Closure Management, Road Closure Map, Safety Escalation Items, Ad-Hoc Requests & Meetings, Construction Safety KPI Dashboard
5. **Security Management** — Security Dashboard, Security Incidents, Report Security Incident, Security Incident Details, Daily Security Assignments, Security Patrol Management, Patrol Tracking Map, Access Control Records, Visitor Management, Traffic Violations, Security Compliance Reports, Security System Integration Status
6. **Incident Management** — Incident Dashboard, Incident Register, Report New Incident, Incident Details, Incident Investigation, Root Cause Analysis, Near Miss Reports, Anonymous Safety Reporting, Corrective Action Management, Preventive Actions, Overdue Actions, Incident Escalations, Lessons Learned, Incident Analytics
7. **Risk & Permit-to-Work** — Risk Management Dashboard, Enterprise Risk Register, Create Risk Assessment, Risk Assessment Details, Risk Matrix, Hazard Identification, Control of Work Dashboard, Permit-to-Work Registry, New Permit Request, Permit Details, Permit Approval Workflow, Active Permits Map, High-Risk Work Monitoring, Permit Closure, Management of Change, Risk & Permit Analytics
8. **Contractor Safety Management** — Contractor Dashboard, Contractor Directory, Register Contractor, Contractor Profile, Contractor Employees, Contractor Project Assignments, Authorized Work Activities, Contractor Compliance, Contractor Incidents, Contractor Inspections, Contractor Audit History, Contractor Risk Register, Contractor Corrective Actions, Contractor Performance Scorecard
9. **Emergency Management** — Emergency Management Dashboard, Emergency Preparedness Plans, Emergency Plan Details, Emergency Drill Calendar, Schedule Emergency Drill, Emergency Drill Results, Emergency Response Procedures, Emergency Event Log, Emergency Response Tasks, Crisis Communications, Emergency Corrective Actions, Emergency Preparedness Reports
10. **Business Continuity Management** — Business Continuity Dashboard, BCM Governance, Business Impact Analysis Registry, Create Business Impact Analysis, BIA Details, Business Continuity Plans, Continuity Plan Details, Dependency Assessments, Continuity Risk Register, Continuity Strategies, Crisis Activation Dashboard, Crisis Communication Workflows, BCM Exercises & Testing, BCM Compliance Reports
11. **Compliance & Governance** — Compliance Dashboard, Compliance Register, Legal & Regulatory Register, Policy Management, Procedure Management, Policy Approval Workflow, Document Version Control, Expiring Policies, Compliance Assessments, Site Compliance Dashboard, Contractor Compliance Benchmarking, Management Review Meetings, Compliance Alerts, Governance Reports
12. **Audits & Inspections** — Audit Dashboard, Audit Plan, Audit Schedule Calendar, Create Audit, Audit Execution Workspace, Digital Audit Checklist, Audit Findings, Non-Conformance Register, Inspection Register, Compliance Standards Mapping, Audit Analytics & Scorecards
13. **Training & Development** — Training Dashboard, Training Calendar, Course Code, Training Type, Location, Attendance, Course Date, Training Records
14. **Environmental Management** — Environmental Dashboard, Environmental Category, Site, Measurement, Limit, Period, Environmental Monitoring Records
15. **Document & Workflow Management** — Dashboard, Document Version Control, Expiring Policies, Compliance Assessments, Site Compliance Dashboard, Contractor Compliance Benchmarking, Management Review Meetings, Compliance Alerts, Governance Reports
16. **Reporting & Business Intelligence** — Dashboard, KPIs, Charts, Calendars, Maps, Workflow Kanbans, Tables
17. **System Administration** — Configuration options, Workflow stages, Save settings, Add stage
18. **Integrations & Data Management** — System ID, Interface, Direction, Sync Frequency, Last Check
19. **Platform Operations & Support** — Platform Operations and Support screens with support ticket management

## Professional Features

Falcon Tech OHSS includes complete front-end OHSS management capabilities:

- **Record management**: Create, edit, delete records with full field validation
- **Approval workflows**: Open → Under Review → Approved → Closed progression
- **Status updates**: Incident management, corrective actions, preventive actions
- **CSV export**: Export all records to CSV format
- **Date selection**: Calendar navigation and date picking
- **KPI dashboards**: Charts, metrics, performance trends
- **Risk matrices**: Likelihood × Severity assessment
- **Permit-to-work**: Permit requests, approvals, hazards, work locations
- **Contractor management**: Directory, profiles, compliance, incidents
- **Emergency management**: Drill calendars, response procedures, corrective actions
- **Compliance & governance**: Policies, assessments, benchmarking
- **Audit & inspections**: Checklists, findings, corrective actions
- **Training & development**: Courses, schedules, attendance, certifications
- **Environmental management**: Measurements, limits, monitoring
- **Document management**: Version control, approvals, revisions
- **Responsive design**: Works on desktop, laptop, and tablet

## Design Philosophy

Built as a professional enterprise OHSS management platform with:
- Soft white and very light grey backgrounds
- Subtle teal and blue accents
- Clean, modern typography using Inter/DM Sans
- Well-aligned sidebar, header, cards, tables, and forms
- Consistent spacing and padding throughout
- Soft borders and subtle shadows
- Medium rounded corners
- Professional icon styling
- No gradients or bright colors
- No oversized headings or buttons
- No crowded interfaces
- No excessive empty space
- Smooth but minimal transitions

## Technical Boundaries

- Browser-only front-end application
- Data stored in browser's localStorage
- No backend server, medical data storage, real authentication, or external enterprise integration
- No live GPS or geolocation services
- Illustrative professional data (no fictional personal names)
- All 250 screens function independently with hash-based routing

## Run the Application

Open `index.html` in Chrome, Edge, or Safari. No installation required.

Or run a local web server:
```
python -m http.server 8080
```
Then visit: `http://localhost:8080`