# Teen_mental_health

## 🎯 Problem Statement
> *"How does digital consumption differ across changing demographic patterns of gender and age among adolescents (13–19 years)? Furthermore, to what extent do daily screen time and subsequent sleep deprivation negatively catalyze the broader adolescent mental health spectrum, specifically regarding stress, anxiety, and depression?"*




## 📚 Literature Review Foundations
- **Mayo Clinic:** Daily social media usage exceeding 3 hours significantly elevates internalizing risks.
- **Royal Children’s Hospital:** Evening screen exposure suppresses melatonin, reducing the sleep window and triggering daytime stress/anxiety.
- **Neurodevelopmental Research:** Prefrontal cortex maturation through age 19 correlates with escalating device dependency in late adolescence.

  

------<img width="1214" height="566" alt="image" src="https://github.com/user-attachments/assets/bd7716e8-229b-4b60-b4b7-142eb85d6fb6" />



## 🛠️ Data Preprocessing & Cleaning
1. **Feature Elimination:** Dropped `social_interaction_level` due to high subjectivity and near-zero target correlation ($+0.005$).
2. **Quality Audit:** Verified 0 null values and 0 duplicate records across 1,200 dataset rows.

---<img width="1184" height="583" alt="image" src="https://github.com/user-attachments/assets/11be2f9b-4afe-4614-8057-79a11c1ce4f5" />




## 📊 Key Visual Insights

| Plot | Description | Core Insight |
| :--- | :--- | :--- |
| **Plot 1** | Gender-Wise Digital Footprint | Males (4.56 hrs) and Females (4.51 hrs) exhibit identical daily social media consumption. |
| **Plot 2** | Age vs. Device Addiction | Addiction spikes at Age 13 (5.75), dips mid-teens, and peaks at Age 19 (5.91). |
| **Plot 3** | Social Media Tiers vs. Stress/Anxiety | Crossing 3 hours/day spikes anxiety (5.80), while 6+ hours pushes stress to 5.76. |
| **Plot 4** | Sleep vs. Stress (Depression Target) | Depression flags (`1`) occur strictly under < 6 hours sleep and stress $\ge$ 7. |
| **Plot 5** | Platform Usage vs. Anxiety by Gender | Anxiety levels remain uniform across platforms (Instagram, TikTok, Both). |
| **Plot 6** | Physical Activity Tiers vs. Mental Health | 0.5–1.2 hours of daily physical activity reduces average anxiety from 5.85 to 5.50. |

--- 
AUTHOR

Tejal Joshi

DATA SCIENTIST

LINKEDIN : https://www.linkedin.com/feed/
