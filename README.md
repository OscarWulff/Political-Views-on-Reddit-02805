# Repository Overview

This repository contains the code and analysis for our study of political discourse and echo chambers on Reddit. It includes two primary components:

---

## **1. Report (`report.pdf` / `report.md`)**

The report contains the full written analysis, including:

* **Introduction & Motivation** — framing online political polarization and echo chambers
* **Dataset & Preprocessing** — details on subreddit selection, user filtering, and text processing
* **Methods**

  * Network construction and community detection
  * Natural language processing pipeline
  * Echo chamber metric formulation
  * Sentiment analysis
* **Results**

  * Community structure and ideological clustering
  * Subreddit isolation scores
  * Sentiment patterns within and across political groups
  * Cross-subreddit behavior of political users
* **Discussion & Implications** — interpreting findings and considering paths to healthier online discourse

---

## **2. Notebook (`analysis.ipynb`)**

The Jupyter Notebook includes the full computational workflow:

* Data processing and cleaning
* Network statistics and structural analysis
* Sentiment distribution analysis
* Louvain community detection and interpretation
* Echo chamber score formulation and analysis
* Sentiment homogeneity metrics
* Network-based TF–IDF vector construction
* Analysis of political users’ influence on non-political forums
* Pre-processing of the additional dataset
* Sentiment scoring for political and non-political posts
* Topic identification for each political orientation

All figures used in the report can be reproduced from this notebook.

---

