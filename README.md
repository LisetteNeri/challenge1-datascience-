Este proyecto aplica técnicas de **Data Science** y **Análisis Exploratorio de Datos (EDA)** para ayudar a la toma de decisiones estratégicas. El objetivo es identificar la tienda menos eficiente de la cadena *Alura Store* para su posterior desinversión.

## 📝 Descripción del Proyecto

El Sr. Juan, dueño de Alura Store, busca capitalizar un nuevo emprendimiento. Para ello, necesita decidir qué tienda vender basándose en datos reales de ventas, reseñas y costos logísticos de sus 4 sucursales.

A través de este análisis, evaluamos:

* **Ingresos Brutos:** Volumen total de ventas por tienda.
* **Satisfacción del Cliente:** Análisis de valoraciones medias.
* **Mix de Productos:** Identificación de categorías y productos con mayor/menor rotación.
* **Eficiencia Logística:** Impacto del costo de envío pagado por el cliente.

## 🛠️ Tecnologías y Dependencias

El proyecto fue desarrollado en un entorno de **Jupyter Notebook** utilizando Python 3.x. Las bibliotecas principales son:

* **Pandas:** Para la carga, limpieza y manipulación de archivos CSV.
* **Matplotlib:** Para la generación de visualizaciones (barras, circulares, dispersión).
* **NumPy:** Para operaciones matemáticas y manejo de arreglos.

## 🚀 Instalación y Ejecución

1. **Clonar el repositorio:**
```bash
git clone https://github.com/LisetteNeri/challenge1-datascience-.git
```

2. **Instalar dependencias:**
Asegúrate de tener instaladas las bibliotecas necesarias:
```bash
pip install pandas matplotlib numpy
```


3. **Ejecutar el Notebook:**
Abre el archivo `.ipynb` en Jupyter Lab, VS Code o Google Colab y ejecuta todas las celdas de forma secuencial.

## 📂 Estructura del Código

El código está organizado de forma modular siguiendo estos pasos:

1. **Carga de datos:** Importación de archivos CSV desde fuentes externas.
2. **Análisis de Facturación:** Sumatoria de precios para estimar ingresos.
3. **Análisis de Categorías:** Conteo de productos por tipo.
4. **Evaluación de Calidad:** Cálculo de promedios de satisfacción.
5. **Análisis de Extremos:** Identificación de productos "estrella" y rezagados.
6. **Costo Logístico:** Cálculo del promedio de envío.

## 📈 Visualizaciones Incluidas

Para facilitar la lectura, el proyecto genera:

* **Gráficos de Barras:** Comparativa de ingresos y valoraciones.
* **Gráficos Circulares:** Distribución de ventas por categoría.
* **Gráficos de Dispersión:** Relación entre precio y costo de envío.

## 💡 Conclusiones Principales

El análisis permite concluir qué tienda presenta indicadores de bajo rendimiento (baja calificación + bajo ingreso), proporcionando al Sr. Juan una recomendación respaldada por evidencia estadística y visual.

---
