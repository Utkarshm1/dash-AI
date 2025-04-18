# dash-AI
An NLP-powered, explainable BI dashboard using Word2Vec, spaCy, and SHAP to summarize and interpret marketing data. Built for decision-makers using Dash and Power BI.
# DashAI 🧠
*An AI-powered business intelligence dashboard that speaks your language — literally.*

---

**DashAI** helps decision-makers cut through noise in marketing data using natural language processing (NLP) and explainable AI (XAI).  
From summarizing campaign reports to revealing the “why” behind KPIs, DashAI is your go-to assistant for turning data into clear, strategic insight — even if you're not a data scientist.

---

## 🔍 What it Can Do

-**Summarize marketing reports** using Word2Vec-enhanced TextRank  
-**Analyze customer sentiment** with spaCy’s transformer pipeline  
-**Explain model predictions** with SHAP (yes, it shows *why* things happen)  
 **Visualize it all in dashboards** with Plotly Dash or Power BI  
 **Designed for non-tech teams too** — you don’t need to write code to get insight

---

## Project Structure

dashai/
├── README.md
├── requirements.txt
├── data/                  ← Sample marketing campaign CSV
├── src/                   ← Python pipeline: ETL, NLP, SHAP, Dashboard
├── notebooks/             ← Optional walkthrough Jupyter notebook
├── assets/                ← Diagrams and visuals



---

## ⚙️ Tech Stack

Built with:
**Python, spaCy, SHAP, XGBoost, Gensim, Plotly Dash, Power BI**

---

## 📄 Research Behind DashAI

This repo supports the paper:  
**“DashAI: An Explainable NLP-Powered Business Intelligence Dashboard”**  
[arXiv submission coming soon]  
Written by: [Utkarsh Mishra](www.linkedin.com/in/utkarsh-mishra-a37193160)

---

## 🚀 Quick Start

Here’s how to run DashAI locally:

```bash
# Clone this repo
git clone https://github.com/Utkarshm1/dash-AI.git
cd dash-AI

# Install dependencies
pip install -r requirements.txt

# Fire up the dashboard
python src/dashboard.py
