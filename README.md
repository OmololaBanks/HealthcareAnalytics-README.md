# Social Determinants of Health (SDOH) Analytics – Risk Stratification & Health Outcomes

## Project Overview
This project delivers an interactive Social Determinants of Health (SDOH) analytics dashboard designed to explore how non-medical factors influence disease burden, hospital admissions, and preventive care utilization.
The solution integrates demographic, health outcome, and social factor datasets to identify structural risk patterns across income levels, housing stability, employment status, health literacy, transport access, and geography.
Designed around real-world public health and healthcare system challenges, the dashboard demonstrates end-to-end data modeling, DAX-based risk scoring, KPI design, and executive-level storytelling. It enables data-driven decision-making by highlighting high-risk populations and uncovering systemic disparities in healthcare utilization.

## Project Objectives
-	Analyze how social determinants influence disease distribution and hospital admissions
-	Identify high-risk population segments using a composite SDOH risk flag
-	Compare preventive care utilization across income, literacy, and housing groups
-	Examine readmission rates by chronic disease type
- Evaluate admission trends across age and income categories
-	Support targeted public health intervention strategies
-	Enable stakeholder-ready insights through risk-adjusted visual storytelling

## Data Sources
Primary Dataset (Integrated Model)
The project combines four siloed datasets into a unified healthcare analytics model:
- Demographics
    Age
    Gender
  	Ethnicity
- Region
    Urban/Rural
- Health Indicators
    Chronic_Disease
    Hospital_Admissions
  	Preventive_Care_Visits
- Social Determinants
    Income_Level
    Employment_Status
    Housing_Stability
    Transport_Access
    Health_Literacy
- Derived Attributes
-	Readmission Rate
-	Admission Rate
-	Composite Housing Risk Flag (High / Medium / Low)

## Data Preparation
- Merged demographic, regional, health, and social determinant datasets into a unified analytical model
- Engineered derived fields using DAX including:
-	Admission Rate measures
-	Readmission Rate calculations
-	Composite SDOH Risk Flag
-	Risk Scoring logic (0–3 structural vulnerability index)

## Key KPIs
-	Population Count
-	Average Age
-	Female % / Male %
-	Total Regions
-	Total Hospital Admissions
-	Total Preventive Care Visits
-	Admission Rate
-	Readmission Rate

## Key Insights
-	Preventive care utilization varies slightly across regions, with urban centers showing higher engagement
-	Admission burden does not perfectly align with preventive utilization across regions
-	Working-age adults (25–44) carry the highest disease burden
-	Moderate-income individuals show higher disease counts than low-income groups, challenging simple income-risk assumptions
-	Structural risk factors cluster in a large Medium-Risk population segment
-	Malaria records the highest readmission rate (28.2%)
-	Urban populations show slightly higher hospital utilization than rural populations
-	Preventive care visits are concentrated among higher-burden groups rather than directly reducing admissions outright
-	Health literacy appears inversely related to repeated preventive visits

## Dashboard Features
Three interconnected dashboards:
-	Community Health Overview
-	Health Outcome & Risk Analysis
-	Social Determinants of Health Dashboard
- Interactive filters (Gender, Ethnicity, Age Band)
- Risk segmentation (High / Medium / Low)
- Regional comparisons
- Disease-specific readmission analysis
- Admission trends by age and income
- Transport and housing impact analysis
- Executive-friendly layout optimized for public health stakeholders

## Business & Policy Value
-	Enables identification of structurally vulnerable populations
-	Supports targeted intervention instead of uniform healthcare allocation
-	Highlights systemic social risk clustering
-	Encourages risk-adjusted performance tracking
-	Demonstrates how SDOH factors influence healthcare utilization patterns
-	Provides a foundation for predictive risk modeling and resource optimization

## Tools Used
-	Power BI – Data modeling, DAX calculations, dashboard development
-	DAX – Risk scoring, rate calculations, composite segmentation logic
-	Excel / Data Preparation Tools – Initial cleaning and dataset structuring
## Future Improvements
-	Separate preventive visits into routine prevention vs chronic follow-up visits
-	Introduce longitudinal tracking to measure intervention impact over time
-	Build predictive risk scoring using regression or machine learning
-	Add cost modeling to estimate financial burden by risk group
	Integrate real-world public health datasets for enhanced realism
