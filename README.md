# 🚀 MaintAI: Predictive Maintenance & Damage Modeling for Turbofan Engines

Welcome to **MaintAI**, an intelligent dashboard project that brings together the power of **Machine Learning**, **Time-Series Forecasting**, and **Physics-based Simulation Modeling** to predict equipment failures—starting with jet engines. 🛠️✈️

---

## 📌 Project Overview

> **“Fix it before it breaks.”**
> **MaintAI** aims to revolutionize industrial maintenance by combining real-world sensor data with powerful prediction models that estimate **Remaining Useful Life (RUL)** of machinery components—especially turbofan engines.

This project blends data science with domain-specific simulations to simulate **damage propagation** and implement **predictive maintenance**.

---

## 🎯 Objectives

* 📊 Build a **Streamlit dashboard** that allows users to **upload and analyze sensor logs**.
* 🔍 Visualize trends and detect early signs of anomalies in engine performance.
* 🤖 Train ML models (like XGBoost) to **predict RUL** of components.
* 🔧 Simulate **engine wear and tear** using NASA’s **C-MAPSS** model.
* 📈 Forecast failures **before** they occur—saving time, cost, and risk.

---

## 🧠 What is Damage Propagation Modeling?

Using **NASA’s C-MAPSS simulator**, we model how **flow and efficiency losses** (due to wear or faults) evolve over time in **gas turbine engines**. These losses:

* Start with an initial degradation point
* Progress exponentially until failure criteria (e.g., health index = 0) is met
* Are recorded across 20+ engine sensors over multiple flight cycles

We use this physics-based approach to **generate realistic failure data** for training and validating our ML models.

---

## 🛠️ Key Features

| Feature                          | Description                                                       |
| -------------------------------- | ----------------------------------------------------------------- |
| 📁 Sensor Data Upload            | Upload time-series engine data (e.g., temperature, pressure, RPM) |
| 📉 Trend Visualization           | Line plots with thresholds, alerts, and anomaly detection         |
| 🔬 Predictive Model Output       | ML-based RUL forecasts with confidence intervals                  |
| 🧩 Anomaly Clustering (Optional) | Detect abnormal patterns using unsupervised learning              |
| 🌐 Streamlit Dashboard           | Interactive, deployed UI for monitoring health and predictions    |

---

## 🧪 Datasets Used

* 📦 **NASA C-MAPSS Dataset**: Simulated run-to-failure data for jet engines

---

## 🧰 Technology Stack

| Layer         | Tools                                |
| ------------- | ------------------------------------ |
| Language      | Python 🐍                            |
| ML/Modeling   | XGBoost, Random Forest, Scikit-learn |
| Data Prep     | Pandas, NumPy                        |
| Visualization | Seaborn, Matplotlib, Plotly          |
| Dashboard     | Streamlit (💻 cloud deployed)        |

---

## 📅 Weekly Timeline (4 Weeks)

| Week | Tasks                                    |
| ---- | ---------------------------------------- |
| 1️⃣  | Understand datasets, perform EDA         |
|  1️⃣ | Engineer features, create RUL labels     |
| 2️⃣  | Train and validate predictive ML models  |
|  2️⃣ | Build Streamlit dashboard                |
| 3️⃣  | Integrate model output into UI           |
| 4️⃣  | Final polish, deployment & documentation |

---

## 📚 Learning Outcomes

* Data wrangling and visualization for time-series sensor data
* Health index modeling & degradation forecasting
* Real-time ML deployment and dashboarding
* Bridging **physics-based modeling** with **data-driven ML**

---

## 🤝 Acknowledgements

Special thanks to:

* **NASA Ames & Glenn Research Center** for the C-MAPSS simulation tool
* [PHM Society](http://www.phmsociety.org) for their 2008 data challenge
* Our mentors and collaborators for guidance in merging **aerospace systems** and **AI**

---

## 🔗 Resources

* 📄 [Damage Propagation Paper (PHM '08)](https://ti.arc.nasa.gov/project/prognostic-data-repository)
* 💾 [NASA Prognostics Data Repository](http://www.nasa.gov/CMAPSS)
* 🧠 [XGBoost Documentation](https://xgboost.readthedocs.io)
* 🌐 [Streamlit](https://streamlit.io)

