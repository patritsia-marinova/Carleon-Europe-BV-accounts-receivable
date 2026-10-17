# 03 – Data Modelling & KPIs

## Overview

This phase of the Quercis project focused on preparing and validating financial data to support accurate Accounts Receivable reporting for Carleon Europe BV.

As a team, we developed a dimensional data model, defined financial KPIs, and investigated data quality issues to ensure the Power BI dashboard provided reliable information for decision-making.

## Data Analysis Activities

### 1. [Dimensional Data Model](https://github.com/patritsia-marinova/Carleon-Europe-BV-accounts-receivable/blob/main/03%20%E2%80%93%20Data%20Modelling%20%26%20KPIs/Dimentional%20Data%20Model.png)

We developed a dimensional data model to structure invoice, customer, payment, and date information for financial reporting.

The model was refined throughout the project based on stakeholder feedback and improvements to the KPI calculations, particularly Days Sales Outstanding (DSO).

### 2. [KPI Development](https://github.com/patritsia-marinova/Carleon-Europe-BV-accounts-receivable/blob/main/03%20%E2%80%93%20Data%20Modelling%20%26%20KPIs/Carleon%20BV%20KPI's%20KSF's.pdf)

We defined financial performance indicators to monitor overdue payments, outstanding balances, and customer payment behaviour.

These included Total Overdue Amount, Total Outstanding Amount, Average Overdue Days, Overdue Rate, and DSO. The KPIs helped translate business requirements into measurable financial insights.

### 3. [Data Validation – Python & Pandas](https://github.com/patritsia-marinova/Carleon-Europe-BV-accounts-receivable/blob/main/03%20%E2%80%93%20Data%20Modelling%20%26%20KPIs/Carleon%20BV%20pandas%20validation.ipynb)

Using Python and Pandas, we analysed overdue invoices, debtor balances, payment behaviour, and financial calculations.

During validation, we discovered that duplicate invoice records could inflate DSO results. By reviewing the calculations at invoice level rather than transaction level, we improved the reliability of the reporting solution.

## Outcome

Our analysis highlighted how **duplicate records, inconsistent data, and incorrect calculation levels can produce misleading financial KPIs**.

By refining the dimensional model and validating the calculations, we established a more reliable foundation for the Power BI dashboard and improved our understanding of how data quality affects business decisions.
