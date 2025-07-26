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

This analysis examines the **average daily screen time among adolescents**, categorized by their **primary device**. Understanding which devices contribute most to screen time helps identify usage patterns and potential areas for intervention.

### Key Findings

#### 1. Smartphones Dominate Screen Time
- **Smartphones** are the most frequently used device, accounting for the **highest average daily screen time**.
- This trend aligns with global patterns of increasing mobile device dependency among youth.
- **Implication:** High smartphone usage may indicate heavy engagement with **social media**, **gaming**, or **streaming**, suggesting a need to further explore the balance between **recreational and educational** use.

#### 2. TV and Laptop Usage
- **Televisions** rank second in average screen time, reflecting continued consumption of both traditional and streaming media.
- **Laptops and tablets** show **lower average usage**, possibly indicating they are used more selectively—likely for **educational** purposes.

---

## 2. Daily Screen Time by Reported Health Impacts

![](Images/Screenshot%202025-07-26%20233945.png) 

This analysis examines the average daily screen time among urban adolescents, categorized by their primary device. Understanding which devices contribute most to screen time helps identify usage patterns and potential areas for intervention.

---

### 🔍 Key Findings

#### 📱 Highest Screen Time Among Those with Multiple Health Impacts
- Adolescents reporting single health issues (e.g., Poor Sleep) have the highest average daily screen time (approaching **12 hours**).
- **Implication**: Prolonged and uninterrupted screen exposure may amplify multiple health risks simultaneously.

#### ⚖️ Single vs. Multiple Health Effects
- Those reporting combined health issues (e.g., Poor Sleep, Anxiety, Obesity Risk) typically have **lower screen times** (between **4 to 8 hours daily**) compared to those with single issues.
- **Notable Exception**: *Anxiety* appears even in groups with high screen time, suggesting a possible two-way relationship — where anxiety leads to more screen time, and excess screen time may worsen anxiety.

#### ⚠️ Obesity Risk as an Emerging Concern
- Although not associated with the absolute highest screen times, *Obesity Risk* shows up **consistently**.
- This may be due to **sedentary behavior** from extended screen use, especially in **gaming** or **streaming-heavy** activities.

---

### 📊 Educational-to-Recreational Screen Time Ratio by Health Impact

![](Images/Screenshot%202025-07-26%20234128.png)   

This analysis examines how the balance between educational and recreational screen time correlates with reported health impacts among urban adolescents. The ratio measures what proportion of total screen time is dedicated to educational versus leisure activities.

### Key Findings

1. **Minimal Variation Across Health Impact Groups**  
   - All groups show educational-to-recreational ratios clustering between **0.40–0.44**, indicating relatively similar screen time balance regardless of health outcomes.  
   - **Implication:** The ratio of educational to recreational screen time may not be a primary determinant of health impacts.

2. **No Clear Linear Relationship**  
   - Adolescents with **no health impacts ("None")** show a ratio of **0.44**, which is in the middle range rather than the highest.  
   - Those with **multiple combined health impacts** show ratios around **0.40–0.42**, only slightly lower than other groups.  
   - **Notable Finding:** The difference between the highest and lowest ratios is less than **0.04**, suggesting weak correlation.

3. **Consistent Educational Engagement Across All Groups**  
   - All health impact categories maintain **moderate educational screen time usage (approx. 40–44%)** of total screen time.  
   - **Implication:** Adolescents generally maintain similar educational screen habits regardless of health issues.

---

### Educational-to-Recreational Screen Time Ratio by Age

![](Images/Screenshot%202025-07-26%20234158.png)

This analysis examines how the balance between educational and recreational screen time varies across different age groups among urban adolescents. The ratio measures what proportion of total screen time is dedicated to educational versus leisure activities from ages 8 to 18.

---

### Key Findings

1. **Clear Age-Related Transition at Age 11**
   - Ages **8–10** show consistently high educational ratios (**0.50**), indicating half of screen time is educational.
   - Ages **11–18** show a dramatic drop to **0.40**, representing a **20% decrease** in educational screen time proportion.
   - **Implication:** A major shift occurs around middle school, where recreational screen use becomes more dominant.

2. **Stable Pattern Through Adolescence**
   - From **ages 11–18**, the educational-to-recreational ratio remains **flat at 0.40** with no variation.
   - **Notable Finding:** Despite adolescence-related changes, the screen time balance remains stable after the initial drop.

