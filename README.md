# Operations SLA & Ticket Aging Dashboard (Power BI)

## Overview
This repository contains a **Power BI dashboard** designed to monitor **SLA compliance, ticket aging, backlog risk, and agent performance** in an operations / support environment.

The dashboard is built from an **operations manager’s perspective**, focusing on **risk identification, workload pressure, and SLA accountability** rather than decorative reporting.

---

## Business Context
Operations and support teams require a quick, reliable view to answer:

- How many tickets are currently open?
- Which tickets are overdue beyond SLA?
- Where is backlog aging increasing?
- Which agents or departments are contributing to SLA breaches?
- Where is immediate operational intervention required?

This dashboard provides a **single-page, executive-ready view** to support these decisions.

---

## Key KPIs
- Total Tickets  
- Open Tickets  
- Overdue Open Tickets (SLA-based)  
- SLA Compliance %  
- SLA Breach %  
- Aged Backlog (8+ Days)

All KPIs are built using **validated DAX measures** and cross-checked against base ticket counts to ensure model reliability.

---

## Analysis Covered
- Ticket aging distribution (recent vs overdue)
- SLA compliance by aging bucket
- High-priority aged tickets by department
- Agent-wise workload and SLA breach analysis
- SLA performance comparison across agents

---

## Data Model
- **Fact Table:** Tickets  
- **Dimension Tables:** Date, Agent, Department, Priority  

The model follows **star schema principles** with clean one-to-many relationships and controlled filter flow.

---

## Tools Used
- Power BI Desktop  
- DAX (CALCULATE, FILTER, DIVIDE, time-based logic)  
- Microsoft Excel (source dataset)
