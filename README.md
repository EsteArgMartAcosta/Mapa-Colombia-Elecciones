# 🗺️ Mapa-Colombia-Elecciones

Repositorio para visualizar de forma **dinámica e interactiva** el mapa de Colombia, donde al pasar el cursor sobre cada **departamento** se muestran las **cifras de votantes** (totales o por categoría, según la fuente de datos).

Este proyecto está pensado para apoyar análisis electorales, visualizaciones académicas y proyectos periodísticos o de datos abiertos.

---

## 🚀 Características principales

- Mapa interactivo de **Colombia por departamentos**.
- Al pasar el mouse sobre un departamento se muestran:
  - Nombre del departamento.
  - Número total de votantes.
  - (Opcional) Votos válidos, votos nulos, abstención, etc.
- Datos cargados desde archivo (`.csv`/`.json`) para facilitar la actualización.
- Código organizado para reutilizar el mapa con distintos conjuntos de datos.

---

## 🧰 Tecnologías utilizadas

Dependiendo de la implementación que se use en este repositorio:

- **Frontend**
  - HTML, CSS, JavaScript
  - [Leaflet](https://leafletjs.com/) o [D3.js](https://d3js.org/) para el mapa interactivo
  - GeoJSON de Colombia por departamentos

- **Datos**
  - Archivos `.csv` o `.json` con resultados de votación por departamento

> Revisa el código fuente para ver exactamente qué librerías se usan en esta versión.

---

## 📂 Estructura del repositorio

```bash
Mapa-Colombia-Elecciones/
├── data/
│   ├── colombia_departamentos.geojson   # Geometrías de los departamentos
│   ├── resultados_votacion.csv          # Datos de votantes por departamento
├── src/
│   ├── index.html                       # Página principal del mapa
│   ├── style.css                        # Estilos del mapa y tooltips
│   ├── main.js                          # Lógica del mapa y los eventos
├── README.md