3. **Elementary vs. Secondary School Distinction**
   - **Elementary (ages 8–10):** Maintain equal educational-recreational balance (**50:50 ratio**).
   - **Secondary (ages 11–18):** Shift to a **40:60** educational-recreational split.
   - **Implication:** School transitions may be key opportunities to reinforce educational screen habits.

---

### Age-Specific Analysis

- **Ages 8–10 (Elementary):**
  - High educational engagement likely due to **parental supervision**, **structured learning apps**, and **limited social media**.
  - Screen time aligns more with **educational goals** and **homework**.

- **Ages 11–13 (Early Middle School):**
  - Sharp transition aligns with **increased social media**, **gaming**, and **peer influence**.
  - Educational screen time becomes proportionally smaller as **recreational use rises**.

- **Ages 14–18 (High School):**
  - Educational ratio remains **low** despite higher academic demands.
  - Indicates recreational activities **strongly compete** with school-related screen use.
  - **Consistency** shows well-established behavior patterns.

---

### Educational-to-Recreational Screen Time Ratio vs. Total Daily Screen Time by Age

![](Images/Screenshot%202025-07-26%20234219.png)  

## Scatter Plot Analysis: Screen Time vs. Educational Ratio by Age

This scatter plot analysis examines the relationship between total daily screen time hours and the educational-to-recreational ratio across different age groups (8–18 years) among urban adolescents.  
Each point represents an age group, with colors distinguishing different ages.

---

### Key Findings

1. **Inverse Relationship Between Total Screen Time and Educational Ratio**
   - **Lower screen time users** (3,400–3,700 daily minutes) show **higher educational ratios (~0.50)** — representing **ages 8–10 (elementary school)**.
   - **Higher screen time users** (3,800–4,200 daily minutes) show **lower educational ratios (~0.40)** — representing **ages 11–18 (middle/high school)**.
   - **Implication:** As total screen time increases with age, the proportion of time spent on educational activities decreases.

2. **Two Distinct Clusters by Developmental Stage**
   - **Elementary Cluster (Ages 8–10):**  
     - Low total screen time (3,400–3,600 minutes/day)  
     - High educational engagement (0.50 ratio)
   - **Adolescent Cluster (Ages 11–18):**  
     - Higher total screen time (3,800–4,200 minutes/day)  
     - Consistently lower educational engagement (0.40 ratio)
   - **Notable Finding:** There is a clear separation in behavior by developmental stage, with **no overlap** between the clusters.

3. **Screen Time Growth with Stable Educational Proportion in Adolescence**
   - **Ages 11–18:**  
     - Screen time increases gradually from 3,800 to 4,200 minutes/day (approx. 10% growth over 7 years).
     - Educational ratio remains **flat at 0.40**, despite rising academic demands.
   - **Implication:** The additional screen time in adolescence is almost entirely recreational.

---

### Age-Specific Analysis

- **Ages 8–10 (Elementary - Blue/Orange/Yellow Points):**
  - **Controlled environment:** Lower screen time reflects parental control and structure.
  - **Balanced use:** Educational content makes up 50% of usage.

- **Ages 11–13 (Middle School - Various Colors):**
  - **Transition period:** Sharp increase in screen time (~3,800–3,900 minutes).
  - **Drop in educational share:** Recreational content outpaces educational use.

- **Ages 14–18 (High School - Purple/Green Points):**
  - **Peak usage:** 4,000–4,200 minutes of daily screen time.
  - **Recreational dominance persists** despite academic workload.

---

### Implications for Screen Time Management

- **Quality vs. Quantity Trade-Off:**  
  More screen time leads to a lower percentage of educational use.

- **Critical Transition Point:**  
  The shift occurs at **3.6 to 3.8 hours/day**, marking the rise of recreational dominance.

- **Adolescent Pattern Stability:**  
  Once the 60% recreational / 40% educational split is established at age 11, it **remains stable**, even as screen time increases.

---

### 6. Average Age and Daily Screen Time by Primary Device

![](Images/Screensho%202025-07-26%20234244.png)   

## Scatter Plot Analysis: Age vs. Total Daily Screen Time by Primary Device

This scatter plot analysis examines the relationship between user age and total daily screen time across different primary devices among urban adolescents.  
Each point represents a primary device category, showing how device preferences correlate with age and usage intensity.

---

### Key Findings

1. **Distinct Device-Age-Usage Clusters**
   - **Smartphone users:** Oldest demographic (~13 years) with **highest screen time (~20,000 hours annually)**
   - **TV users:** Mid-range age (~12.5 years) with **moderate screen time (~10,000 hours annually)**
   - **Tablet users:** Youngest demographic (~12 years) with **lowest screen time (~5,000 hours annually)**
   - **Laptop users:** Oldest demographic (~14.5 years) with **moderate-high screen time (~6,000 hours annually)**

