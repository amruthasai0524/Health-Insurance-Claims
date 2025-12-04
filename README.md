🏥 Health Insurance Claims – Exploratory Data Analysis (EDA)

A data-driven investigation to uncover how lifestyle, demographics, and habits influence healthcare insurance charges. This project transforms raw insurance data into actionable insights that support smarter pricing, prevention strategies, and healthcare decision-making.

📌 Project Overview

Health insurance costs vary widely across individuals, yet the real drivers behind these variations are often unclear.
This EDA project analyzes 5,338 insurance records to identify the key factors influencing healthcare charges, focusing on:

Age

Sex

BMI (Body Mass Index)

Number of children

Smoker status

Region

Charges

The goal is to understand which factors matter most and how they contribute to cost variations.

📂 Dataset Details

Total Rows: 5,338

Columns: 7

Data Types: Mix of numerical + categorical

Source: Public health insurance dataset

✔ Data Cleaning Performed

No missing values found

Duplicate entries removed

Outliers handled using IQR & boxplot analysis

All categorical columns standardized

🔍 Exploratory Data Analysis
1️⃣ Univariate Analysis

Most customers fall into young to middle age groups

Many individuals show BMI > 30 → overweight/obese

Smoking population is small but has extremely high charges

Charges distribution is right-skewed (few people pay very high amounts)

2️⃣ Bivariate Analysis

Key relationships uncovered:

Smokers vs Non-Smokers: Smokers have drastically higher charges

Age vs Charges: Costs increase gradually with age

BMI vs Charges: Higher BMI → higher medical expenditure

Region & Gender: Minimal impact on charges

3️⃣ Multivariate Analysis

Highest charges observed among:

Older individuals

High BMI (overweight/obese)

Smokers

Number of children shows very little influence on total charges

⭐ Key Insights

Smoking is the strongest cost driver

Smokers consistently pay significantly more than non-smokers

BMI and lifestyle habits matter more than age

Obesity increases long-term healthcare spending

Demographics like region and gender have limited impact

Healthy habits = Lower insurance charges

Lifestyle choices outweigh location or gender differences

🎯 Conclusion

Health insurance costs are primarily shaped by personal lifestyle factors rather than demographics.
Smokers and obese individuals face the highest charges, making preventive lifestyle choices the most effective strategy for reducing healthcare costs.

🚀 Future Scope

Add medical history, diet, and physical activity data

Build predictive ML models for:

Charge prediction

Risk classification

Premium optimization

Create real-time dashboards for insurers

Scale analysis to multi-country datasets for global insights

👩‍💻 About Me

Amrutha Sai Yarragodala
Bachelor of Pharmacy graduate passionate about Data Science in Healthcare.
I use analytics to uncover meaningful patterns that improve medical and insurance decisions.

🔗 GitHub: https://github.com/amruthasai0524

🔗 LinkedIn: www.linkedin.com/in/amruthasaiyarragodala
