# 🔍 Cozy Brand Health Analytics
An end-to-end analytics project that combines Python and Power BI to track brand health for Cozy, a Vietnamese RTD tea brand, benchmarked against 6 master brands in the Vietnam ready-to-drink tea category: C2, Không Độ, Olong Tea Plus, Boncha, Dr. Thanh, and a grouped "Other" segment (TH True Tea, Tea Go, Vinamilk Happy Milktea, Seventy, VietFuji, Jokky, Búp non 365). 

This project takes a messy, wide-format questionnaire export and turns it into a clean star schema, then builds a 4-page interactive Power BI report with actionable, insight-driven titles rather than plain chart descriptions.

---
## 📊 Project Snapshot
|                     |                                                               |
| ------------------- | --------------------------------------------------------------|
| **Type**            | End-to-end brand health analytics                             |
| **Category**        | Vietnam Ready-to-Drink (RTD) Tea                              |
| **Focal brand**     | Cozy                                                          |
| **Sample**          | 2,600 respondents · 2 waves (2024 n=1,300 / 2025 n=1,300)     |
| **Tools**           | Python · Power BI                                             |
| **Data model**      | Star schema - 2 dimension tables, 6 fact tables               |

---

## 🎯 Business Context
Cozy's awareness grew +4.8pp YoY (94.2% in 2025), yet BUMO sits at just 9.3%, ~20pp behind the category leader. This project investigates where that gap comes from and what to do about it. 

This project aims to answer:

- Where does Cozy lose the most consumers along the funnel, and is it getting better or worse?
- Why do consumers who already know Cozy still not choose it — product or brand perception? 
- Does Cozy reach the right channels and occasions? 
- Is Cozy's competitive position improving or declining, and against whom?

--- 
## 💡 Key Insights
### 📉 Funnel Performance
- Cozy trails across the entire funnel, with the sharpest drop between Awareness and Spontaneous Recall.
- Cozy's BUMO edged up just 1.0pp to 9%, still trailing the category leader by ~20pp.
- Cozy reaches 24% fewer channels per person than category leaders.

## 🎨 Imagery & Barriers
- Flavor is the #1 reason people say no to Cozy.
- Dislike of flavor and limited variety remain Cozy's key barriers, consistent across waves.
- Refreshment imagery is Cozy's growth driver - up 4pp to 55% in 2025, the only attribute trending upward.
- Cozy lags top competitors by 23–33pp across most attributes, relying heavily on "reliable brand" (56%) to close the gap.

## 🛒 Channel & Occasion
- C2 purchases are concentrated in Grocery Shop (68% of C2 buyers); Cozy is more evenly spread across channels (60% via Grocery Shop, but stronger relative presence in Coffee shops and Supermarkets).
- Break-time is the leading occasion for both brands; Cozy and C2 show broadly similar occasion patterns, with C2 slightly ahead on "consumed outside" occasions.
## 🔄 Switching Dynamics
- Net switching is positive for Cozy, but driven by two opposite dynamics.
- Cozy gains the most switchers from Olong Tea Plus.
- Cozy loses the most switchers to C2.
- This points to two distinct strategic needs: offense against Tea Plus, defense against C2.


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
- Loading the resulting tables into Power BI and building relationships between them in the data model


## 📈 Dashboard
<img width="509" height="309" alt="image" src="https://github.com/user-attachments/assets/98124f84-bac9-4ac4-ac27-eb10adb9a2af" />
<img width="507" height="309" alt="image" src="https://github.com/user-attachments/assets/3346a975-4c36-47dd-ba65-e064ff7d82ce" />
<img width="510" height="310" alt="image" src="https://github.com/user-attachments/assets/0db4ee0b-4b02-4df2-99db-0ad0d75f5085" />
<img width="508" height="308" alt="image" src="https://github.com/user-attachments/assets/1042b51b-b581-4084-a4a0-e26d668ae8dd" />