2. **Age-Driven Device Migration Pattern**
   - **Tablet dominance (~12 years):** Indicates parental control and educational focus.
   - **TV as transitional device (~12.5 years):** Shared family screen time during early adolescence.
   - **Smartphone peak (~13 years):** Correlates with social media adoption and peer connection.
   - **Laptop usage (~14.5 years):** Reflects academic and productivity needs.

3. **Inverse Relationship Between Age and Screen Time Intensity**
   - **Surprising trend:** Younger smartphone users (~13 years) show **highest screen time**.
   - **Laptop users (older teens):** More **structured, academic-focused** use despite being the oldest.
   - **Implication:** **Peak screen time happens in early adolescence**, not late teens.

---

### Device-Specific Analysis

- **Smartphones (Blue - Age 13, ~20k hours):**
  - Highest-intensity screen use.
  - Social connectivity drives continuous engagement.
  - Portability leads to near-constant access.

- **TV (Purple - Age 12.5, ~10k hours):**
  - Shared family use, with parental oversight.
  - Acts as a bridge between tablet and smartphone stages.
  - Passive viewing may naturally limit duration.

- **Tablets (Orange - Age 12, ~5k hours):**
  - Preferred by the youngest users.
  - Structured and time-limited use, often educational.
  - Supports parental control and learning-based content.

- **Laptops (Light Blue - Age 14.5, ~6k hours):**
  - Used for academics, research, and productivity.
  - Lower screen time reflects more goal-oriented engagement.
  - Indicates a shift toward adult-like usage habits.

---

### Implications for Screen Time Management

- **Smartphone peak at age 13:** Marks a high-risk period for excessive screen engagement.
- **Device-specific interventions needed:** Different devices require tailored management strategies.
- **Age-appropriate device progression:** Natural migration pattern suggests developmental appropriateness of device types.

## 7. Educational-to-Recreational Screen Time Ratio by Urban vs. Rural Location

![](Images/Screenshot%202025-07-26%20234306.png) 

## Pie Chart Analysis: Educational-to-Recreational Screen Time Ratio by Location

This pie chart analysis examines the sum of educational-to-recreational ratios between urban and rural adolescents. It highlights the relative contribution of each geographic setting to overall educational screen time engagement patterns.

### Key Findings

1. **Urban Dominance in Educational Screen Time**
   - Urban areas account for **2.91K (70.38%)** of the total educational-to-recreational ratio sum.
   - Rural areas contribute **1.22K (29.62%)** of the total ratio sum.
   - *Implication:* Urban adolescents collectively demonstrate significantly higher educational screen time engagement.

2. **Geographic Disparity in Educational Engagement**
   - Urban areas contribute more than double the educational screen time ratio compared to rural areas.
   - The **70%-30%** split indicates substantial inequality in educational technology utilization.
   - *Notable Finding:* Likely driven by differences in infrastructure, resources, and access to educational technology.

3. **Population vs. Engagement Considerations**
   - Urban areas generally have larger adolescent populations, but ratio-based measurement suggests this isn't purely population-driven.
   - The gap likely reflects real behavioral differences in educational screen use.
   - *Implication:* Rural adolescents may face barriers or follow different screen usage patterns.

### Geographic Analysis

- **Urban Areas (Teal - 70.38%):**
  - Resource advantages: Better internet, device access, and education programs.
  - Structured support: More comprehensive school digital learning.
  - Parental influence: More tech-literate parents.
  - Competitive academics: Greater use of edtech for success.

- **Rural Areas (Red - 29.62%):**
  - Infrastructure limitations: Slower or limited internet access.
  - Resource constraints: Fewer devices and limited edtech tools.
  - Alternative patterns: More TV/entertainment-based screen time.
  - Fewer digital school programs: Gaps in educational tech integration.

### Implications for Educational Equity

- **Digital Divide Impact:** Rural adolescents may be disadvantaged in digital learning access.
- **Access vs. Usage:** Differences reflect both resource availability and cultural attitudes.
- **Academic Risk:** Lower educational screen ratios in rural areas may affect readiness.

## 8. Average Age by Screen Time Recommendation Compliance

![](Images/Screenshot%202025-07-26%20234323.png) 

## Pie Chart Analysis: Average Age by Screen Time Recommendation Compliance

