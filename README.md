# Cluster Analysis of Acute Respiratory Distress Syndrome

## Introduction
This project explores clustering methods for biomedical marker data to identify distinct subgroups in patients with Acute Respiratory Distress Syndrome (ARDS). The study aims to uncover patterns in the data that may influence survival outcomes. The primary aim of this analysis is to identify clusters in the biomedical markers data. Clustering analysis is used as an exploratory technique and to understand the inherent structure of the data. The secondary aim is to determine whether the clusters correspond to the outcome variables for survival. Additionally, the analysis further evaluates the impact of significant predictors identified through clustering on survival outcomes, utilizing clustering as a dimensionality reduction technique.

ARDS is a critical condition with a high global mortality rate, necessitating innovative analytical approaches to understand its underlying patterns. This study utilizes data from 450 patients, focusing on 29 key biomedical markers recorded on the first day of ECMO treatment. 

This project was undertaken as part of the MSc Data Analytics program at the University of Glasgow (2023–24) for the *Dissertation Project*, using a dataset provided by the School. It involved conducting an independent data analysis investigation and presenting the findings in the form of a detailed dissertation.

---

## Objectives
1. **Data Preparation and Preprocessing**: Cleaning and transforming data for clustering analysis.
2. **Exploratory Data Analysis (EDA)**: Identifying trends and outliers in biomedical markers.
3. **Clustering Analysis**: Applying and comparing unsupervised learning methods.
4. **Feature Selection**: Identifying key markers influencing cluster formation and survival outcomes.
5. **Insights**: Evaluating how clusters relate to survival outcomes and deriving actionable recommendations.

---

## Tools and Technologies  

- **Languages**: R  
- **Techniques**: Machine Learning, Cluster Analysis, Predictive Modelling, High-Dimensional Data Reduction, Data Visualization, Model Evaluation   

### Libraries Used  
The following R libraries were utilized for this dissertation project:   
- `readxl`  
- `dplyr`  
- `ggplot2`  
- `tidyr`  
- `VIM`  
- `corrplot`  
- `GGally`  
- `gridExtra`  
- `factoextra`  
- `cluster`  
- `dendextend`

  ---

## Files and Repository Structure
**R folder**
- `Dissertation_Analysis.qmd`: R scripts for data preprocessing, clustering, visualization and analysis.
- `Dissertation_Report.pdf`: Final project report summarizing analysis, insights, and recommendations.

---

## Insights  
- The analysis identified two primary clusters with distinct profiles and survival outcomes, providing insights into patient subgroups.  
- Certain variables significantly influenced clustering and contributed to understanding survival predictions.  
- Reduced feature sets enhanced the efficiency and accuracy of predictive models.  
- Clustering served as an effective exploratory tool for analyzing complex, high-dimensional datasets.

---

## Conclusion
This study successfully identified meaningful clusters within biomedical marker data, providing insights into the inherent structure of the dataset. The clustering analysis demonstrated the strengths and limitations of various methods, each offering unique advantages depending on the evaluation metrics. While some methods excelled at compactness and separation, others highlighted potential outliers and noise points.

The analysis further explored the relationship between clusters and survival outcomes, revealing distinct patterns and associations, though clusters alone were insufficient for precise predictions. By incorporating selected features into predictive models, the study enhanced model performance, showcasing the utility of clustering as a tool for dimensionality reduction and exploratory analysis.

These findings emphasize the potential for clustering to uncover critical subgroups within complex datasets, offering valuable insights for more targeted investigations and applications.
