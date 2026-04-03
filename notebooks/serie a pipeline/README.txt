# Pipeline Análisis Serie A TIM 2025/26

Automatiza scraping, limpieza y análisis de estadísticas SofaScore Serie A. Genera reportes interactivos semanales.

## **Qué hace**
- **Scraping**: Extrae Matches, Players, Shots, Teams
- **ETL**: Limpia y valida datos (posesión=100%)
- **Dashboard**: Widgets interactivos (equipos, goles, shots)
- **Automatización**: n8n + Papermill semanal

## **Estructura**
proyecto_serie_a/
├── 00_scraping_serie_a.ipynb # Extracción SofaScore
├── 01_limpiar_analizar.ipynb # ETL + Dashboard
├── data/raw/ # CSV scraping
├── data/cleaned/ # Datasets limpios
├── escudos/ # Logos equipos PNG
└── outputs/ # PDFs/HTML automáticos

##  **Instalación rápida**

pip install -r requirements.txt
jupyter lab  # o jupyter notebook
Uso manual
00_scraping_serie_a.ipynb → data/raw/

01_limpiar_analizar.ipynb → data/cleaned/ + dashboard

Automatización (n8n + Papermill)

# En n8n Execute Command node:
papermill 01_limpiar_analizar.ipynb \
  outputs/reporte_semana10.ipynb \
  -p equipo="Juventus" \
  -p fecha="2026-03-21"
Ejemplo output
CSV limpios en data/cleaned/

Dashboard interactivo con escudos

Reportes HTML/PDF en outputs/

Dependencias
Ver requirements.txt

Contacto
Israel - La Plata, AR | Portfolio: [https://github.com/oyhenart]