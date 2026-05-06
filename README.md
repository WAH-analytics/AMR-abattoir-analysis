# AMR-abattoir-analysis
Geospatial and data-driven analysis of antimicrobial resistance patterns in abattoir samples across Osun State, identifying resistance hotspots and public health risks.

# 🦠 Geospatial Surveillance of Antimicrobial Resistance (AMR)
### Evaluating Pathogen Persistence Across Critical Abattoir Reservoirs in Osun State

## 📌 Project Overview
Antimicrobial Resistance (AMR) is often called the "Silent Pandemic." This project utilizes advanced geospatial mapping and data analytics to track the prevalence of resistant bacterial isolates across four key municipalities in Osun State: **Ede, Ife, Iwo, and Osu.**

By analyzing **274 bacterial isolates** from abattoir environments, this study identifies "Superbug" hotspots and high-risk environmental reservoirs, providing a data-driven roadmap for public health intervention.

## 🚨 Public Health Problem 
Abattoirs serve as critical points for pathogen transmission, yet monitoring of antimicrobial resistance in these environments is often limited.
The absence of structured surveillance makes it difficult to:
-Identify resistance hotspots
-Track environmental contamination
-Evaluate antibiotic effectiveness
This project addresses these gaps by transforming raw laboratory data into actionable public health insights.

## 🧠 Analytical Approach
The project followed a structured analytical workflow:
-Cleaned and transformed raw laboratory data
-Engineered new analytical features to enhance insight generation
-Designed a risk-based framework to quantify environmental danger
-Built an interactive dashboard to visualize resistance patterns
-Interpreted results to generate actionable recommendations

##🧪 Dataset & Structure

Source: Abattoir environmental samples
Size: 274 bacterial isolates
Locations: Ede, Ife, Iwo, Osu
Variables: Antibiotic response, location, surface type, inhibition zones

#🧹 Data Cleaning & Feature Engineering 

The project transformed a raw dataset of 6 core columns into a sophisticated analytical framework featuring over **15 strategic metrics**, including:
* **CLSI Standardization:** Categorizing inhibition zone measurements (mm) into Sensitive, Intermediate, and Resistant.
- **Environmental Danger Index:** A custom-weighted "Risk Score" to quantify the danger level of specific surfaces.
- **Resistance Phenotyping:** Classifying isolates as **MDR** (Multi-Drug Resistant), **XDR** (Extensively Drug-Resistant), and **XDR*** (The "Superbug" – resistant to all 5 tested classes).

#📊 Dashboard & Key Insights
🌍 Geographic Hotspots
(image) 
### 1. Geographic "Epicenters"
* **Iwo:** Ranked #1 in the Resistance Risk Index.
* **Osu:** Shows a staggering **85.5% resistance rate to Ceftazidime**, rendering the drug effectively useless in this municipality.

(image) 
### 2. Environmental "Red Zones"
* **Butcher Tables:** Identified as the highest-risk surface (Risk Score: 3.00). Porous materials act as primary reservoirs for pathogen persistence.
* **Concrete Slabs:** Show high cumulative resistance to Augmentin, suggesting inadequate decontamination.
* **Surrounding Soil:** Acts as a "Warning Zone," with high resistance leakage into the broader community.

(image) 
### 3. Antibiotic Performance
* **The "Last Resort":** **Imipenem** remains the most reliable option (up to 80% sensitivity).
* **Total Failure:** **Ceftazidime** is failing globally across the study area, with resistance exceeding 68%.

## 📊 Dashboard Insights 
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%203.png)
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%204.png)
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%205.png)
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%207.png)
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%208.png)
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%2012.png)
![AMR Dashboard Overview](AMR%20Dashobard%20Overview%2015.png)


## 💡 Strategic Recommendations
1. **Infrastructure:** Replace porous wooden tables with stainless steel to prevent biofilm formation.
2. **Policy:** Restrict Ceftazidime use in local veterinary settings to slow resistance progression.
3. **Environmental:** Improve drainage systems to prevent effluent leakage into community soil.

##⚠️ Limitations
-Dataset limited to selected abattoirs within Osun State
-Resistance patterns may vary across seasons and regions
-Findings should be complemented with broader surveillance data

## 🛠️ Tech Stack
- **Data Cleaning:** Microsoft Excel
- **Feature Engineering:** Power Query
- **Visualization:** Power BI (Geospatial Mapping & Interactive Reporting)
- **Domain Expertise:** Microbiology & Public Health Surveillance

## 📂 Repository Contents
- `Abattoir AMR.pbix`: Interactive Power BI Dashboard.
- `Abattoir AMR_Case Summary.docx`: Full technical report and strategic recommendations.
- `Abattoir_AMR_Antibiotics.xlsx`: Cleaned surveillance data.
- `AMR Dashobard Overview`: Visual exports of the analytics.



---
## 👨‍🔬 About the Author
I am a **Microbiologist and Data Analyst**. I specialize in bridging the gap between laboratory science and strategic data reporting to drive data-informed health policies.

**Connect with me:**
https://www.linkedin.com/in/waliyullahi-akorede-husain-135131309/ | https://x.com/drwah001
