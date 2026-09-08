# Acceptance Criteria

## Overview

The following acceptance criteria define the conditions that must be met for the project's key user stories and functional requirements to be considered successfully implemented.

These criteria were created for this independent portfolio case study and do not represent official requirements provided by Olist.

---

## AC-001 — Delivery Status Classification

**Related User Story:** US-002  
**Related Functional Requirement:** FR-001

### Given
A completed order contains both an estimated delivery date and an actual delivery date.

### When
The delivery status is calculated.

### Then
- The order shall be classified as **On-Time** when the actual delivery date is on or before the estimated delivery date.
- The order shall be classified as **Late** when the actual delivery date is after the estimated delivery date.

---

## AC-002 — Delivery Performance KPIs

**Related User Story:** US-001  
**Related Functional Requirement:** FR-002

### Given
Validated completed-order data is available.

### When
The user views the delivery performance dashboard.

### Then
The dashboard shall display:
- Total completed orders
- Total on-time deliveries
- Total late deliveries
- On-time delivery rate
- Late-delivery rate

---

## AC-003 — Delay Duration

**Related User Story:** US-003  
**Related Functional Requirement:** FR-003

### Given
An order is classified as Late.

### When
Delay duration is calculated.

### Then
The solution shall display the number of days between the estimated delivery date and the actual delivery date.

---

## AC-004 — Time-Based Analysis

**Related User Story:** US-004  
**Related Functional Requirement:** FR-004

### Given
Order and delivery dates are available.

### When
The user analyzes delivery performance over time.

### Then
The solution shall allow delivery KPIs to be compared across available time periods.

---

## AC-005 — Geographic Analysis

**Related User Story:** US-005  
**Related Functional Requirement:** FR-005

### Given
Geographic information is available for relevant orders.

### When
The user analyzes delivery performance by geography.

### Then
The solution shall display comparable delivery metrics across available geographic areas.

---

## AC-006 — Seller Performance Analysis

**Related User Story:** US-006  
**Related Functional Requirement:** FR-006

### Given
Orders can be associated with sellers.

### When
The user analyzes seller delivery performance.

### Then
The solution shall calculate delivery metrics by seller and allow identification of sellers with higher late-delivery rates.

---

## AC-007 — Customer Satisfaction Analysis

**Related User Story:** US-007  
**Related Functional Requirement:** FR-007

### Given
Completed orders can be associated with customer review scores.

### When
The user analyzes customer satisfaction.

### Then
The solution shall compare review scores between On-Time and Late deliveries.

---

## AC-008 — Freight and Order Analysis

**Related User Story:** US-008  
**Related Functional Requirement:** FR-008

### Given
Relevant freight and order characteristics are available.

### When
The user analyzes delivery performance.

### Then
The solution shall allow those characteristics to be compared against delivery outcomes.

---

## AC-009 — Interactive Filtering

**Related User Story:** US-009  
**Related Functional Requirement:** FR-009

### Given
The Power BI dashboard is open.

### When
The user applies an available filter.

### Then
Relevant KPIs and visualizations shall update to reflect the selected filter.

---

## AC-010 — Interactive Dashboard

**Related User Story:** US-010  
**Related Functional Requirement:** FR-010

### Given
Validated analytical data is available.

### When
The user opens the Power BI dashboard.

### Then
The dashboard shall present delivery-performance and customer-satisfaction metrics in a clear and usable format.

---

## AC-011 — Data Validation

**Related User Story:** US-011  
**Related Functional Requirement:** FR-011

### Given
Source data has been loaded for analysis.

### When
Data validation is performed.

### Then
The workflow shall check for:
- Missing values
- Duplicate records
- Invalid dates
- Inconsistent date sequences
- Other relevant data-quality issues

Any identified issues shall be documented before KPI calculations are finalized.

---

## AC-012 — Business Findings and Recommendations

**Related User Story:** US-012  
**Related Functional Requirement:** FR-012

### Given
The analytical work has been completed.

### When
The final findings are documented.

### Then
The project shall include:
- Major delivery-performance findings
- Relevant customer-satisfaction findings
- Identified areas for further investigation
- Data-driven business recommendations
- Suggested KPIs for ongoing monitoring
