# Equality on Paper, Inequality in Practice
### Equality on paper is not enough — real equality requires power, participation, and opportunity.
**A Visual Exploration of the Gender Inequality Index (1990–2023)**

**Project Type:** Research-Based Interactive Data Visualization  
**Focus:** Visual insight discovery over statistical black-boxing  
**View Interactive Presentation:** [Canva Presentation](https://canva.link/jbtis8k2l6dvgqf)

---

## 📖 Abstract
This project investigates global gender inequality using the UNDP Gender Inequality Index (GII) dataset spanning 195 countries over 33 years (1990–2023). Through interactive and multi-frame data visualizations, we examine how gender disparities in health, empowerment, and labour market participation have evolved over time and why formal legal equality does not always translate to real-world equity. Our visualizations reveal a world where progress is real but deeply uneven, shaped by geography, development level, and cultural context.

**Keywords:** Gender Inequality Index, Data Visualization, Human Development, Tableau, Structural Inequality, Reproductive Health, Labour Gap.

---

## 🧠 Research Framework

**Problem Framing:**
Using the CPQH method (Context → Problem → Questions → Hypothesis)

**Core Questions Explored:**
* Do maternal health outcomes directly drive gender inequality scores?
* Are education and workforce inclusion the strongest levers for reducing gender inequality?
* Is political representation a faster route to gender equality than education or health?

---

## 🔬 Methodology

**Visualization Methodology Inspired By:** John Tukey, Edward Tufte, Ben Shneiderman, Cleveland & McGill

Our methodological approach focused on:
* Analyzing trends in the GII across 195 countries from 1990 to 2023.
* Examining the relationship between Human Development Index (HDI) and GII, exposing cases where high development hasn't produced proportional gender equity.
* Exploring how individual GII sub-dimensions (reproductive health, political empowerment, and labour market participation) contribute to overall inequality.

---

## 📊 Dataset

The analysis leverages datasets sourced from the **United Nations Development Programme (UNDP) Human Development Reports**:
1. **Primary Dataset**: A cross-sectional snapshot of gender inequality indicators for all 192 countries (2023) From Kaggle.
2. **Secondary Dataset**: A longitudinal panel dataset spanning 33 years (1990–2023) to enable time-series analysis.

**Dataset Author:** Gianina-Maria Petrașcu

The GII measures gender-based disadvantages across three key dimensions:
* **Reproductive Health**: Maternal Mortality Ratio & Adolescent Birth Rate.
* **Empowerment**: Parliamentary Representation & Secondary Education.
* **Labour Market**: Labour Force Participation Rate.

---

## 🧪 Hypotheses Tested (via Visual Analysis)

Our analysis is divided into three core hypotheses, each accompanied by an interactive Tableau dashboard:

### 1. Reproductive Burden Hypothesis (`Hypothesis 1.twbx`)
**Question:** Do maternal health outcomes directly drive gender inequality scores?
* Investigates the impact of adolescent birth rates and maternal mortality on the overall GII across different development tiers.

### 2. The Education-Labour Trap (`Hypothesis 2.twbx`)
**Question:** Are education and workforce inclusion the strongest levers for reducing gender inequality?
* Explores the disconnect between educational attainment and formal labour force participation for women.

### 3. Political Power as a Fast-Track to Equality (`Hypothesis 3.twbx`)
**Question:** Is political representation a faster route to gender equality than other factors?
* Examines whether female representation in parliament serves as a leading indicator for broader gender equality improvements also we include case study evidence of Saudi Arabia and UAE.

### Hypothesis Testing Results

| Hypothesis | H1 Statement | Verdict | Key Evidence |
|------------|--------------|---------|--------------|
| **H1 — Reproductive Burden** | Countries with higher adolescent birth rates and maternal mortality show significantly higher GII | Supported ✓ | Heatmap: GII rises from 0.20 to 0.61 across birth-mortality groups |
| **H2 — Education-Labour Trap** | Female education and labour force participation are the strongest predictors of GII | Supported ✓ | Female education has steepest regression slope; both must act together for maximum GII reduction |
| **H3 — Political Fast-Track** | Parliamentary inclusion reduces GII faster than education or health | Supported ✓ | Parliament change averages +9.56 during shocks vs +1.42 for education; UAE/Saudi case studies confirm |

*All three null hypotheses are rejected. The alternative hypotheses are supported by consistent visual and quantitative evidence across the dashboards.*

---

## ✨ Highlight Visuals
* Geographically mapping high GII vs. high reproductive health risks.
* Scatter plot matrices (SPLOM) comparing the impact of birth rate, education, and mortality on GII.
* Ridgeline plots showing the distribution shift of inequality across birth rate groups.
* Heatmaps detailing the joint impact of birth rate and maternal mortality on inequality.

---

## 💡 Key Takeaways
* **Progress is real but uneven:** While global averages for GII have improved, structural disparities remain deeply rooted in low-development regions.
* **Reproductive health is the foundation:** Countries that cannot ensure safe childbirth and prevent adolescent pregnancy cannot make meaningful progress on overall gender equality, regardless of their economic development level.
* **Education is the most reliable long-term lever:** Female secondary education has the strongest, most consistent relationship with GII across all contexts — but its effect is maximized only when women can also enter the workforce and political institutions.
* **Political inclusion is uniquely powerful as a shock mechanism:** When women gain parliamentary representation through structural reform rather than incremental change, GII drops immediately and substantially — as demonstrated by Saudi Arabia and the UAE.

---

## 🔗 Resources

* **Interactive Presentation:** [Canva Presentation](https://canva.link/jbtis8k2l6dvgqf)
* **GII Dataset:** [Kaggle](https://www.kaggle.com/datasets/gianinamariapetrascu/gender-inequality-index?resource=download)

---

## 📂 Repository Contents
* `Group - 14 IDV Report.docx`: The comprehensive project report detailing our exploratory data analysis, statistical findings, and dashboard designs.
* `Group - 14 IDV PPT.pptx`: The presentation slides for the project.
* `GII_Dataset.zip`: The raw and derived datasets used for the analysis.
* `Hypothesis 1.twbx`, `Hypothesis 2.twbx`, `Hypothesis 3.twbx`: Interactive Tableau workbooks containing the visualizations.

---

## 👥 Authors 

* **Urvi Kava** 
* **Harsh Patel**

### Feedback & Collaboration
Feedback and collaboration are always welcome. Feel free to open an issue or submit a pull request if you have suggestions for further analysis or visual enhancements!
