# End-to-End-Banking-Project-in-Databricks
End-to-end banking data engineering project in Databricks covering data ingestion, transformation, and analytics using PySpark, Delta Lake, and SQL. Processes customer, transaction, and loan data to support risk analysis, monitoring, business intelligence reporting and operational insights.

## Background
* VirtualBank generates large volume of data from core banking systems, payment gatewayys, and external credit bureaus.
* Data is stored across multiple platforms and formats, making unified analytics difficult.
* Business teams require quickinsights into customer activity, risk, and branch performance.

## Problem
* Banking data exists in multiple disconnected sources, creating data silos.
* Manual pipelines make data processing slow, complex, and hard to scale.
* Business users lack self-service anaytics for operational and risk insights.

## Solution
+ Build a metadata-driven framework on Databricks using Medallion Architecture (Bronze, Silver, and Gold).
+ Integrate SQL Server and Cloud storage data sources into a unified analytics platform.
+ Create interactive Dashboards and Genie AI interfacefor business users to query data.

## VIRTUALBANK Architecture

![VB_Architecture](https://github.com/Josiahgare/End-to-End-Banking-Project-in-Databricks/blob/a4c01d22c7d798eb2be0487d9f83d70cfc25edf9/docs/VIRTUALBANK%20Architecture.drawio.svg)
