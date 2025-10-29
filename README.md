# Project 1 - Clinical Trial Patient Recruitment and Adherence Monitoring

This project delivers an enterprise-level data analytics solution designed to address critical challenges in clinical trial management: patient recruitment delays and complex adherence monitoring. Pharmaceutical companies and research organizations often face immense costs and setbacks due to these issues.

## Problem Statement

Clinical trials frequently suffer from delays caused by inefficient patient recruitment processes. Furthermore, manually tracking patient adherence to trial protocols across multiple sites is prone to errors and risks data integrity. These problems lead to increased costs, extended timelines, and potential compromise of study results.

## Use Case

This solution provides a **central command center** for trial managers, enabling them to monitor recruitment funnels and patient adherence in real-time. By analyzing data from Electronic Data Capture (EDC) and Electronic Medical Record (EMR) systems, the system identifies recruitment bottlenecks at specific sites, forecasts enrollment completion dates, and proactively flags patients at risk of non-adherence or dropout.

## Key Modules

  * **Multi-Site Data Integration Pipeline:** A robust pipeline designed to ingest anonymized patient data from various EDC systems (e.g., Medidata Rave, Veeva) and EMR systems.
  * **Patient Recruitment Funnel Visualization:** Interactive visualizations that track patients through the entire recruitment funnel, from initial screening to enrollment and randomization. This helps identify where patients are dropping off.
  * **Site Performance Leaderboard:** A dashboard that compares the performance of different clinical trial sites based on key metrics such as enrollment velocity, screen failure rates, and data quality scores.
  * **Patient Adherence Dashboard:** A dedicated dashboard for monitoring patient compliance with trial protocols, including visit completion rates and medication adherence tracking (e.g., from e-diary submissions).
  * **Dropout Risk Prediction Model:** An analytical model that identifies patients at risk of non-adherence or early dropout, utilizing factors like missed visits, demographic data, and other relevant trial parameters.

## Technologies Used

  * **Data Sources:** CSV/Excel exports from EDC systems (e.g., Medidata Rave, Veeva), SQL databases.
  * **ETL & Modeling:** Power Query (M Language) for data extraction, transformation, and loading, and DAX for complex calculations and data modeling within Power BI.
  * **Visualization Platform:** Microsoft Power BI Desktop for report development and Power BI Service for deployment and interactive dashboards.
  * **Analytics Concepts:** Funnel analysis, Key Performance Indicator (KPI) tracking, and risk scoring methodologies.

## Benefits

  * **Reduced Trial Costs and Delays:** Proactive identification of recruitment bottlenecks and at-risk patients helps streamline operations.
  * **Improved Data Integrity:** Automated data integration and adherence monitoring reduce manual errors.
  * **Enhanced Decision-Making:** Real-time insights empower trial managers to make data-driven decisions.
  * **Better Patient Outcomes:** Early identification of adherence issues allows for timely interventions.
  * **Optimized Resource Allocation:** Understanding site performance helps in allocating resources more effectively.
