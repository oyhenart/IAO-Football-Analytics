
![Python](https://img.shields.io/badge/python-3.12-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![n8n](https://img.shields.io/badge/n8n-workflow-red?logo=n8n)
![JSON](https://img.shields.io/badge/data-JSON-lightgrey?logo=json)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/IAO-Football-Analytics/blob/main/notebooks/Scatter_plot_flechas_pases.ipynb)
![Antigravity](https://img.shields.io/badge/physics-antigravity-brightgreen?logo=python&logoColor=white)

# IAO Football Analytics 

**IAO Football Analytics** es un proyecto personal orientado al análisis de rendimiento futbolístico utilizando herramientas de *Python*, *Pandas*, *Matplotlib* y *mplsoccer*.  
El objetivo es desarrollar habilidades prácticas en *data analytics* aplicadas al fútbol, generando visualizaciones y métricas que aporten valor táctico.

---

## Estructura del repositorio

- `data/` → archivos de datos crudos o procesados.  
- `src/` → scripts de Python para procesamiento, análisis o funciones.  
- `outputs/` → gráficos, resultados y reportes generados.  
- `notebooks/` → notebooks de experimentación y análisis.
- `workflow/` → flujos de n8n para la obtención y limpieza automática de datos.

---

# Notebooks disponibles

| Notebook | Descripción | Abrir en Colab |
|-----------|-------------|----------------|
| [`Mapas_de_pases.ipynb`](notebooks/Mapas_de_pases.ipynb) | Visualización de pases entre jugadores con estructura y estilo de red. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapas_de_pases.ipynb) |
| [`Mapa_de_calor.ipynb`](notebooks/Mapa_de_calor.ipynb) | Genera mapas de calor para analizar zonas de mayor actividad en el campo. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapa_de_calor.ipynb) |
| [`Scatter_plot_flechas_pases.ipynb`](notebooks/Scatter_plot_flechas_pases.ipynb) | Muestra los pases entre jugadores con flechas indicando dirección e intensidad. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Scatter_plot_flechas_pases.ipynb) |
| [`scatter_plot_efectividad_defensiva.ipynb`](notebooks/scatter_plot_efectividad_defensiva.ipynb) | Analiza y representa visualmente las acciones defensivas de los jugadores. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/scatter_plot_efectividad_defensiva.ipynb) |
| [`Mapa_de_pases.ipynb`](notebooks/Mapa_de_pases.ipynb) | Crea mapas de pases simples como punto de partida para análisis tácticos. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oyhenart/IAO-Football-Analytics/blob/main/notebooks/Mapa_de_pases.ipynb) |
| *(Próximamente)* | Más análisis y modelos de rendimiento. |

---

## Automatización (n8n)

Para optimizar el flujo de trabajo, he integrado un sistema de automatización utilizando **n8n**. Esto permite que la recolección de datos no sea manual, facilitando un pipeline de datos más dinámico.

* **Carpeta:** `/automation`
* **Funcionalidad:** * Conexión con APIs de datos deportivos.
    * Limpieza inicial de JSONs y conversión a formato compatible con Pandas.
    * Almacenamiento automático en la carpeta `/data`.

> **Nota:** Los archivos `.json` en la carpeta de automatización son exportaciones de los workflows. Para usarlos, impórtalos en tu instancia de n8n.

## Librerías principales
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `mplsoccer`

---

## Próximos pasos
- Añadir datasets reales en `/data/`.
- Guardar visualizaciones generadas en `/outputs/`.
- Crear funciones personalizadas en `/src/` para automatizar análisis.

---

## Cómo empezar

1. Abrir el notebook en Google Colab.  
2. Instalar librerías necesarias:
   ```python
   !pip install -r requirements.txt
   
## Autor
**Israel Oyhenart**  
Contacto: [LinkedIn](https:www.linkedin.com/in/israel-oyhenart/)

## Fuentes / Créditos

Algunos ejercicios y datos fueron obtenidos o inspirados en [LanusStats](https://linktr.ee/lanusstats)  
Se usaron para fines educativos y de aprendizaje personal.
