<div align="center">
  <img src="https://avatars.githubusercontent.com/u/143138109?v=4" width="120" alt="IAO Logo" style="border-radius: 50%;">

  # IAO Football Analytics

  **Football Data Analyst & Analytics Engineer**
  *Arquitectura de Datos · Automatización · BI aplicado al Fútbol*

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/israel-oyhenart/)
  [![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white)](https://oyhenart.github.io/iao-analytics/)
</div>

## Sobre este proyecto

**IAO Football Analytics** es mi laboratorio de **Football Data Science**. 
El enfoque de este repositorio no es únicamente el análisis de rendimiento táctico, sino el diseño e implementación de **Data Pipelines** escalables. Construyo sistemas modulares que transforman datos crudos (Scraping, APIs) en inteligencia deportiva accionable orientada a clubes, departamentos de scouting y cuerpos técnicos.

---

## Estructura del repositorio

Este repositorio está organizado de forma modular:

- `data/` → datasets crudos o procesados  
- `notebooks/` → análisis exploratorios y visualizaciones  
- `src/` → scripts reutilizables en Python  
- `outputs/` → imágenes generadas (mapas, gráficos, reportes)  
- `workflow/` → automatizaciones exportadas desde n8n  

---

## Tech Stack

### Data Architecture & Extraction
![n8n](https://img.shields.io/badge/n8n-FF6D5B?style=for-the-badge&logo=n8n&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-20232A?style=for-the-badge&logo=python&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### ETL & Data Processing
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-11557C?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Visualization, Dashboards & Video
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black)
![mplsoccer](https://img.shields.io/badge/mplsoccer-2E7D32?style=for-the-badge&logo=python&logoColor=white)
![ipywidgets](https://img.shields.io/badge/ipywidgets-FFD43B?style=for-the-badge&logo=jupyter&logoColor=black)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoft-power-bi&logoColor=black)
![LongoMatch](https://img.shields.io/badge/LongoMatch-2E7D32?style=for-the-badge&logo=play&logoColor=white)

---

## Data Pipelines & Proyectos Destacados

### 1. Serie A Analysis Pipeline
Implementación de un flujo ETL modular para la liga italiana, priorizando la inmutabilidad de los datos originales y la automatización de métricas.
* **Estructura del Data Flow:** Extracción automatizada (`00_scraping`) → Limpieza y aplicación de lógica táctica (`01_limpiar_analizar`) → Integración dinámica de assets visuales mediante Pillow.

### 2. Mundial 2022 (StatsBomb Open Data)
Procesamiento masivo de eventos para el análisis de progresión, circuitos de pases y distancias al arco rival utilizando la API de StatsBomb.

### 3. Eficiencia Goleadora (Understat)
Sistema de extracción automatizada para evaluar métricas de xG (Expected Goals) y rendimiento ofensivo.

---

## Arquitectura del Repositorio

El diseño garantiza la escalabilidad del sistema y la reproducibilidad técnica:

* `proyecto_serie_a/` → Pipeline ETL completo y documentado.
* `data/`
    * `raw/` → Datasets crudos inmutables (Single Source of Truth).
    * `cleaned/` → Datos normalizados y procesados para consumo.
* `notebooks/` → Entornos de experimentación y análisis exploratorio.
* `src/` → Scripts modulares en Python para reutilización funcional.
* `outputs/` → Entregables visuales listos para reporte a cuerpo técnico.
* `workflow/` → Automatizaciones y orquestación exportadas desde n8n.
* `escudos/` → Repositorio local de assets estáticos (logos PNG).

---

## Modelos Analíticos y Visuales

Exploración interactiva de los modelos de inteligencia táctica desarrollados:

* **Mapas de pases (Red de conexiones)** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapas_de_pases.ipynb)
* **Mapas de calor (Zonas de influencia)** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapa_de_calor.ipynb)
* **Scatter de pases con direccionalidad (Flechas)** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Scatter_plot_flechas_pases.ipynb)
* **Efectividad defensiva** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/scatter_plot_efectividad_defensiva.ipynb)
* **Análisis Mundial 2022 (StatsBomb)** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/mundial_2022_statsbomb.ipynb)
* **Eficiencia Goleadora (Understat - Web Scraping)** [Abrir notebook localmente](notebooks/plantilla_understat_pro.ipynb)

<details>
<summary><b>Ver ejemplos de visualizaciones generadas</b></summary>
<br>

**Mapa de pases** ![Mapa de pases](outputs/mapa_pases.png)

**Heatmap – Rodrigo De Paul** ![Heatmap De Paul](outputs/heatmap_rodrigo_de_paul.png)

**Scatter de pases con flechas** ![Scatter flechas](outputs/scatter_flechas_pases.png)

</details>

---

## Automatización (n8n)

Integración de flujos de trabajo autónomos para optimizar tiempos de scouting y análisis:
- Obtención programada de datos desde APIs deportivas.
- Limpieza inicial y parseo de eventos JSON.
- Almacenamiento directo y estructurado en el directorio `/data`.
- *Workflow disponible para importación en:* `workflow/obtencion_datos_futbol.json`

---

#### Web Scraping y Sourcing de Datos
* **Libraries:** `BeautifulSoup`, `Selenium`, `requests`.
* **Advanced Sourcing:** `soccerdata` (Integración con Understat, FBRef, WhoScored).

---

## Próximos Pasos

- Integración de métricas avanzadas mediante modelos de Machine Learning.
- Automatización de reportes post-partido (PDF generados dinámicamente) distribuidos vía n8n.
- Despliegue de Dashboards interactivos alojados en la nube.

---

## Autor

**Israel Oyhenart**  
Analista de Datos aplicado al Fútbol

LinkedIn:  
https://www.linkedin.com/in/israel-oyhenart

---

Este repositorio tiene fines de aprendizaje y desarrollo profesional.





