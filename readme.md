
# 📂 InternUp Capstone Solution Reference

Welcome to the Shawn Wang Data & Analysis portfolio! This repository serves as a central navigation hub for all of my interactive dashboards, visualizers, and research reports. Click on any project below to explore its code, documentation, and interactive demo.

---

## 🔗 Table of Contents

1. [H1B Visa Analysis Dashboard](#h1b-visa-analysis-dashboard)  
2. [OEWS Visualizer](#oews-visualizer)  
3. [AI-Psychology & AI-CBT Market Landscape Analysis](#ai-psychology--ai-cbt-market-landscape-analysis)

---

## 🛠️ H1B Visa Analysis Dashboard

**Description:**  
An interactive Streamlit app combining USCIS H-1B petition data with BLS OEWS wage statistics to let you explore geographic patterns, industry trends, approval rates, and salary distributions for H-1B sponsorship.

**Features:**
- Choropleth map of applications by state  
- Top-10 bar charts for cities, industries, and employers  
- Stacked bars of initial vs. continuing filings by fiscal year  
- Company-size pie chart  
- Approval-rate line charts (overall, by state, by industry)  
- Violin plots of wage distributions with optional petition-count overlay  
- In-chart controls & explanatory expanders  
- Embedded CSS styling & caching for speed

**How to Run:**
```bash
git clone https://github.com/ShouzhiWang/H1B-Data-Analysis.git
cd H1B-Data-Analysis
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
````

---

## 📈 OEWS Visualizer

**Description:**
A Streamlit-based web app for exploring the Bureau of Labor Statistics’ Occupational Employment and Wage Statistics (OEWS) data. Compare wage percentiles, job counts, and geographic variation across occupations and industries.

**Features:**

* National, state, and metro‐level choropleth maps
* Histograms of wage distributions
* Wage percentile tables
* Multi‐occupation salary comparisons
* Raw‐data explorer with search/filter

**How to Run:**

```bash
git clone https://github.com/ShouzhiWang/oews-visualizer.git
cd oews-visualizer
pip install streamlit pandas plotly
streamlit run app.py
```

---

## 📚 AI-Psychology & AI-CBT Market Landscape Analysis

**Description:**
A comprehensive market‐landscape report (PDF) analyzing the global AI-Psychology and AI-Cognitive Behavioral Therapy (AI-CBT) industry. Covers market sizing, segment dynamics, competitive positioning, regulatory hurdles, and a three‐phase commercial roadmap (2025–2028).

**Contents:**

1. Executive Summary & Key Trends
2. Market Sizing & 2024–2034 Growth Projections
3. Platform Strategies: D2C, B2B2C & Blended Care
4. Competitive Landscape & Porter’s Five Forces
5. Regulatory Environment & FDA/GDPR Compliance
6. Phase I–III Roadmap & Gantt Charts
7. Appendix: Glossary, Data Sources & Assumptions

**Access the Report:**
[Download AI-Psychology & AI-CBT Report (PDF)](/docs/Cap23.pdf)


---

### 📝 License

All projects are released under the MIT License. See [LICENSE](LICENSE) for details.

---

*Created & maintained by Shawn Wang — 2025*


