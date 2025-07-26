# Analyzing-Urban-Adolescents-Digital-Habits-and-Health-Impacts
This project explores average daily screen time among adolescents, categorized by primary device type (smartphone, TV, laptop, tablet) and evaluates the relationship between screen time and reported health impacts. 
# Analyzing Urban Adolescents’ Digital Habits and Health Impacts

## Introduction

In today’s digitally driven world, screen time among adolescents has become a topic of increasing concern. The proliferation of smartphones and other digital devices has reshaped how young individuals interact, learn, and entertain themselves. 

This data analysis project explores patterns in daily screen time usage among urban youth, focusing on key attributes such as:

- Age  
- Gender  
- Primary device used  
- Educational vs. recreational screen engagement  
- Potential health impacts  

The dataset, comprised entirely of urban residents aged 9 to 18, offers valuable insights into the balance (or imbalance) between educational and recreational screen use.

By examining variables such as average daily screen time, whether users exceed recommended limits, and the presence of reported health impacts, this analysis aims to identify emerging trends and behavioral patterns. 

The ultimate goal is to provide a data-driven understanding of screen time dynamics, which may inform future research, parental guidance, or policy recommendations on healthy device usage among young individuals.

---

## Executive Summary

In today’s technology-driven world, screen time among adolescents has surged, raising critical concerns about its long-term effects on youth development, education, and health.

This data analysis project explores screen time behaviors among urban adolescents aged 8 to 18, using a structured dataset to:

- Identify usage patterns  
- Assess health implications  
- Uncover device usage trends  

The study focuses on core variables such as:

- Age  
- Gender  
- Average daily screen time  
- Primary device used  
- Educational vs. recreational screen time ratio  
- Self-reported health impacts  

**Key findings include:**

- **Smartphones** are the dominant device, particularly among early adolescents.
- Average screen time **peaks around age 13**.
- A significant behavioral shift is observed around **age 11**, where screen use tilts from educational to recreational and remains stable through the teenage years.
- High screen time is strongly associated with **multiple health issues** including:
  - Eye strain  
  - Poor sleep  
  - Anxiety  
  - Obesity risk  

Interestingly, the **educational-to-recreational ratio remains relatively stable** (~0.40–0.44) across different health impact groups, suggesting that **total screen time volume**—not content type—is more critical in influencing health outcomes.

The analysis also highlights a **significant digital divide** between urban and rural adolescents. Urban youth account for over **70%** of both total screen time and educational screen usage, pointing to inequalities in infrastructure, device access, and educational opportunities.

The report concludes with **actionable recommendations** for parents, educators, healthcare professionals, and policymakers, including:

- Setting screen time boundaries  
- Promoting digital literacy  
- Screening for screen-related health symptoms  
- Addressing rural-urban disparities in digital access  

This data-driven perspective offers valuable insights into adolescent digital behavior and lays a foundation for future strategies aimed at promoting healthier, more balanced screen engagement in youth populations.

---

## Objectives

The primary objective of this data analysis project is to investigate the **patterns, behaviors, and implications** of daily screen time usage among urban adolescents.

### Specific goals include:

1. **Quantify Average Screen Time**  
   Assess the average daily screen time across different age groups and genders.  

2. **Evaluate Exceedance of Recommended Limits**  
   Identify the proportion of individuals exceeding recommended screen time thresholds and examine associated characteristics.

3. **Analyze Device Usage Patterns**  
   Understand the prevalence of different primary devices—especially smartphones—and their correlation with screen time.

4. **Explore Educational vs. Recreational Use Balance**  
   Examine how the ratio of educational to recreational screen activities varies across age and gender.

5. **Assess Health Implications**  
   Investigate reported health impacts linked to screen time, especially among high-usage individuals.

6. **Provide Actionable Insights**  
   Generate findings to support parental awareness, educational policies, and health-related recommendations regarding digital behavior in youth.

---

## Data Overview

The dataset comprises records of **screen time behavior** among **urban adolescents aged 9 to 18**. Each row represents an individual respondent, with data collected on:

- **Demographics**  
- **Device usage patterns**  
- **Potential health implications**  

### Key Variables:

- `Age`: Numeric (8–18 years)  
- `Gender`: Categorical (Male/Female)  
- `Avg_Daily_Screen_Time_hr`: Numeric (Average screen time in hours per day)  
- `Primary_Device`: Categorical (e.g., Smartphone)  
- `Exceeded_Recommended_Limit`: Boolean (True/False)  
- `Educational_to_Recreational_Ratio`: Numeric (Ratio of educational to recreational screen use)  
- `Health_Impacts`: Categorical (e.g., None, Eyestrain, Headache)  
- `Urban_or_Rural`: All values = "Urban"

### Data Integrity:

- **Duplicates**: Removed during Power BI import  
- **Formatting**: Consistent  
- **Missing Values**: None detected in the visible subset  
- **Structure**: Clean and analysis-ready  

This structured dataset provides a solid foundation for examining behavioral trends and generating evidence-based insights into screen time habits among urban youth.

---

## Data Preparation Process

Before analysis, the following preprocessing steps were completed:

1. **Data Importation and Inspection**  
2. **Handling Missing Values**  
3. **Checking for Duplicates**  
4. **Data Type Validation**  
5. **Standardization of Categorical Values**

---

## Data Analysis and Insights

### 1. Average Daily Screen Time by Primary Device

![](Images/Screenshot%202025-07-26%20232622.png) 
