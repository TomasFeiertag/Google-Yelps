> **Nota:** Este repo es un fork de un proyecto grupal (equipo OpportUnity, análisis de mercado en Filadelfia, EE.UU. para identificar oportunidades de inversión en sectores comerciales con datos de Yelp y Google Maps), original en [Franiturriagaa/PF-Google-Yelps-Final](https://github.com/Franiturriagaa/PF-Google-Yelps-Final).
>
> **Mi rol (Data Analyst / Data Engineer):**
> - Recopilación y limpieza de datos de Yelp y Google Maps, integrándolos en un Data Warehouse.
> - Análisis exploratorio de datos (EDA) para identificar los sectores más prometedores.
> - Modelo predictivo de machine learning para evaluar nuevas oportunidades de negocio.
> - Técnicas de NLP para extraer insights de reseñas de clientes.
> - Sistema de visualización interactiva de datos para la toma de decisiones.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4285F4,50:34A853,100:0d1117&height=180&section=header&text=Google%20%26%20Yelp%20Analytics&fontSize=40&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Market%20Intelligence%20%7C%20NLP%20Sentiment%20%7C%20BigQuery&descAlignY=60&descSize=17&descColor=a8f0c6" />

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

</div>


---

## 📌 Overview

Big data market analysis project for **Philadelphia, USA**, using Google Maps and Yelp reviews (2015–2022) to identify optimal investment opportunities in the commercial sector. Built a full data pipeline from raw data to a predictive ML model for business investment insights.

**Client:** Fictional investor seeking to enter the Philadelphia market  
**Team:** OpportUnity (5 Data Engineers, Analysts & ML Engineers)

---

## 🎯 Objectives

1. **Data Collection** — Extract & clean Yelp + Google Maps data into a unified Data Warehouse (BigQuery)
2. **EDA** — Identify top business categories, geographic distribution, and customer sentiment
3. **ML Model** — Predict viability of new business investments based on historical patterns
4. **Dashboard** — Interactive visualization for strategic decision-making

---

## 📊 Key Visualizations

### Top 12 Cities — Business Distribution (Yelp)
![Top 12 Cities](./Data/Images/top_12_ciudades.png)

### Top 20 Most Common Categories (Google Maps)
![Top 20 Categories](./Data/Images/Top_Categorias.png)

---

## 📈 KPIs

| KPI | Description |
|---|---|
| **Star Rating Variation (%)** | Track reputation changes over time |
| **Review vs Competition (%)** | Benchmark against competitor review volume |
| **Customer Base Growth (%)** | Measure client acquisition momentum |

---

## ⚒️ Tech Stack

| Layer | Tools |
|---|---|
| **Languages** | Python |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Power BI |
| **NLP** | NLTK (sentiment analysis on reviews) |
| **ML** | Scikit-learn |
| **Cloud** | Google Cloud, BigQuery, Google Functions, Cloud Scheduler |
| **Version Control** | Git, GitHub |

---

## 🔄 Pipeline

```
Yelp + Google Maps Data ──► ETL ──► BigQuery Data Warehouse
                                         │
                              ┌──────────┴──────────┐
                              ▼                     ▼
                         EDA + NLP           ML Predictive Model
                              │                     │
                              └──────────┬──────────┘
                                         ▼
                                    Power BI
```

---

## 📎 Resources

- 🎥 [Demo 1](https://view.genially.com/66e3ba6323483daa2b09b4b3/dossier-opportunity-demo-1)
- 🎥 [Demo 2](https://view.genially.com/66e9e7231311c2e19a16d0a6/dossier-opportunity-demo-2)
- 🎥 [Demo 3](https://view.genially.com/66f5ef5be1afa063b2cdea8c/dossier-opportunity-salford-demo-3)
- 📖 [Data Dictionary](https://docs.google.com/document/d/1wp87RQDi-Qv1rIYS5CRFyrhT0XSjsl6IxVqsItqPHKc/edit?usp=sharing)

---

## 👥 Team — OpportUnity

| Name | Role |
|---|---|
| **Tomás Feiertag** | Data Engineer |
| Thomas Bracamonte | Data Engineer |
| Valentín Testa | Data Analyst |
| Francisco Iturriaga | Data Analyst |
| Pablo Cesar | ML Ops |

---

## 👤 Contact

**Tomás Feiertag** — Data Scientist · NLP & LLMs @ Movistar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/tfeiertag/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/TomasFeiertag)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:34A853,100:4285F4&height=100&section=footer" />
