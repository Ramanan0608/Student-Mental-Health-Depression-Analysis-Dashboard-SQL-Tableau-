****Student Mental Health & Depression Analysis Dashboard (SQL & Tableau)
Dashboard Link: https://prod-in-a.online.tableau.com/t/ramanankkl-41602ffee8/views/StudentCountAnalysis/StudentCountAnalysis*****

The goal of this project is to analyze student mental health indicators such as academic pressure, sleep duration, dietary habits, financial stress, and depression levels. By visualizing these factors, institutions can understand risk patterns, identify high-impact stressors, and take steps to support student well-being.

Steps Followed
Step 1 — Data Cleaning Using SQL

Imported raw student dataset containing columns such as Gender, Age, Academic Pressure, Sleep Duration, Dietary Habits, Study Satisfaction, Financial Stress, Study Hours, Family History of Mental Illness, and Depression.

Cleaned data by removing duplicates, handling missing values, correcting inconsistent categories, and generating new calculated fields for better segmentation.

Standardized data types (numeric, categorical, boolean) and validated value ranges.

Step 2 — Data Preparation

Exported the cleaned SQL output and connected it to Tableau for visualization.

Created hierarchy fields, grouped categorical values, and applied bins for Age, Academic Pressure, and Sleep Duration.

Designed calculated fields to categorize depression and identify high-risk groups.

Step 3 — Tableau Dashboard Development

Built multiple charts:

Bar charts for depression distribution

Heatmaps for correlation between academic pressure, sleep, and depression

Trend charts for study hours and satisfaction

Donut/Bar charts for demographic breakdown

Added slicers/filters for Gender, Age Group, Academic Pressure Level, and Sleep Duration to make the dashboard interactive.

Applied professional formatting, color themes, KPIs, and tooltips for better user experience.

Step 4 — Insights Extraction

Identified strong correlation between high academic pressure, poor sleep duration, and increased depression levels.

Found that students with family history of mental illness showed higher depression frequency.

Noted that longer study hours and low study satisfaction contributed to mental health decline.

Highlighted patterns that educational institutions can use to design intervention programs.

Key Insights
1. Depression Levels

A significant portion of students reported signs of depression.

Depression was highest among students with high financial stress and poor sleep habits.

2. Academic Pressure Impact

Students with high academic pressure showed much higher depression probability compared to those with moderate/low pressure.

3. Lifestyle & Behavioral Factors

Low sleep duration and unhealthy dietary habits were common contributors.

Study satisfaction was inversely related to depression levels.

4. Risk Segmentation

High-risk groups were identified using combinations of:

Academic pressure

Financial stress

Study hours

Family mental-illness history
