# Why Do People Use Sports Tracking Apps?

**The Role of Data, Motivation, and Health Improvement in Digital Fitness Platforms**

BBA Final Project | IE University | April 2026  
Author: Ana Maria Rull Orti (ID: 16313)  
Supervisor: Prof. César Moreno Pascual

---

## Project Overview

This repository contains the quantitative analysis for my BBA thesis investigating the psychological and behavioral drivers of sports tracking app usage. Using Self-Determination Theory (SDT) and the Technology Acceptance Model (TAM) as theoretical frameworks, the study examines three key dimensions:

1. **Data feedback** and its impact on self-efficacy and goal achievement
2. **Social features** versus data tracking as engagement drivers
3. **Numerical reliance** and its relationship with anxiety and enjoyment

**Sample:** n = 101 (52 app users, 49 non-users)  
**Method:** Online survey with Pearson correlation, OLS regression, and K-Means clustering

---

## Research Hypotheses

### H1: Data Feedback Enhances Performance
*"Data feedback from sports tracking apps enhances users' self-efficacy and goal achievement."*

- **Result:** SUPPORTED
- **Key finding:** Strong positive correlation between data feedback and goal achievement (r = 0.570, p < .001, R² = 0.509)

### H2: Social Features Drive Engagement
*"Social features (sharing, competition, rewards) drive user engagement more than data tracking alone."*

- **Result:** REJECTED
- **Key finding:** Social features and data tracking contribute equally to engagement (t = 0.316, p = .753)

### H3: Numerical Reliance and Negative Outcomes
*"Over-reliance on numerical targets reduces intrinsic enjoyment and increases anxiety."*

- **Result:** PARTIALLY SUPPORTED
- **Key finding:** Numerical reliance increases anxiety (r = 0.430, p = .001) but paradoxically correlates with higher enjoyment (r = 0.379, p = .006)

---

## Tech Stack

- **Python 3.10+**
- **pandas** — data manipulation
- **scipy** — statistical testing
- **statsmodels** — OLS regression
- **scikit-learn** — K-Means clustering
- **matplotlib** — visualizations
- **Google Colab** — notebook environment

---

## Repository Structure

```
sports-tracking-apps-thesis/
├── README.md
├── notebooks/
│   └── Results_and_Analysis_updated-2.ipynb    # Complete statistical analysis
├── figures/
│   ├── Figure_1_Age_Distribution.png
│   ├── Figure_2_Gender_Distribution.png
│   ├── Figure_3_Nationality_Distribution.png
│   ├── Figure_4_Users_NonUsers.png
│   ├── Figure_5_Mean_Scores.png
│   ├── Figure_6_H1_Regression.png
│   ├── Figure_7_H2_Comparison.png
│   ├── Figure_8_H2_Regression.png
│   ├── Figure_9_H3_Regression.png
│   ├── Figure_10_H3_Negative_Effects.png
│   ├── Figure_11_NonUser_Analysis.png
│   └── Figure_12_Correlation_Heatmap.png
└── data/
    └── (survey data — available upon request)
```

---

## How to Run

### Option 1: Google Colab (Recommended)
1. Open the notebook in Google Colab
2. Upload your dataset or connect to Google Drive
3. Run all cells sequentially

### Option 2: Local Jupyter
```bash
# Clone the repository
git clone https://github.com/arullieu2021/sports-tracking-apps-thesis.git
cd sports-tracking-apps-thesis

# Install dependencies
pip install pandas scipy statsmodels scikit-learn matplotlib seaborn

# Launch Jupyter
jupyter notebook notebooks/Results_and_Analysis_updated-2.ipynb
```

---

## Key Results

### Clustering Analysis (K-Means, k=3)
The analysis identified three distinct user segments:

- **Cluster A — Motivated Achievers (46.2%):** High motivation, high outcomes, high pressure/guilt — functional dependency profile
- **Cluster B — Moderate Users (34.6%):** Balanced motivation, good outcomes, low anxiety — ideal wellbeing profile
- **Cluster C — Light Users (19.2%):** Low motivation, lowest outcomes, habitual use without strong engagement

### Statistical Summary
- **H1 composite × Goal achievement:** r = 0.570, p < .001
- **H1 composite × PA increase:** r = 0.714, p < .001
- **H2 Social vs Data tracking:** t = 0.316, p = .753 (no significant difference)
- **H3 Numerical reliance × Comparison anxiety:** r = 0.430, p = .001
- **H3 Numerical reliance × Enjoyment:** r = 0.379, p = .006 (paradox)

---

## Full Thesis

The complete written thesis (74 pages) includes:
- Comprehensive literature review (SDT, TAM, gamification, toxic tracking)
- Detailed methodology (survey design, sampling, power analysis)
- Discussion of the H3 enjoyment paradox
- Managerial implications for app developers
- Limitations and future research directions

Available upon request: ana.rull.orti@student.ie.edu

---

## Academic Context

**Institution:** IE University, Bachelor of Business Administration  
**Area:** Marketing — Empirical Research (Quantitative)  
**Supervisor:** Prof. César Moreno Pascual, PhD  
**Submission Date:** April 2026  

---

## License

This project is licensed under the MIT License — see below for details.

```
MIT License

Copyright (c) 2026 Ana Maria Rull Orti

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Acknowledgments

- Prof. César Moreno Pascual for supervision and feedback
- IE University for institutional support
- Survey participants (n = 101) for their time and responses

---

## Contact

**Ana Maria Rull Orti**  
Bachelor of Business Administration, IE University  
Email: ana.rull.orti@student.ie.edu  
LinkedIn: [linkedin.com/in/ana-maria-rull-orti](https://linkedin.com/in/ana-maria-rull-orti)

---

**If you find this research useful, please consider citing it in your work!**
