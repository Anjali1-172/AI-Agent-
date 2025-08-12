# 🌊 Life Under Water — Carbon Credits for Marine Conservation  

> **IBM AI Agent Internship Project**  
> Leveraging carbon credits and AI to protect marine ecosystems.

![Marine Conservation](https://upload.wikimedia.org/wikipedia/commons/6/6a/Coral_reef.jpg)

---

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)  
[![Google Colab](https://img.shields.io/badge/Google%20Colab-Available-orange.svg)](https://colab.research.google.com/)  
[![SDG14](https://img.shields.io/badge/SDG-14%20Life%20Below%20Water-blue)](https://sdgs.un.org/goals/goal14)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

---

## 📑 Table of Contents
1. [Project Overview](#-project-overview)  
2. [Sustainable Development Goal](#-sustainable-development-goal)  
3. [Problem Statement](#-problem-statement)  
4. [Why This Matters](#-why-this-matters)  
5. [Data Pipeline](#-data-pipeline)  
6. [Features](#-features)  
7. [Model Development](#-model-development)  
8. [Workflow](#-workflow)  
9. [Testing](#-testing)  
10. [Tools & Resources](#-tools--resources)  
11. [Effectiveness](#-effectiveness)  
12. [Model Outcome](#-model-outcome)  
13. [Project Links](#-project-links)  
14. [Conclusion](#-conclusion)  

---

## 📌 Project Overview
The **ocean** covers over **70%** of our planet, produces oxygen, absorbs CO₂, and supports millions of species.  
However, it is threatened by:
- Pollution
- Overfishing
- Rising sea temperatures
- Habitat destruction

This project explores how **carbon credits** — assigning financial value to activities that reduce emissions — can be applied to **marine conservation**.

---

## 🎯 Sustainable Development Goal
**Goal 14: Life Below Water**  
Protect and restore oceans to maintain biodiversity and combat climate change.

---

## ❗ Problem Statement
Human activities damage marine ecosystems:
- Industrial pollution
- Coastal habitat destruction
- Overfishing
- CO₂ emissions → ocean acidification

**Impact:** Threatens biodiversity, reduces carbon storage, worsens climate change.  
**Opportunity:** Carbon credits can incentivize conservation but require accurate *blue carbon* measurement.

---

## 🌍 Why This Matters
Preserving oceans is about:
- Saving marine species
- Protecting ecosystem balance
- Ensuring a sustainable future

Economic tools like carbon credits can **motivate industries, governments, and communities** to invest in ocean health.

---

## 🛠 Data Pipeline

**Data Collection:**  
- From Google Form → Google Sheets (CSV export)  
- Updates every 30 seconds

**Preprocessing:**  
- Rename long headers  
- Remove missing critical values  
- Clean numeric formatting (remove commas, convert to float)

---

## ⚙ Features
- **Energy consumed** (MWh)  
- **Fuel used** (litres)  
- **Production output** (tons)

No additional transformations — raw features are used directly.

---

## 📊 Model Development

**Main Technique:**  
- Multiple Linear Regression (MLR) to predict CO₂ emissions

**Possible Alternatives:**  
- Support Vector Regression (SVR)  
- Random Forest Regression  
- Neural Networks / LSTM for time series

---

## 🔄 Workflow
1. **Prepare data** → organize inputs & outputs  
2. **Train model** → learn relationships between variables  
3. **Predict emissions** from new input data  
4. **Categorize** into Low, Moderate, or High  
5. **Calculate carbon credits** based on allowable limits  
6. **Automate flow** using `langgraph` state management

---

## 🧪 Testing
- No formal cross-validation yet  
- Error handling for invalid/missing data  
- Logging failures in email reports

---

## 🛠 Tools & Resources
- **Python**
- **Pandas** — Data manipulation  
- **Scikit-learn** — ML training & prediction  
- **Langgraph** — Workflow orchestration  
- **Yagmail** — Gmail SMTP for reports  
- **Google Sheets** — Data source

---

## 📈 Effectiveness
- **Real-time** CO₂ forecasts from operational data  
- **Scalable** and **extensible** for advanced models  
- Relevant for **sustainability-tech** and **climate policy**

---

## 📬 Model Outcome
- Automates data collection → prediction → credit calculation → email reporting  
- Prevents duplicate emails  
- Continuous near real-time operation

---

## 🔗 Project Links
- **Model:** [Colab Notebook](https://colab.research.google.com/drive/1orEmRB-JeQLsnxG2uaZbfdkUEIRZVqQS#scrollTo=kRR6kfCApoIf)  
- **Training:** [Colab Training Notebook](https://colab.research.google.com/drive/1f0qAboYKdHkRQnTFZ8HHXLFA1OWIbYec)  
- **Google Form:** [Submit Data](https://docs.google.com/forms/d/e/1FAIpQLScEReVlvdw93XiosDxNANyPXld5O68PvYuoOwrr3P56Go9mxg/viewform)  

---

## 📌 Conclusion
This is an **MVP** demonstrating how **AI + Carbon Credits** can protect marine ecosystems.  
With **more data, advanced algorithms, and rigorous validation**, it can scale into a robust sustainability platform.

---
