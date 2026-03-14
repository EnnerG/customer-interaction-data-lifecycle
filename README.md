# Customer Interaction Data Stream — Data Lifecycle Map

This project provides a clear, senior‑level mapping of the data lifecycle for a customer interaction data stream. It demonstrates understanding of data governance, quality, ingestion, transformation, and consumption.

---

# 🔄 Data Lifecycle Overview

## 1. Ingestion
- Sources: CRM, Support Ticketing, Billing System  
- Method: Scheduled batch ingestion (daily)  
- Validation: Schema check + row count comparison  

## 2. Storage
- **Raw Zone:** Immutable, timestamped files  
- **Staging Zone:** Cleaned, standardized tables  
- **Curated Zone:** Business‑ready customer interaction model  

## 3. Transformation
- Deduplication using customer ID  
- Standardization of timestamps  
- Mapping lifecycle events to unified taxonomy  
- PII masking applied  

## 4. Governance
- Data dictionary maintained in Confluence  
- RBAC access control  
- Audit logs retained for 90 days  
- Data quality checks: completeness, freshness, accuracy  

## 5. Consumption
- BI dashboards (Power BI, Tableau)  
- API endpoints for product teams  
- SQL access for analysts  

## 6. Optimization Loop
- Monitor pipeline failures  
- Track data freshness SLA  
- Collect user feedback monthly  
- Add new sources as needed  

---

## 📎 Purpose of This Project
This lifecycle map demonstrates:
- Strong understanding of data lifecycle  
- Governance and quality awareness  
- Ability to communicate complex systems clearly  
- Alignment with data engineering and analytics teams  

