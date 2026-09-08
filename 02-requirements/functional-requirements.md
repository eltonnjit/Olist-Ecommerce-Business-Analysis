# Functional Requirements

## Overview

The following functional requirements define the capabilities the analytical solution must provide to satisfy the project's business requirements.

These requirements were developed for this independent portfolio case study and do not represent official requirements provided by Olist.

## Functional Requirements

### FR-001 — Delivery Status Classification
The solution shall classify completed orders as On-Time or Late by comparing the actual delivery date with the estimated delivery date.

**Supports:** BR-001, BR-002

### FR-002 — Delivery Performance KPIs
The solution shall calculate and display key delivery metrics, including:
- Total completed orders
- Total on-time deliveries
- Total late deliveries
- On-time delivery rate
- Late-delivery rate

**Supports:** BR-001, BR-009

### FR-003 — Delay Duration
The solution shall calculate the number of days between the estimated delivery date and actual delivery date for late orders.

**Supports:** BR-002

### FR-004 — Time-Based Analysis
The solution shall allow delivery performance to be analyzed across available time periods to identify trends in late-delivery rates.

**Supports:** BR-003

### FR-005 — Geographic Analysis
The solution shall calculate and compare delivery performance across available customer and seller geographic locations.

**Supports:** BR-004

### FR-006 — Seller Performance Analysis
The solution shall calculate delivery metrics by seller to identify sellers associated with higher late-delivery rates.

**Supports:** BR-005

### FR-007 — Customer Satisfaction Analysis
The solution shall compare customer review scores between on-time and late deliveries.

**Supports:** BR-006

### FR-008 — Freight and Order Analysis
The solution shall support analysis of available freight and order characteristics to identify patterns associated with delivery performance.

**Supports:** BR-007

### FR-009 — Interactive Filtering
The Power BI dashboard shall allow users to filter available performance metrics by relevant dimensions such as:
- Time period
- Geographic location
- Seller

**Supports:** BR-003, BR-004, BR-005, BR-009

### FR-010 — Performance Dashboard
The solution shall provide an interactive Power BI dashboard that presents delivery performance, customer satisfaction, and related analytical findings.

**Supports:** BR-009

### FR-011 — Data Validation
The analytical workflow shall validate relevant source data for missing values, duplicates, invalid dates, and other data-quality issues before KPI calculations are performed.

**Supports:** BR-009

### FR-012 — Business Findings
The solution shall produce documented findings identifying major delivery-performance patterns and potential areas for process improvement.

**Supports:** BR-008, BR-010
