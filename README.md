# 🎬 Sistema de Recomendación de Películas (Mini Netflix)

Este proyecto implementa un **sistema de recomendación de películas** utilizando *filtrado colaborativo basado en similitud de coseno*, acompañado de una interfaz interactiva en Jupyter Notebook con estilo tipo Netflix.

---

## 🚀 Descripción

El sistema permite seleccionar un usuario y obtener:

* 🎬 Su película favorita
* 🎯 Recomendaciones personalizadas
* 📊 Visualización de popularidad general
* 📈 Comparación de recomendaciones

La interfaz simula una experiencia tipo **Netflix**, con tarjetas visuales y gráficas en modo oscuro.

---

## 🧠 Tecnologías utilizadas

* **Python**
* **Pandas** → manejo de datos
* **Scikit-learn** → similitud de coseno
* **Matplotlib** → visualización
* **IPyWidgets** → interfaz interactiva
* **HTML + CSS (inline)** → estilo tipo Netflix

---

## 📊 Metodología

El sistema utiliza:

### 🔹 Filtrado colaborativo basado en ítems

1. Se construye una matriz **usuario–película**
2. Se calcula la similitud entre películas usando:

   * Cosine Similarity
3. Se generan recomendaciones:

   * Basadas en películas vistas por el usuario
   * Excluyendo las ya vistas
   * Ponderadas por similitud y rating

---

## 🧪 Dataset

El dataset se genera de forma sintética:

* 16 usuarios
* 15 películas
* Ratings entre 1 y 5
* No todos los usuarios ven todas las películas (simulación realista)

Ejemplo:

| user_id | movie_title  | rating |
| ------- | ------------ | ------ |
| Cesar   | Harry Potter | 5      |
| Cesar   | Infinity War | 3      |
| ...     | ...          | ...    |

---

## 🎯 Funcionalidades

✔️ Selección de usuario interactiva
✔️ Identificación de película favorita
✔️ Recomendaciones personalizadas
✔️ Visualización de datos en tiempo real
✔️ Gráficas en modo oscuro
✔️ Exportación a CSV

---

## 📸 Vista del sistema

* Interfaz tipo Netflix
* Tarjetas de películas recomendadas
* Gráficas lado a lado

---

## ▶️ Cómo ejecutar

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/tu-repo.git
```

2. Instala dependencias:

```bash
pip install pandas matplotlib scikit-learn ipywidgets
```

3. Ejecuta el notebook o script:

```bash
jupyter notebook
```

---

## 📁 Exportación de datos

El dataset puede guardarse como CSV:

```python
df.to_csv("peliculas.csv", index=False)
```

---

## 🧠 Aprendizajes clave

* Construcción de sistemas de recomendación
* Manejo de matrices usuario-item
* Aplicación de similitud de coseno
* Visualización de datos en dashboards
* Integración de UI en notebooks

---

## 🚀 Posibles mejoras

* Integración con API de películas (posters reales)
* Sistema de login de usuarios
* Modelo híbrido (contenido + colaborativo)
* Despliegue como aplicación web (Flask / Streamlit)

---

## 👨‍💻 Autor

Proyecto desarrollado como parte de una práctica en Ciencia de Datos.

---
