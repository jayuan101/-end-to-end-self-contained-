# -end-to-end-self-contained-

# Customer Segmentation & Sentiment Analysis for Marketing Insights

**Author:** Ja-Yuan Pendley  
**Stack:** Python, scikit-learn, LDA, TF-IDF, TruncatedSVD, KMeans, Matplotlib

## Overview
This project demonstrates an end-to-end marketing analytics workflow:
- Generate customer feedback data (synthetic but realistic)
- Clean text and compute lightweight **sentiment**
- Discover themes via **LDA topic modeling**
- Build customer segments using **TF-IDF → SVD → KMeans**
- Validate segments with **silhouette score**
- Visualize sentiment over time, revenue by segment, and topic share

> Mirrors my production approach: Python/SQL ETL → ML/NLP in scikit-learn → cloud-ready artifacts and BI handoff.

## Why it matters
- Identifies **price-sensitive vs. advocate** segments for targeted messaging
- Surfaces operational issues (e.g., **late delivery**) from text
- Creates deployable **features & segments** for personalization/re-marketing

## Quickstart
```bash
# 1) Create venv (optional)
python -m venv .venv && source .venv/bin/activate  # on Windows: .venv\Scripts\activate

# 2) Install deps
pip install -U pandas numpy scikit-learn matplotlib

# 3) Run
python marketing_analysis.py
