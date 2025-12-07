# 📊 Challenge N° 1 | Alura Store | Data Science

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Finalizado-green)

## 📝 Descripción del Proyecto

Este proyecto forma parte del primer desafío de la ruta de **Ciencia de Datos** de Alura Latam. 

El objetivo principal es actuar como consultor de datos para el **Sr. Juan**, dueño de la cadena de tiendas "Alura Store". El negocio necesita liquidez para un nuevo emprendimiento y se debe tomar una decisión estratégica basada en datos: **¿Cuál de las 4 sucursales debe ser vendida?**

Para responder a esta pregunta, se realizó un análisis exhaustivo de ventas, rendimiento financiero, satisfacción del cliente y eficiencia logística.

## 🎯 Objetivos

* Consolidar y limpiar bases de datos dispersas (archivos CSV).
* Analizar métricas clave: Ingresos totales, costos de envío, calificaciones y mix de productos.
* Identificar patrones de comportamiento en cada sucursal.
* Generar visualizaciones impactantes para la toma de decisiones.
* Presentar una recomendación final justificada.

## 🛠️ Tecnologías y Herramientas

* **Python:** Lenguaje principal.
* **Pandas:** Manipulación y limpieza de DataFrames.
* **Matplotlib / Seaborn:** Generación de gráficos (Barras, Líneas, Mapas de calor).
* **Folium:** Visualización geoespacial (Mapas interactivos).
* **Jupyter Notebook / Google Colab:** Entorno de desarrollo.

## 📂 Estructura de los Datos

El análisis se basó en 4 datasets correspondientes a cada tienda, conteniendo las siguientes variables:

| Variable | Descripción |
| :--- | :--- |
| `Tienda` | Identificador de la sucursal (1, 2, 3, 4) |
| `Producto` | Nombre del artículo vendido |
| `Categoría` | Clasificación del producto (Muebles, Electrónicos, etc.) |
| `Precio` | Valor de venta del producto |
| `Costo de envío` | Costo logístico asociado a la venta |
| `Calificación` | Rating dado por el cliente (1 a 5) |
| `Lat/Lon` | Coordenadas geográficas de la venta |

## 📊 Metodología del Análisis

1.  **Carga e Integración:** Unificación de los archivos `tienda_1.csv` a `tienda_4.csv` en un único DataFrame.
2.  **Limpieza de Datos:** Verificación de tipos de datos y valores nulos.
3.  **Análisis Exploratorio (EDA):**
    * Cálculo de ingresos totales por tienda.
    * Comparativa de costos de envío promedio.
    * Evaluación de satisfacción del cliente (Promedio de calificaciones).
    * Identificación de productos *Top* y *Bottom* performers.
4.  **Visualización:** Creación de gráficos comparativos y mapas de distribución geográfica.

## 💡 Hallazgos y Recomendación

Tras el análisis, se determinó que la **Tienda 4** es la candidata ideal para la venta debido a:
* **Menor Facturación:** Es la tienda con los ingresos totales más bajos del grupo.
* **Estancamiento:** No lidera ni en volumen de ventas ni en calidad de servicio (calificación promedio).
* **Dependencia:** Su catálogo de ventas exitosas está menos diversificado que el de la tienda líder (Tienda 1).

> **Recomendación:** Vender la Tienda 4 y reinvertir el capital en mejorar la logística de la Tienda 1 y fidelizar a los clientes de la Tienda 3.

## 🚀 Cómo ejecutar este proyecto

1.  Clona el repositorio:
    ```bash
    git clone https://github.com/MiguelAngelEsc/Challenge-1-Alura-Store---Data-Science.git
    ```
2.  Instala las dependencias:
    ```bash
    pip install pandas matplotlib seaborn folium
    ```
3.  Abre el notebook en tu entorno favorito (Jupyter o Colab) y ejecuta las celdas secuencialmente.

---
**Autor:** Miguel Angel Tapiero Escobar 

**Curso:** Formación en Ciencia de Datos - Alura Latam
