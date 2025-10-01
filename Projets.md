---
layout: page
title: Projects
permalink: /project
---

# Project: Predicting Respiratory Disease Risk

<img src="Projet1/images/image2.png" width="800" height="500" />

---

## Overview

**Goal:**  
Predict the risk of chronic respiratory diseases (such as asthma, COPD) based on individual lifestyle factors and environmental pollution indicators.

---

## Data Sources

- **Lifestyle & Health Data**:  
  - ANSES (anses.fr)  
  - AMELI (ameli.fr)  

- **Pollution Data**:  
  - Open-Météo (PM2.5, NO₂, O₃, weather conditions)

---

## 🔧 Features Considered

- Age, sex, smoking status  
- Physical activity level  
- Air pollution levels (daily/weekly averages)  
- Temperature/humidity  
- Geographic location (urban vs. rural)

---

## Project Architecture

<img src="Projet1/images/architecture.png" width="800" />

Pipeline:  
1. **Data Collection** – Ameli, ANSES, Open-Météo  
2. **ETL Process** – MongoDB → Transformation → Supabase  
3. **Preprocessing & EDA** – cleaning, normalization, feature engineering  
4. **Machine Learning** – model training  
5. **Deep Learning** – neural networks  
6. **Visualization with DigDash** – interactive dashboards  
7. **Deployment** – [Web app demo](https://pmc-frontend-gvo6.onrender.com/)

---

## 🔗 Notebooks & Code
- [ETL Scripts](https://github.com/AMFATMA/fatmaamor.github.io/blob/master/Projet1/Bloc1/api.py)
- [Preprocessing & Analysis](https://fatmaamor.github.io/Projet1/Bloc2/analyse_preprocessing.ipynb)  
- [Machine Learning](https://fatmaamor.github.io/Projet1/Bloc3/machine_learning.ipynb)  
- [Deep Learning](https://fatmaamor.github.io/projet1/Bloc4/Deep_learning.ipynb)  



---

## Dashboard Preview

<img src="Projet1/images/dash.png" width="1000" />

---

## 🛠️ Tools & Technologies

<p align="left"> 
<a href="https://www.python.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" /></a>
<a href="https://pandas.pydata.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" width="40" /></a>
<a href="https://scikit-learn.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="40" /></a>
<a href="https://seaborn.pydata.org/"><img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="40" /></a>
<a href="https://www.tensorflow.org"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" width="40" /></a>
<a href="https://www.docker.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="40" /></a>
<a href="https://www.postgresql.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="40" /></a>
</p>

---

[Home](README.md) | [Contact](contact.md)






