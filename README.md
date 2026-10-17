# Carleon Europe BV – Accounts Receivable & Business Intelligence

## Project Overview

During Semester 3 of my ICT & Business studies at Fontys University of Applied Sciences, I worked on a group project for Carleon Europe BV, as part of the Quercis project, to improve its Accounts Receivable process through business analysis, data analytics, Business Intelligence, and automation.

The organisation relied heavily on manual invoice tracking, Excel exports, and communication between departments to monitor outstanding payments. This made it difficult to identify overdue invoices, prioritise customer follow-ups, and maintain an accurate overview of financial performance.

Our goal was to develop a Business Intelligence solution that would improve financial visibility, reduce manual work, and support data-driven decision-making for the Finance and Customer Service departments.

## From Business Problem to BI Solution

The project followed five main stages:

1. **Business Analysis:** Investigated the existing Accounts Receivable process (IST) through stakeholder interviews, BPMN modelling, bottleneck identification, and Fishbone Analysis.

2. **Process Improvement:** Designed an improved future-state process (SOLL), conducted a GAP analysis, defined business, user, and system requirements, and explored opportunities to improve invoice monitoring and communication.

3. **Data Modelling & KPI Development:** Developed a dimensional data model, identified relevant financial KPIs, and used Python and Pandas to validate financial data and calculations, including Days Sales Outstanding (DSO).

4. **Power BI Dashboard:** Developed an interactive dashboard through multiple iterations, implemented KPI calculations and visualisations, investigated data modelling issues, and improved the reporting solution based on stakeholder feedback.

5. **Automation & Implementation:** Designed and tested a Power Automate workflow for automated KPI notifications and prepared an implementation plan, Service Level Agreement (SLA), and cost estimation to evaluate the proposed solution's implementation.

## The Power BI Dashboard

The main technical deliverable was a two-page Power BI dashboard designed to support two different stakeholder groups.

### Page 1 – CFO: Financial Performance Overview

The CFO dashboard focuses on strategic financial monitoring and provides insights into:

- Total Overdue Amount
- Total Outstanding Amount
- Average Overdue Days
- Days Sales Outstanding (DSO)
- Financial performance and overdue trends

The dashboard supports financial performance analysis, receivables monitoring, and identifying potential liquidity risks.

### Page 2 – KCC: Accounts Receivable Prioritisation

The KCC dashboard focuses on operational collections management and helps identify customers requiring follow-up through:

- Customer priority rankings
- Overdue invoice information
- Outstanding customer balances
- Overdue severity and payment delays
- Operational KPIs for customer follow-up

Separating the two perspectives allowed the solution to address both strategic financial decision-making and day-to-day collections activities.

Throughout development, the dashboard was improved through KPI validation, data modelling adjustments, and stakeholder feedback.

## Tools & Technologies

| Area | Tools & Methods |
|---|---|
| Business Analysis | BPMN, IST/SOLL, GAP Analysis, Fishbone Analysis |
| Data Analytics | Python, Pandas, Data Validation |
| Business Intelligence | Power BI, DAX, KPI Reporting, Dashboard Design |
| Data Modelling | Dimensional Data Modelling, Table Relationships |
| Automation | Microsoft Power Automate |
| Project Management | Agile, Trello, Stakeholder Communication |

## My Contribution

My main responsibility was **independently developing the initial Power BI dashboard**, from investigating the required KPI calculations to designing the reporting pages and implementing the visualisations.

At the beginning of the development phase, I took the initiative to determine how the KPIs we had identified and presented to the client could be translated into a functional reporting solution. This involved researching DAX formulas, developing financial calculations, selecting suitable visualisations, and organising the information to meet stakeholder needs.

I created multiple dashboard drafts, continuously testing and refining the calculations, layouts, and visualisations. The development version included in this repository represents my most accurate and complete iteration before the final adjustments.

During the later stages, I collaborated with a teammate to investigate and establish relationships between columns from different tables, which were necessary for certain calculations and visualisations to work correctly.

After identifying the remaining issues, I asked my teammate to make the final adjustments, including replacing displayed customer IDs with customer names and improving the dashboard's colour scheme.

Beyond Power BI development, I also:

- Contributed to analysing the existing and future business processes (IST/SOLL).
- **Independently developed the project requirements**, translating business needs into business, user, and system requirements.
- Participated in project discussions, planning, and stakeholder communication.
- Contributed to identifying bottlenecks and exploring process improvement opportunities.

This project strengthened my ability to take initiative, solve technical problems independently, collaborate with others, and translate business requirements into practical technical solutions.

## Repository Structure

The repository is organised according to the main phases of the project.

| Folder | Contents |
|---|---|
| [01 – Business Analysis](01%20%E2%80%93%20Business%20Analysis) | IST process, stakeholder analysis, bottlenecks, Fishbone Analysis |
| [02 – Process Improvement](02%20%E2%80%93%20Process%20Improvement) | SOLL process, GAP analysis, requirements, process improvement |
| [03 – Data Modelling & KPIs](03%20%E2%80%93%20Data%20Modelling%20%26%20KPIs) | Dimensional model, KPI definitions, Python and Pandas validation |
| [04 – Power BI Dashboard](04%20%E2%80%93%20Power%20BI%20Dashboard) | My Power BI development, final dashboard, documentation and findings |
| [05 – Implementation & Automation](05%20%E2%80%93%20Implementation%20%26%20Automation) | Power Automate workflow, implementation plan, SLA, cost estimation |

Each folder contains the relevant project deliverables and a README explaining the activities, decisions, and outcomes of that phase.

## Project Outcome

The project resulted in a two-page Power BI dashboard that combines strategic financial monitoring with operational customer payment prioritisation.

The CFO dashboard provides insight into financial performance and overdue receivables, while the KCC dashboard supports customer follow-up and collections prioritisation.

We also demonstrated the potential of automated KPI monitoring through a successfully tested Power Automate workflow and prepared supporting documentation for potential implementation.

By combining business process analysis, data modelling, KPI development, Business Intelligence, and automation, the project demonstrated how technology can improve financial visibility and support more informed business decisions.

For me, the project was particularly valuable because it allowed me to combine **business analysis with hands-on technical development**, take ownership of a major deliverable, and gain experience translating real client requirements into a working Business Intelligence solution.
