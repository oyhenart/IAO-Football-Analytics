<div align="center">
  <img src="https://avatars.githubusercontent.com/u/143138109?v=4" width="120" alt="IAO Logo">

  # IAO Football Analytics

  **Analítica de Datos · Automatización · BI aplicado al Fútbol**  
  Python · n8n · StatsBomb · Visualización · Web Scraping · Longomatch

  <a href="https://www.linkedin.com/in/israel-oyhenart">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
</div>

---

## Sobre este proyecto

**IAO Football Analytics** es un proyecto personal donde desarrollo habilidades prácticas en:

- Análisis de rendimiento futbolístico.  
- Visualización táctica de eventos.  
- Automatización de flujos de datos deportivos.  
- Extracción de información desde fuentes públicas.  

El objetivo es construir un portfolio real orientado a clubes, scouting y analítica deportiva.

---

## Estructura del repositorio

Este repositorio está organizado de forma modular:

- `data/` → datasets crudos o procesados  
- `notebooks/` → análisis exploratorios y visualizaciones  
- `src/` → scripts reutilizables en Python  
- `outputs/` → imágenes generadas (mapas, gráficos, reportes)  
- `workflow/` → automatizaciones exportadas desde n8n  

---

## Stack Tecnológico

### Análisis y Visualización
- Python (`pandas`, `numpy`)
- `matplotlib`
- `mplsoccer`
- StatsBomb Open Data

### Videoanálisis
- LongoMatch (captura y etiquetado)

### Automatización
- n8n (pipelines de datos)

### Web Scraping aplicado al fútbol
- `requests`
- `BeautifulSoup`
- `Selenium`

---

## Notebooks disponibles

Actualmente el repositorio incluye los siguientes análisis:

### Mapas de pases (red de conexiones)
Archivo: `notebooks/Mapas_de_pases.ipynb`  
Visualización de pases entre jugadores con estructura tipo network.

Abrir notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapas_de_pases.ipynb)

---

### Mapa de calor
Archivo: `notebooks/Mapa_de_calor.ipynb`  
Análisis de zonas de mayor participación en el campo.

Abrir notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapa_de_calor.ipynb)

---

### Scatter de pases con flechas
Archivo: `notebooks/Scatter_plot_flechas_pases.ipynb`  
Representación de dirección e intensidad de pases.

Abrir notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Scatter_plot_flechas_pases.ipynb)

---

### Efectividad defensiva
Archivo: `notebooks/scatter_plot_efectividad_defensiva.ipynb`  
Acciones defensivas y rendimiento visual por jugador.

Abrir notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/scatter_plot_efectividad_defensiva.ipynb)

---

### Mundial 2022 (StatsBomb)
Archivo: `notebooks/mundial_2022_statsbomb.ipynb`  
Análisis de progresión, pases y distancia al arco rival usando StatsBomb Open Data.

Abrir notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/mundial_2022_statsbomb.ipynb)

---

📌 Próximamente se agregarán nuevos modelos y reportes automáticos.

---

## Automatización con n8n

El repositorio incluye flujos de automatización para evitar tareas manuales como:

- obtención de datos desde APIs deportivas
- limpieza inicial de eventos JSON
- organización automática en `/data`

Workflow disponible:

- `workflow/obtencion_datos_futbol.json`

> Los archivos `.json` son exportaciones.  
> Para utilizarlos, deben importarse dentro de una instancia local o cloud de n8n.

---

## Próximos pasos

- Incorporar datasets reales en `/data`
- Generar reportes gráficos guardados en `/outputs`
- Crear funciones reutilizables en `/src`
- Automatizar alertas y reportes post-partido con n8n
- Integrar scraping de fixtures y estadísticas públicas

---

## Autor

**Israel Oyhenart**  
Analista de Datos aplicado al Fútbol

LinkedIn:  
https://www.linkedin.com/in/israel-oyhenart

---

## Créditos

Parte del contenido y datasets fueron inspirados en ejercicios educativos de:

- LanusStats → https://linktr.ee/lanusstats

Este repositorio tiene fines de aprendizaje y desarrollo profesional.





