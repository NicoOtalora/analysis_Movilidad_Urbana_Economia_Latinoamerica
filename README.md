# Movilidad Urbana y Economía en Latinoamérica – Análisis con TomTom Traffic Index y OECD Cities

Este repositorio contiene el análisis desarrollado para evaluar cómo la movilidad urbana se relaciona con la productividad económica en ciudades de Latinoamérica y otras regiones del mundo.

El análisis combina dos fuentes de datos reales: **TomTom Traffic Index** (más de 1,000,000 de registros de tráfico por ciudad) y **OECD Cities** (indicadores económicos como PIB per cápita, desempleo, calidad del aire y población), que fueron limpiados, estandarizados y combinados para identificar en qué ciudades conviene invertir en infraestructura de transporte.

## 📂 Contenido del repositorio

- `notebooks/mobility_economy_project.ipynb`
  → Notebook principal con carga, limpieza, unión de datasets, análisis de tráfico y economía, visualizaciones y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK_EN_GITHUB)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/mobility_economy_project.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente los datasets `tomtom_traffic.csv` y `oecd_city_economy.csv` desde `/datasets/` (o desde un enlace público, según corresponda)

## 🧠 Objetivo del análisis

- Limpiar y estandarizar datos reales de tráfico y economía (formatos de fecha, separadores numéricos, nombres de columnas)
- Unir ambos datasets por ciudad y año para construir una vista consolidada
- Analizar y visualizar la relación entre congestión vehicular (`jams_delay`) y PIB per cápita (`city_gdp_capita`)
- Identificar patrones entre movilidad y desarrollo económico para apoyar decisiones de inversión en infraestructura de transporte

## 📌 Principales hallazgos

- No existe una relación clara y universal entre el PIB per cápita y la congestión vehicular.
- Ciudad de México presenta alta congestión y PIB alto, mientras que Montevideo tiene PIB alto y baja congestión.
- Bogotá y Lima muestran PIB medio con congestión alta, lo que sugiere que otros factores (infraestructura, densidad poblacional, planificación urbana) influyen más que el nivel económico.

---
