
# Emotions, Context, and Substance Use in Adolescents
This repository contains analysis code for the paper:

**Emotions, Context, and Substance Use in Adolescents:  
A Large Language Model Analysis of Reddit Posts**

Jianfeng Zhu*, Hailong Jiang, Yulan Wang, Karin G. Coifman, Ruoming Jin, Deric R. Kenne  
(*Corresponding author: jzhu10@kent.edu*)

---

## Overview

This study examines how emotions and social contexts (family, peers, school) are expressed in adolescent substance-use discussions on Reddit’s **r/teenagers** subreddit (2018–2022).  
We combine large language model (LLM)–based annotation, statistical analysis, and interpretable machine learning to characterize emotion–context patterns associated with substance use.

This repository provides code for data preprocessing, annotation, analysis, and figure generation.
<img width="432" height="177" alt="image" src="https://github.com/user-attachments/assets/2496b8f6-4291-4764-bd47-b4a441c8f303" />

---

## Data Availability

This study uses **publicly available Reddit data**.  
Due to data size and ethical considerations, raw data are **not redistributed** in this repository.

The Reddit dataset can be accessed via **Academic Torrents**:

🔗 https://academictorrents.com/details/89d24ff9d5fbc1efcdaf9d7689d72b7548f699fc

Users are responsible for complying with Reddit’s terms of service and relevant ethical guidelines.

All examples shown in the paper are paraphrased to protect user privacy.

---

## Code Structure
The analysis pipeline is organized into the following Jupyter notebooks:

- **0_Temporal_Trends.ipynb**: Monthly trends and peak detection of substance-use posts (Figure 2)
- **1_Manual_Label_Validation.ipynb**: Human-coded validation of LLM annotations
- **2_LLM_Emotion_Annotation.ipynb**: LLM-based emotion labeling
- **3_LLM_Context_Annotation.ipynb**: LLM-based context labeling (family, peer, school)
- **4_Emotion_Context_Subtopic_Analysis.ipynb**: LLM-assisted thematic analysis of emotion–context pairings
- **5_Feature_Importance.ipynb**: Interpretable machine learning and SHAP feature importance analysis

Each script is documented to indicate its role in the analysis pipeline.

---

## Reproducibility

To install dependencies:

```bash
pip install -r requirements.txt
