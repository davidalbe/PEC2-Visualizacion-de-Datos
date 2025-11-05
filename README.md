# Visualización de Datos — PEC 2 (Máster universitario en Ciencia de Datos - UOC)

Este repositorio contiene los códigos y datos utilizados para la **Práctica 2 (PEC 2)** de la asignatura **Visualización de Datos** del *Máster Universitario en Ciencia de Datos* de la **Universitat Oberta de Catalunya (UOC)**.

El objetivo de esta práctica es **explorar y aplicar nuevas técnicas de visualización** saliendo de la zona de confort habitual, entendiendo su esencia y adecuación según el tipo de datos y el objetivo comunicativo.

---

## Objetivos de la PEC 2

- Investigar **tres técnicas de visualización asignadas**.
- Analizar su origen, autoría, ventajas, limitaciones y usos más comunes.
- Determinar los **tipos de datos más adecuados** para cada técnica.
- Crear **una visualización práctica por técnica** utilizando datos abiertos.
- Publicar las visualizaciones online y acompañarlas de un **comentario analítico**.
- Elaborar un **vídeo explicativo (7–8 min máx.)** siguiendo el guion oficial de la PEC.

---

## Técnicas de visualización trabajadas

| Técnica | Descripción breve | Archivo Jupyter asociado |
|----------|------------------|---------------------------|
| **Area Chart** | Representa la evolución de una variable cuantitativa en el tiempo mediante un área rellena bajo una línea. Ideal para mostrar tendencias acumuladas. | [`Area_Chart.ipynb`](./Area_Chart.ipynb) |
| **Waterfall Chart** | Muestra cómo un valor inicial se ve afectado por una serie de incrementos y decrementos sucesivos. Muy útil para desglosar la variación de un total. | [`Waterfall_Chart.ipynb`](./Waterfall_Chart.ipynb) |
| **Connected Scatter Plot** | Une puntos de un diagrama de dispersión según su orden temporal, permitiendo observar simultáneamente relaciones y evolución en el tiempo. | [`Connected_Scattered_Chart.ipynb`](./Connected_Scattered_Chart.ipynb) |

---

## Estructura del repositorio

- ├── Area_Chart.ipynb # Notebook con el gráfico de área
- ├── Connected_Scattered_Chart.ipynb # Notebook con el connected scatter plot
- ├── Waterfall_Chart.ipynb # Notebook con el gráfico de cascada
- ├── datos_area_chart.csv # Datos para el gráfico de área
- ├── datos_connected_scattered_chart.xlsx # Datos para el gráfico connected scatter
- └── README.md # Este archivo

---

## Fuentes de referencia

Durante el desarrollo se consultaron los siguientes recursos especializados en visualización:

- [Data to Viz](https://www.data-to-viz.com/)
- [The Data Visualization Catalogue](https://datavizcatalogue.com/ES/)
- [DataViz Project](https://datavizproject.com/)

---

## Contenidos del vídeo explicativo

El vídeo asociado a esta práctica sigue el siguiente esquema:

1. **Presentación personal** y contexto de la práctica.  
2. **Enlaces públicos** a las visualizaciones interactivas publicadas.  
3. **Definición general** de cada técnica: origen, funcionamiento y ejemplos de aplicación.  
4. **Tipo y estructura de datos** más adecuados para cada visualización.  
5. **Demostración práctica** de la visualización creada en Python (Matplotlib / Plotly).  
6. **Comentario analítico**:  
   - Qué se representa.  
   - Qué aspecto o patrón se destaca.  
   - Qué objetivo comunicativo se busca.  
   - Por qué la técnica elegida es adecuada para ese propósito.  

---

## Tecnologías empleadas

- **Lenguaje:** Python 3.x  
- **Entorno:** Jupyter Notebook  
- **Librerías principales:**  
  - `pandas`  
  - `matplotlib`  
  - `plotly`  
  - `numpy`  

---

## Publicación

Las visualizaciones finales se encuentran disponibles en línea (versión estática o interactiva) a través de **GitHub Pages**, siguiendo los criterios de accesibilidad sin registro.

---

## Autor

**Nombre:** David Alvaro Berlanga
**Asignatura:** Visualización de Datos  
**Máster Universitario en Ciencia de Datos — UOC**  
**Año académico:** 2025–2026  

