# ETL-Automatizado
# 🚕 ETL Pipeline para Análisis de Viajes de Taxi

## 📌 Descripción

Este proyecto implementa un pipeline ETL automatizado para analizar datos de viajes de taxi utilizando tecnologías cloud.

El pipeline procesa datos de movilidad urbana utilizando Python y Google Cloud y automatiza el flujo de datos con Apache Airflow.

## 🛠 Tecnologías

🐍 Python  
📊 Pandas  
☁ Google Cloud Storage  
🗄 BigQuery  
⚙ Apache Airflow  
📈 Matplotlib  
🧮 SQL  

## 🏗 Arquitectura

Raw Data  
↓  
Python ETL  
↓  
Cloud Storage  
↓  
BigQuery  
↓  
SQL Analytics  
↓  
Airflow Automation  

## 📊 Dataset

NYC Taxi Trip Data

## ⚙ Instalación

git clone repository

python -m venv venv

pip install -r requirements.txt

## ▶ Ejecutar pipeline

python scripts/etl_pipeline.py

## ⚙ Automatización

airflow standalone

activar DAG taxi_etl_pipeline

## 🎯 Resultados

El pipeline permite analizar patrones de movilidad urbana y generar métricas de transporte.
