# 🔍 Cozy Brand Health Analytics
An end-to-end analytics project that combines Python and Power BI to track brand health for Cozy, a Vietnamese RTD tea brand, benchmarked against 6 master brands in the Vietnam ready-to-drink tea category: C2, Không Độ, Olong Tea Plus, Boncha, Dr. Thanh, and a grouped "Other" segment (TH True Tea, Tea Go, Vinamilk Happy Milktea, Seventy, VietFuji, Jokky, Búp non 365). 

This project takes a messy, wide-format questionnaire export and turns it into a clean star schema, then builds a 4-page interactive Power BI report with actionable, insight-driven titles rather than plain chart descriptions.

---

##  📂 Dataset
### Data Source
The original dataset is derived from a brand health survey conducted to measure consumers' awareness, consideration, usage, and perceptions of beverage brands.

The raw survey data was provided in a wide-format structure, containing survey responses across a large number of questions and variables.
### Data Transformation

The raw survey dataset was transformed using Python (pandas) into a set of clean, business-oriented tables.
The transformation process involved:

- Reviewing the survey questionnaire and variable definitions
- Mapping survey questions to relevant business concepts (funnel, imagery, barriers, occasion, channel, switching)
- Restructuring the wide-format survey data into long-format analytical tables
- Separating respondent, brand, and survey-related information into distinct tables
- Standardizing common key columns (Serial number, Wave, Master Brand) across all tables so they could be connected later
- Loading the resulting tables into Power BI and building relationships between them in the data model\
### Data pipeline

