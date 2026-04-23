#  Sistema de Recomendación de Películas

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

##  Descripción

Este proyecto implementa un **sistema de recomendación de películas** utilizando *filtrado colaborativo basado en similitud de coseno*, acompañado de una interfaz interactiva en Jupyter Notebook con estilo tipo Netflix.

El sistema permite seleccionar un usuario y obtener recomendaciones personalizadas en tiempo real.

---

## 🧠Tecnologías utilizadas

* Python
* Pandas
* Scikit-learn
* Matplotlib
* IPyWidgets
* HTML + CSS (inline)

---

##  Metodología

### 🔹 Filtrado colaborativo basado en ítems

1. Construcción de matriz usuario–película
2. Cálculo de similitud con **Cosine Similarity**
3. Generación de recomendaciones:

   * Basadas en películas vistas
   * Excluyendo las ya vistas
   * Ponderadas por similitud

---

## Dataset

Dataset sintético generado en el código:

* 16 usuarios
* 15 películas
* Ratings entre 1 y 5
* Simulación de comportamiento real (no todos ven todo)

---

##  Funcionalidades

✔️ Selección de usuario interactiva
✔️ Identificación de película favorita
✔️ Recomendaciones personalizadas
✔️ Visualización con gráficas
✔️ Interfaz estilo Netflix
✔️ Exportación a CSV

---

##  Interfaz

* UI estilo Netflix
* Tarjetas de recomendaciones
* Dashboard con gráficas horizontales

---

## Instalación y uso

### 1. Clonar repositorio

```bash
git clone https://github.com/tu-usuario/tu-repo.git
```

### 2. Instalar dependencias

```bash
pip install pandas matplotlib scikit-learn ipywidgets
```

### 3. Ejecutar

```bash
jupyter notebook
```

---

## 📁 Exportación de datos

```python
df.to_csv("peliculas.csv", index=False)
```

---

##  Aprendizajes clave

* Sistemas de recomendación
* Filtrado colaborativo
* Similitud de coseno
* Visualización de datos
* UI en notebooks

---

## Mejoras futuras

* Integración con API de películas (posters reales)
* Sistema de usuarios real
* Modelo híbrido (content-based + collaborative)
* Deploy en web (Flask / Streamlit)

---
