# 📦 Data Sources

This folder contains all raw data sources used in this portfolio project.  
The data is collected from both Kaggle datasets and a REST API for analytical and engineering purposes.

---

## 📊 Dataset

- **Platform:** : Kaggle
- **Dataset Name:** Ecommerce Order & Supply Chain Dataset
- **Source Link:** https://www.kaggle.com/datasets/bytadit/ecommerce-order-dataset
- **Type:** Static dataset 
- **Format:** CSV

### Description
This dataset is used as the main data source for ecommerce analytics, including order behavior, customer activity, and sales insights.

---

## 🌐 REST API — Platzi Fake Store

- **Platform:** Platzi Fake Store API
- **Base URL:** https://api.escuelajs.co/api/v1
- **Type:** REST API (dynamic data)
- **Format:** JSON

### Tables / Resources Used
- `products` → product catalog data (name, price, category, images)
- `users` → user/customer data
- `categories` → product categories

### Description
This API is used to simulate real-world data ingestion from an external system. It helps demonstrate how to work with semi-structured JSON data and build ingestion pipelines for analytics.

---

## ⚙️ Notes

- Kaggle dataset represents a **batch/static data source**
- Platzi Fake Store API represents a **real-time / external API source**
- Data is processed through a layered pipeline (bronze → silver → gold)

---

## 🎯 Purpose in Project

This combination of sources demonstrates:
- Multi-source data ingestion (file + API)
- Handling structured and semi-structured data
- Building a modern data engineering pipeline