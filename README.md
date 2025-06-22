# 🌍 Carbon Veracity Analyzer | ESG Fraud Detection System

Developed as part of the **Trends Marketplace initiative** at the Carlson School of Management, the Carbon Veracity Analyzer is a GenAI-powered tool designed to detect potential fraud and promote transparency in carbon credit markets.

---

## 🎯 Objective

To build a system that analyzes both **unstructured** and **structured** ESG data sources to:
- Identify suspicious carbon credit projects
- Flag unverifiable or unvalidated claims
- Score project documents based on credibility

---

## 📦 Data Sources

- 📝 **Unstructured data**:  
  Project Design Documents (PDDs) from **[Verra’s Public Registry](https://registry.verra.org/)**

- 📊 **Structured data**:  
  UC Berkeley’s **Voluntary Registry Offsets Database (VROD)(https://gspp.berkeley.edu/berkeley-carbon-trading-project/offsets-database)**

---

## 🧠 Key Features

- ✅ **Veracity Scoring** using the **LLaMA 3** large language model
- 📉 **Anomaly Detection** using **Isolation Forest** 
- 📂 **Azure Blob Storage** integration for secure document access
- ⚙️ **Streamlit Web App**:
  - Select and analyze carbon offset projects
  - View flagged risk indicators (e.g., unverifiable baselines, lack of 3rd-party validation)
  - Download detailed reports with highlighted evidence

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Data Handling**: Pandas
- **GenAI**: LLaMA 3 via `ollama` (locally hosted)
- **Cloud Storage**: Azure Blob Storage
- **Environment Management**: `python-dotenv`
- **Anomaly Detection**: scikit-learn (Isolation Forest)
---
