# 🕵️‍♂️ NeoSilk: AI-Enhanced Dark Web Threat Intelligence Framework

NeoSilk is an **AI-powered framework** designed to collect, analyze, and visualize darknet marketplace data for cybersecurity threat intelligence. It combines automated web scraping, advanced NLP modeling, and interactive dashboards to uncover patterns and monitor illegal activity across `.onion` sites on the dark web.

---
## 🎯 Project Aim

NeoSilk aims to provide a modular and intelligent framework for dark web threat intelligence. By combining advanced scraping, natural language processing (NLP), and interactive dashboards, the system enables cybersecurity analysts to:

- Detect and monitor illicit activities (e.g., drugs, fraud, digital contraband)

- Extract meaningful insights from hidden marketplaces

- Transform unstructured darknet content into actionable intelligence

- Support early warning systems for emerging threats

- This project bridges the gap between the dark web’s anonymity and the visibility needed for proactive cyber defense.





---

## 🚀 Project Overview

Traditional cybersecurity tools often fail to monitor the highly unstructured and hidden content of darknet marketplaces. NeoSilk addresses this gap by offering an **end-to-end pipeline** that enables:

- Secure and intelligent scraping of dark web marketplaces
- Classification of illicit product listings (Drugs, Digital, Tutorials)
- Sentiment analysis of user reviews on products
- Real-time data visualization for analysts and researchers

---

## 🔍 Features

### 🧠 NLP Tasks
- **Illicit Category Classification** (Drugs, Digital, Tutorials)
  - Models: BERT, RoBERTa, DarkBERT
- **Sentiment Analysis on User Reviews**
  - Models: DistilBERT, DistilRoBERTa, DistilGPT-2
- **RAG-based Question Answering** *(exploratory)*

### 📊 Dashboards
- Interactive dashboards (Power BI & Tableau) with:
  - KPIs: Total products, views, purchases, average price, etc.
  - Funnel analysis, shipping distributions, and top seller insights
  - Category distribution, out-of-stock trends, and high-risk regions

### 🕸️ Dark Web Scraping
- Custom scrapers for `.onion` marketplaces
  - **Hidden Market**: Fully scraped (no CAPTCHA)
  - **MGM Grand**: CAPTCHA-handled with manual solving; dataset of 5K CAPTCHA images also provided
- Tor network routing via `socks5h://127.0.0.1:9150`

---

## 📦 Datasets

| Marketplace   | Description                     | Data Source | Notes                         |
|---------------|----------------------------------|-------------|-------------------------------|
| Hidden Market | No CAPTCHA, full scraping       | `.onion`    | Drugs, Digital, Tutorials     |
| MGM Grand     | CAPTCHA-protected, solved manually | `.onion` | Clean 5.8K records after filtering |

A separate dataset of **5,000 Alphanumeric CAPTCHAs** is also [hosted on Kaggle](https://www.kaggle.com/) for training CAPTCHA-solving models.

---

## 📈 Model Results

### Classification (Drugs)
- **DarkBERT** achieved the highest accuracy and F1-score across all categories.

### Sentiment Analysis (Pharmaceutical Reviews)
- **DistilRoBERTa** outperformed DistilBERT and DistilGPT-2 in sentiment classification (Positive, Neutral, Negative).

See detailed evaluation results and graphs in the `notebooks/` and `results/` folders.

---

## 🔐 Ethical Use

This project was developed **for educational and cybersecurity research purposes**. All data scraping was conducted with careful supervision by our academic advisors and follows ethical guidelines. This tool is not intended for malicious use.

---

## 📚 Team

Developed by:

- Mostafa Aly Hashem
- Nour El-Dien Mostafa Mohammed
- Mohammed Hassanien Sayed
- Adham Tarek Abdelaziz
- Abdelhamid Mahmoud Ahmed

Graduation Project – 2025  
**Cairo University**
– Faculty of Computers and Artificial Intelligence
- AI Departement

---

## 🔗 Project Links

- 🧠 **Full Project Report**: [Overleaf Link if available]
- 📊 **Kaggle Dataset (CAPTCHAs)**: [Link]
- 👨‍💻 **Full Repository**: [NeoSilk GitHub Repo](https://github.com/mostafa-aly-sayed/NeoSilk.git)

---

