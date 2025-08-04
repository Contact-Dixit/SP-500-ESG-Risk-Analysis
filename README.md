# 📊 S&P 500 ESG Risk Dashboard (Power BI)

A data analysis and business intelligence project to explore Environmental, Social, and Governance (ESG) risk scores for companies listed in the S&P 500 index. The purpose is to identify which sectors and organizations have higher sustainability risks and to present those insights through an interactive Power BI dashboard.

---

## 🧩 Project Definition

**Objective:**  
To clean, analyze, and visualize ESG Risk Scores sourced from publicly available S&P 500 ESG dataset. The dashboard helps stakeholders quickly evaluate sustainability risk exposure across sectors and companies.

**KPIs Displayed:**
- Average ESG Risk Score
- Highest & Lowest ESG Scores
- Number & Percentage of Companies with High Controversy
- Sector-wise Average ESG Risk
- Breakdown of Environmental, Social & Governance Risk components
- Top high-risk companies

---

## 📁 Dataset Description

| Column                   | Description                                |
|--------------------------|--------------------------------------------|
| Symbol                  | Stock Ticker                                |
| Name                    | Company Name                                |
| Sector                  | GICS Sector                                 |
| Industry                | GICS Industry                               |
| Total ESG Risk score    | Aggregated ESG Risk                         |
| Environment Risk Score  | Environmental component score               |
| Social Risk Score       | Social component score                      |
| Governance Risk Score   | Governance component score                  |
| Controversy Score       | ESG controversy rating (severity)           |
| ESG Risk Percentile     | Percentile ranking among peers              |
| ESG Risk Level          | Categorical rating (Low, Medium, High)      |

---

## 🔧 Tech Stack

- **Power BI Desktop** — Dashboard design and visualization
- **Python / Google Colab** — Data cleaning & preprocessing
- **Pandas, NumPy** — Data wrangling

---

## 🚀 Findings & Results

- **Energy & Industrial sectors** show the **highest ESG risks**, driven mostly by environmental and governance shortcomings.
- Companies like **Occidental Petroleum**, **ExxonMobil**, and **Boeing** appear at the top of high-risk list.
- Approximately **17% of S&P 500 companies have “high controversy” scores**, signaling operational/stakeholder incidents.
- **Technology & Healthcare** sectors maintain **relatively low ESG risks**.
- Environmental and Social scores are *strongly correlated* with overall ESG risk score.

---

## 📊 Dashboard Preview

<img src='Screenshot/S&P 500 ESG Risk Power BI Dashboard' /> 

---

## 💡 Future Improvements

- Time-series ESG score tracking (year-over-year analysis)
- Include Market Cap / Financial performance overlay
- Deploy dashboard to Power BI Cloud (service)

---

## 📬 Contact

Feel free to connect on **www.linkedin.com/in/dixitpatel-senioranalyst** or reach out if you’d like to collaborate on data analytics or BI projects!
