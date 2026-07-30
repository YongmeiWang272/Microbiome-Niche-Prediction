# Identifying Niche-Specific Microbiome Biomarkers via Random Forest

**Author:** [Yongmei Wang] 
**Domain:** Environmental Microbiology / AI for Science

## 📌 Project Overview
In this independent project, I developed a Random Forest classification model to predict the human body site origins (e.g., gastrointestinal, oral, skin) of microbial samples based purely on taxonomic profiles. 

A critical step in my pipeline involved rigorous **data cleaning to eliminate metadata leakage** (such as sequencing centers and funding sources), ensuring the algorithm learned true biological associations rather than technical batch effects.

## 🔬 Key Biological Insights
By extracting clean genus-level features, the optimized model successfully identified keystone taxa driving ecological niche differentiation. 

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/ae2c6c6b-1139-4e98-b5f8-35ddbca98aef" />


As shown in the feature importance analysis:
*   **Propionibacterium**: Correctly identified as the top predictive biomarker, perfectly aligning with its role as a key commensal in lipid-rich skin niches.
*   **Neisseria & Rothia**: Accurately pinpointed as core oral/respiratory microbiome markers.
*   **Helicobacter**: Successfully highlighted as a highly specific indicator for the extreme gastric environment.

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
*   **Techniques:** Feature Engineering, Data Leakage Prevention, Random Forest Classification, Biological Interpretation.

## 🚀 How to Run
The complete code and analysis can be viewed in the `[你的Colab文件名].ipynb` notebook included in this repository.