This pie chart analysis examines the average age distribution of adolescents based on whether they exceed recommended screen time limits. The chart illustrates the relative age contributions of compliant versus non-compliant users.

### Key Findings

1. **Older Adolescents More Likely to Exceed Recommendations**
   - Adolescents who exceed limits show a higher average age contribution of **13.19 years (52.72%)**.
   - Adolescents within recommended limits have a lower average age contribution of **11.82 years (47.28%)**.
   - *Implication:* Violations of screen time limits increase with age, reflecting greater independence and reduced parental oversight.

2. **Nearly Even Split in Compliance Patterns**
   - The **52%-48%** distribution indicates that excessive screen time affects nearly half of all adolescents.
   - This near-equal split suggests screen time management is a widespread challenge.
   - *Notable Finding:* The issue affects a large portion of adolescents, not just a specific subgroup.

3. **Age-Related Decline in Compliance**
   - The **1.37-year difference** (13.19 vs. 11.82) between groups marks a significant developmental shift.
   - This pattern corresponds with increased autonomy, device ownership, and social media use among older teens.
   - *Implication:* Early adolescence (around **age 12**) may be a crucial window for screen time intervention before non-compliant habits form.

---

## 9. Total Daily Screen Time by Urban vs. Rural Location

![](Images/Screenshot%202025-07-26&20234345.png)  

Pie Chart Analysis: Total Daily Screen Time by Urban vs. Rural Adolescents

This pie chart analysis examines the sum of average daily screen time hours between urban and rural adolescents. It highlights the relative contribution of each geographic setting to overall screen time consumption.

Key Findings

Urban Dominance in Total Screen Time

Urban areas: 29.72K hours (70.39%)

Rural areas: 12.51K hours (29.61%)

Implication: Urban adolescents exhibit significantly higher daily screen time consumption.

Striking Geographic Disparity

Urban screen time is more than double that of rural areas.

The 70%-30% split mirrors educational screen time patterns.

Notable Finding: Disparity reflects differences in population density, behavior, and access.

Consistent Urban-Rural Digital Divide

Identical proportional split as in educational screen time analysis.

Rural areas show lower digital engagement across all metrics.

Implication: Geographic location shapes overall digital lifestyle patterns.

Geographic Analysis

Urban Areas (Red - 70.39%)

Infrastructure: High-speed internet enables greater screen time.

Device Access: More devices per household and individual ownership.

Lifestyle: Screens are embedded in daily routines.

Content Variety: Access to streaming, gaming, and social platforms.

Peer Influence: More screen-based social interaction.

Rural Areas (Teal - 29.61%)

Infrastructure Issues: Slower internet, connectivity limitations.

Resource Constraints: Fewer devices and data restrictions.

Alternative Activities: More outdoor and non-digital entertainment.

Traditional Lifestyles: Less screen-centered family habits.

Practical Barriers: High internet costs and limited support.

Implications for Screen Time Management

Population-Adjusted Differences: Suggest true behavioral variation.

Infrastructure Impact: Location affects digital behavior.

Health Considerations: Urban youth may face higher screen-related health risks.

Recommendations

1. Parents and Guardians

Monitor Total Screen Time: Focus on overall exposure, not just content.

Create Structured Schedules: Especially around age 11.

Encourage Offline Activities: Reading, sports, and family time.

2. Educators and Schools

Teach Digital Literacy: Encourage healthy screen habits.

Use Mobile-Friendly Tools: Leverage common devices for education.

Start Early (Ages 8–11): Critical window for behavior formation.

3. Healthcare Professionals

Screen for Digital Overuse: Check for sleep, anxiety, or eye strain.

Offer Guidance: Refer to digital wellness support if needed.

4. Policymakers and Community Leaders

Close the Digital Divide: Invest in rural digital infrastructure.

Raise Awareness: Campaigns for screen time education.

Fund Research: Explore screen time's impact on health and education.

Conclusion

This analysis highlights screen time trends among urban adolescents aged 8 to 18. Smartphones dominate usage, with screen time often exceeding limits, especially in older age groups. Despite a balanced ratio of educational vs. recreational use, high screen time is linked to health issues like poor sleep, anxiety, and eye strain.

The urban-rural divide in screen time emphasizes inequalities in access and digital habits. These findings call for a multi-stakeholder approach involving families, schools, healthcare, and policymakers to promote healthier digital behaviors.

By understanding urban screen time dynamics, this report offers a foundation for data-driven interventions, awareness campaigns, and educational programs that encourage responsible and balanced tech use among youth.


