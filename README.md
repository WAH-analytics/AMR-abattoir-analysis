# 🦠 AMR Abattoir Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Cleaning-217346?logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-0F9D58)
![Public Health](https://img.shields.io/badge/Domain-Public%20Health-blue)
![Microbiology](https://img.shields.io/badge/Field-Microbiology-darkgreen)
![AMR](https://img.shields.io/badge/Focus-Antimicrobial%20Resistance-red)

Geospatial and data-driven analysis of antimicrobial resistance patterns in abattoir samples across Osun State, identifying resistance hotspots and public health risks. 

# 🦠 Geospatial Surveillance of Antimicrobial Resistance (AMR)
### Evaluating Pathogen Persistence Across Critical Abattoir Reservoirs in Osun State 

## 📑 Table of Contents

- [🌟 Project Highlights](#-project-highlights)
- [🎯 Project Objectives](#-project-objectives)
- [📌 Project Overview](#-project-overview)
- [🚨 Public Health Problem](#-public-health-problem)
- [🧠 Analytical Approach](#-analytical-approach)
- [🧪 Dataset & Structure](#-dataset--structure)
- [🧹 Data Cleaning & Feature Engineering](#-data-cleaning--feature-engineering)
- [📊 Dashboard & Visual Insights](#-dashboard--visual-insights)
- [📊 Key Insights](#-key-insights)
- [💡 Strategic Recommendations](#-strategic-recommendations)
- [⚠️ Limitations](#-limitations)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Repository Contents](#-repository-contents)
- [👨‍🔬 About the Author](#-about-the-author) 

## 🌟 Project Highlights

- 🦠 **274 bacterial isolates** analyzed across four municipalities in Osun State.
- 📍 Identified **geographic antimicrobial resistance hotspots** using geospatial analysis.
- 🧪 Applied **CLSI standards** to classify isolates as Sensitive, Intermediate, or Resistant.
- ⚠️ Developed a custom **Environmental Danger Index** to assess contamination risk.
- 📈 Engineered **15+ analytical metrics** from raw laboratory data.
- 📊 Built an **interactive Power BI dashboard** to communicate key public health insights.
- 💡 Produced evidence-based recommendations to support antimicrobial stewardship and environmental health policies.

## 🎯 Project Objectives

This project was undertaken to:

- Assess the prevalence and distribution of antimicrobial resistance (AMR) in abattoir-derived bacterial isolates across Osun State.
- Identify geographic hotspots with elevated resistance patterns using geospatial analysis.
- Evaluate the effectiveness of commonly used antibiotics against isolated pathogens.
- Develop analytical metrics, including an Environmental Danger Index, to prioritize high-risk environmental reservoirs.
- Transform raw laboratory data into an interactive Power BI dashboard that supports evidence-based public health decision-making.
- Generate actionable recommendations for antimicrobial stewardship, environmental sanitation, and disease surveillance.

## 📌 Project Overview
Antimicrobial Resistance (AMR) is often called the "Silent Pandemic." This project utilizes geospatial mapping and data analytics to track the prevalence of resistant bacterial isolates across four key municipalities in Osun State: **Ede, Ife, Iwo, and Osu.**

By analyzing **274 bacterial isolates** from abattoir environments, this study identifies "Superbug" hotspots and high-risk environmental reservoirs, providing a data-driven roadmap for public health intervention.

## 🚨 Public Health Problem 
Abattoirs serve as critical points for pathogen transmission, yet monitoring of antimicrobial resistance in these environments is often limited.
The absence of structured surveillance makes it difficult to:

- Identify resistance hotspots
- Track environmental contamination
- Evaluate antibiotic effectiveness
  
This project addresses these gaps by transforming raw laboratory data into actionable public health insights.

## 🧠 Analytical Approach
The project followed a structured analytical workflow:
* Cleaned and transformed raw laboratory data
* Engineered new analytical features to enhance insight generation
* Designed a risk-based framework to quantify environmental danger
* Built an interactive dashboard to visualize resistance patterns
* Interpreted results to generate actionable recommendations

## 🧪 Dataset & Structure
* Source: Atobatele et al. (2024)
doi: 10.17632/ccmrx8n7mk.1 
* Size: 274 bacterial isolates
* Locations: Ede, Ife, Iwo, Osu
Variables: Antibiotics, Sample Source, Inhibition Zones

## 🧹 Data Cleaning & Feature Engineering 
The project transformed a raw dataset of 6 core columns into a sophisticated analytical framework featuring over **15 strategic metrics**, including:
- **CLSI Standardization:** Categorizing inhibition zone measurements (mm) into Sensitive, Intermediate, and Resistant.
- **Environmental Danger Index:** A custom-weighted "Risk Score" to quantify the danger level of specific surfaces.
- **Resistance Phenotyping:** Classifying isolates as **MDR** (Multi-Drug Resistant), **XDR** (Extensively Drug-Resistant), and **XDR*** (resistant to all five tested antibiotic classes).
    
## 📊 Dashboard & Visual Insights

### Executive Dashboard
![Executive Dashboard](Images/executive_dashboard.png)

### Antibiotic Resistance Analysis
![Antibiotic Resistance Analysis](Images/antibiotic_resistance_analysis.png)

### Geographic Hotspots
![Geographic Hotspots](Images/geographic_hotspots.png)

### Environmental Risk
![Environmental and Source Risk](Images/environmental_and_source_risk.png)

### Antibiotic Performance
![Antibiotic Performance](Images/antibiotic_performance.png)

## 📊 Key Insights

### 1. Geographic Resistance Hotspots

- **Iwo recorded the highest overall resistance risk** among the four study locations, indicating that it represents the most concerning geographic hotspot in the dataset. This suggests a greater concentration of resistant isolates and highlights Iwo as a priority location for further surveillance and intervention.

- **Osu recorded an 85.5% resistance rate to Ceftazidime**, the highest observed resistance level for this antibiotic across the study locations. This means that only a small proportion of the isolates from Osu remained susceptible to Ceftazidime, indicating substantially reduced effectiveness of the antibiotic against the tested isolates in this location.

- The geographic variation in resistance patterns demonstrates that antimicrobial resistance was **not uniformly distributed across the study area**. Differences between Ede, Ife, Iwo, and Osu therefore provide useful evidence for geographically targeted surveillance and antimicrobial stewardship.

### 2. Environmental Risk Zones

- **Butcher tables recorded the highest environmental risk score (3.00)** among the sampled environmental sources. Because these surfaces are repeatedly exposed to animal materials and may be difficult to clean thoroughly, they can serve as important points for the persistence and transmission of resistant bacteria.

- **Concrete slabs also showed elevated resistance patterns**, particularly in relation to Augmentin. This highlights the importance of considering frequently contaminated working surfaces as potential reservoirs for resistant organisms, especially where sanitation and disinfection practices may be inadequate.

- **Surrounding soil represents an important environmental surveillance point.** The presence of resistant isolates in soil suggests that antimicrobial-resistant bacteria may extend beyond the immediate processing environment. Contaminated soil can potentially contribute to wider environmental dissemination through runoff, animal movement, waste disposal, and human activity.

- The source-level analysis indicates that **environmental reservoirs should be considered alongside the animals and food-processing areas themselves when designing AMR surveillance and control strategies.**

### 3. Antibiotic Performance

- **Imipenem demonstrated the highest overall susceptibility among the tested antibiotics**, reaching approximately 80% susceptibility in some locations. This indicates that Imipenem retained comparatively greater activity against the tested isolates than the other antibiotics evaluated in this study.

- However, this finding should **not be interpreted as a recommendation for routine use of Imipenem**. As a carbapenem, its effectiveness is particularly important to preserve, and continued surveillance is necessary to prevent the development and spread of carbapenem resistance.

- **Ceftazidime showed the highest resistance levels**, with resistance exceeding 68% across the study locations. The particularly high resistance observed in Osu (85.5%) suggests substantial loss of effectiveness against the tested isolates in that location.

## 💡 Strategic Recommendations

The findings suggest several opportunities for strengthening antimicrobial stewardship, environmental hygiene, and AMR surveillance across the studied abattoir environments.

1. **Improve Abattoir Surface Hygiene and Infrastructure:**  
   Butcher tables recorded a high environmental risk score. This highlights the importance of improving the materials and sanitation practices used on frequently contaminated surfaces. Where feasible, porous wooden surfaces should be replaced or upgraded with smooth, non-porous, easily disinfected materials such as stainless steel. Routine cleaning and disinfection protocols should also be strengthened to reduce the persistence and transmission of resistant bacteria.

2. **Strengthen Antimicrobial Stewardship:**  
   The high resistance observed against Ceftazidime, particularly in Osu, indicates the need for closer monitoring of antimicrobial use. Antibiotic selection should be guided by appropriate susceptibility testing. There should be professional veterinary prescription of antibiotics for the animals when needed rather than routine or indiscriminate use. Local surveillance data should also be incorporated into antimicrobial stewardship programs to support more informed treatment decisions.

3. **Strengthen Environmental Management:**  
   The presence of resistant isolates across environmental sampling points highlights the importance of proper abattoir waste and wastewater management. Improved drainage, controlled effluent disposal, and regular sanitation of surrounding areas could help reduce the movement of potentially resistant organisms from abattoir environments into surrounding soil and other environmental reservoirs.

4. **Prioritize High-Risk Locations for Surveillance:**  
   Iwo and Osu demonstrated particularly concerning resistance patterns and should be considered priority locations for continued AMR surveillance. Periodic sampling across abattoir surfaces and surrounding environmental reservoirs could help determine whether these patterns persist over time.

5. **Promote Routine AMR Monitoring:**  
   Regular monitoring of antimicrobial susceptibility patterns can provide early warning of emerging resistance and help identify changes in antibiotic effectiveness. Combining laboratory surveillance with geographic and environmental data would allow public health authorities to better identify and prioritize emerging AMR hotspots.

## ⚠️ Limitations

- **Geographic Scope:** The analysis was based on selected abattoir environments within four locations in Osun State (Ede, Ife, Iwo, and Osu). Therefore, the findings may not be representative of all abattoirs or communities within Osun State or other regions.

- **Sample Size and Coverage:** The analysis included **274 bacterial isolates**, providing useful evidence of resistance patterns within the sampled environments but limiting the extent to which the findings can be generalized to the wider population.

- **Temporal Coverage:** The dataset represents observations from a specific sampling period. Antimicrobial resistance patterns may change over time due to differences in antimicrobial use, environmental conditions, seasonal factors, and infection-control practices.

- **Association Rather Than Causation:** The analysis identifies patterns and relationships between resistance, location, antibiotic, and sample source. These associations should not be interpreted as proof that a particular environmental factor directly caused the observed resistance.

- **Risk Index:** The Environmental Danger Index was developed as an analytical prioritization framework for this project. It provides a comparative measure of environmental risk within the dataset and should not be interpreted as a standardized clinical or epidemiological risk score.

- **Need for Broader Surveillance:** The findings should be complemented with larger, multi-location, and longitudinal surveillance studies incorporating additional bacterial species, environmental variables, antimicrobial-use data, and laboratory confirmation where appropriate.

## 🛠️ Tech Stack
- **Data Cleaning:** Microsoft Excel
- **Feature Engineering:** Power Query
- **Visualization:** Power BI (Geospatial Mapping & Interactive Reporting)
- **Domain Expertise:** Microbiology & Public Health Surveillance

## 📂 Repository Contents

```text
├── Dashboard/
│   └── Abattoir AMR.pbix
│
├── Data/
│   ├── Raw/
│   │   └── AMR raw dataset.xlsx
│   └── Processed/
│       ├── Abattoir AMR.xlsx
│       └── Abattoir_AMR_Antibiotics.xlsx
│
├── Images/
│   ├── executive_dashboard.png
│   ├── antibiotic_resistance_analysis.png
│   ├── geographic_hotspots.png
│   ├── environmental_and_source_risk.png
│   └── antibiotic_performance.png
│
├── Report/
│   └── Abattoir_AMR_Case_Summary.docx
│
└── README.md
```

---
## 👨‍🔬 About the Author
I am a **Microbiologist and Data Analyst**. I specialize in bridging the gap between laboratory science and strategic data reporting to drive data-informed health policies.

**Connect with me:**
https://www.linkedin.com/in/waliyullahi-akorede-husain-135131309/ | https://x.com/drwah001
