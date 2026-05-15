# 🔍 Predictive Models — Panama Robbery Statistics

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

> **Final project for the Predictive Models course** — MSc. Data Analytics, Universidad Tecnológica de Panamá.

---

## 📌 Overview

Time series analysis of monthly robbery statistics in Panama (March 2021 – December 2023), sourced from the **Procuraduría General de la Nación (PGN)**. The project applies both classical statistical models in Excel and Python-based time series techniques to understand crime trends and forecast future behavior.

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| `robospanama.ipynb` | Seasonal decomposition, stationarity testing (ADF), log transformation, moving average smoothing |
| `modeloarima.ipynb` | ARIMA model — parameter selection, fitting, and forecasting |
| `estadistica_robos_df.xlsx` | Raw dataset used for modeling |
| `modelos_predictivos_excel.xlsx` | Excel-based models: Moving Average · Exponential Smoothing · Holt |
| `PGN - Informe Estadístico de Delitos de Robo.pptx` | Full presentation with methodology and conclusions |
| `PGN-Informe Estadistico de Delitos de Robo (word).docx` | Written report |

---

## 🧪 Methodology

### Python (`robospanama.ipynb`)
- Time series visualization — monthly robbery count
- Rolling mean & standard deviation (6-month window)
- Log transformation for variance stabilization
- Seasonal decomposition (additive model) — trend, seasonality, residuals
- **Augmented Dickey-Fuller (ADF) test** for stationarity
  - Result: series is non-stationary (p-value = 0.3958, failed to reject H₀)

### Python (`modeloarima.ipynb`)
- ARIMA parameter tuning
- Model fitting on transformed series
- Forecasting future robbery trends

### Excel (`modelos_predictivos_excel.xlsx`)
- **Moving Average** — smoothing short-term fluctuations
- **Exponential Smoothing** — weighted recent observations
- **Holt's Linear Trend Model** — capturing trend component

---

## 🛠️ Tech Stack

`Python` · `pandas` · `numpy` · `matplotlib` · `statsmodels` · `scikit-learn` · `Microsoft Excel`

---

## 📊 Dataset

- **Source:** Procuraduría General de la Nación (PGN) — Panama
- **Period:** March 2021 – December 2023 (monthly frequency)
- **Variable:** Number of robberies per month

---
---

# 🔍 Modelos Predictivos — Estadística de Robos en Panamá

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

> **Proyecto Final del curso de Modelos Predictivos** — Maestría en Analítica de Datos, Universidad Tecnológica de Panamá.

---

## 📌 Descripción

Análisis de series temporales de estadísticas mensuales de robos en Panamá (marzo 2021 – diciembre 2023), con datos provenientes de la **Procuraduría General de la Nación (PGN)**. El proyecto aplica modelos estadísticos clásicos en Excel y técnicas de series temporales en Python para entender las tendencias del crimen y proyectar su comportamiento futuro.

---

## 📂 Estructura del Repositorio

| Archivo | Descripción |
|---------|-------------|
| `robospanama.ipynb` | Descomposición estacional, prueba de estacionariedad (ADF), transformación logarítmica, suavización por promedio móvil |
| `modeloarima.ipynb` | Modelo ARIMA — selección de parámetros, ajuste y pronóstico |
| `estadistica_robos_df.xlsx` | Dataset original utilizado para los modelos |
| `modelos_predictivos_excel.xlsx` | Modelos en Excel: Promedio Móvil · Suavización Exponencial · Holt |
| `PGN - Informe Estadístico de Delitos de Robo.pptx` | Presentación completa con metodología y conclusiones |
| `PGN-Informe Estadistico de Delitos de Robo (word).docx` | Informe escrito |

---

## 🧪 Metodología

### Python (`robospanama.ipynb`)
- Visualización de la serie temporal — cantidad de robos por mes
- Media móvil y desviación estándar móvil (ventana de 6 meses)
- Transformación logarítmica para estabilizar la varianza
- Descomposición estacional (modelo aditivo) — tendencia, estacionalidad, residuos
- **Prueba de Dickey-Fuller Aumentada (ADF)** para estacionariedad
  - Resultado: serie no estacionaria (p-valor = 0.3958, no se rechaza H₀)

### Python (`modeloarima.ipynb`)
- Selección de parámetros del modelo ARIMA
- Ajuste del modelo sobre la serie transformada
- Pronóstico de tendencias futuras de robos

### Excel (`modelos_predictivos_excel.xlsx`)
- **Promedio Móvil** — suavización de fluctuaciones de corto plazo
- **Suavización Exponencial** — mayor peso a observaciones recientes
- **Modelo de Tendencia Lineal de Holt** — captura el componente de tendencia

---

## 🛠️ Stack Tecnológico

`Python` · `pandas` · `numpy` · `matplotlib` · `statsmodels` · `scikit-learn` · `Microsoft Excel`

---

## 📊 Dataset

- **Fuente:** Procuraduría General de la Nación (PGN) — Panamá
- **Período:** Marzo 2021 – Diciembre 2023 (frecuencia mensual)
- **Variable:** Cantidad de robos por mes
