# Práctica Módulo Exploración & Visualización de Datos
### Bootcamp Big Data, Machine Learning & IA_Keepcoding
___

Este repositorio contiene el desarrollo de una práctica de **exploración y visualización de datos** utilizando **Power BI**. A partir del dataset **Superstore**, se han calculado KPIs clave y se ha diseñado un dashboard 
interactivo para responder preguntas relevantes sobre los datos, como por ejemplo:

- ¿Cuáles son las categorías de productos más vendidas en cada región?
- ¿Qué categoría de productos tiene el mejor margen de beneficio y en qué orden por región?
- ¿Cuál es la tendencia de las ventas por región?
- ¿Cuál es el segmento que presenta mayor número de ventas?

---

## 🎯 Objetivos del Proyecto
- **Cálculo de los siguientes KPIs relevantes con power query:**  
  - **Total Sales:** Ventas totales.  
  - **Total Profit:** Beneficio total.  
  - **Profit Margin:** Margen de beneficio.  
- **Buenas prácticas para el diseño del Dashboard:**  
  - Máximo de 5 vistas para no sobrecargar la visualización.  
  - Gráficos adecuados según el tipo de datos, para asegurar una facil interpretación.  
  - Filtros y leyendas bien posicionados para mejorar la experiencia del usuario.
- **Interactividad:**  
  - Uso de filtros y acciones entre gráficos.  
  - Visualizaciones dinámicas que permiten explorar los datos en profundidad.  

---

## 📊 Dataset

Para el desarrollo del dashboard se ha utilizado el siguiente dataset de kaggel: [Superstore.csv](https://github.com/Leticia2512/Practica-Exploracion-Visualizacion-de-Datos/blob/main/Superstore.csv).

---

## 📈 Diseño del Dashboard
El dashboard incluye las siguientes vistas:

1. **Gráficas de barras apiladas:**
   - **Ventas por Categoría**: Ventas distribuidas por categoría. Incluye un gráfico interactivo de anillo para el detalle de las ventas por categoría y región.
   - **Ventas por Región y Segmento**: Ventas por región y segmento.
2. **Tabla:**  
   - Información detallada por región, categoría, total profit y profit margin.
3. **Gráfico de líneas:**  
   - **Ventas por Año y Trimestre**: Evolución de ventas anuales y trimestrales.

Para una mejor interacción y exploración de los datos se han usado *slicers* para filtrar por región y por fecha.

Puedes visualizar el dashboard en el siguiente enlace:
[Practica_PowerBI_SuperstoreSales_Dataset.pbix](https://github.com/Leticia2512/Practica-Exploracion-Visualizacion-de-Datos/blob/main/Practica_PowerBI_SuperstoreSales_Dataset.pbix).


---

## 🛠️ Lenguajes y Herramientas Utilizadas
- **DAX (Data Analysis Expressions)**: para cálculos y medidas en Power BI.
- **Herramienta de exploración y visulacización**: Power BI.

___

## 🔍 Conclusiones 
Este análisis permite identificar tendencias en las ventas y rentabilidad del negocio, ayudando a la toma de decisiones estratégicas. Gracias a la interactividad del dashboard, es posible filtrar los datos y enfocarse en áreas específicas de interés.

A continuación se responde a las preguntas que se plantean al inicio de la práctica:

- ¿Cuáles son las categorías de productos más vendidas en cada región? *Furniture* en todas las regiones.
  
- ¿Qué categoría de productos tiene el mejor margen de beneficio y en qué orden por región? *Other supplies*. El mayor margen de benefiios lo presenta la región *West* con un 475%, seguida de *East* con un 334% y muy cerca y por último, la región *South* con un 330%.
  
- ¿Cuál es la tendencia de las ventas por región? Todas las regiones presentan una tendencia a la alza en las ventas, siendo la región *West* la que presenta un mayor aumento y la región *South* la que menos.
  
- ¿Cuál es el segmento que presenta mayor número de ventas? *Consumer* en todas las regiones.

  


