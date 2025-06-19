# Análisis de comportamiento de compra de clientes — Proyecto Instacart

## ES Español

**Rol:** Analista de Datos  
**Herramientas:** Python (pandas, numpy, matplotlib, seaborn), Jupyter Notebook

### Descripción del proyecto  
Este proyecto consistió en analizar datos de Instacart, una plataforma de entrega de comestibles online. Utilizando un dataset real modificado para educación, exploramos hábitos de compra, limpiamos datos y generamos visualizaciones para comunicar hallazgos clave.

### Objetivos del análisis  
- Preprocesar el dataset: corregir tipos de datos, valores ausentes y duplicados.  
- Analizar patrones de compra según día de la semana, hora y frecuencia de pedidos.  
- Identificar productos más populares, reordenados y añadidos primero al carrito.  
- Comprender comportamiento recurrente con métricas como proporción de reorden y cantidad de artículos por pedido.

### Preparación y limpieza de datos  
Se trabajó con cinco archivos principales:  
- instacart_orders.csv  
- products.csv  
- order_products.csv  
- aisles.csv  
- departments.csv

#### Procesamiento aplicado  
- Conversión de columnas a tipos adecuados (int, category, datetime).  
- Tratamiento de valores ausentes, especialmente en days_since_prior_order.  
- Eliminación de duplicados usando criterios lógicos basados en ID usuario y orden.  
- Documentación de decisiones para trazabilidad y reproducibilidad.

### Análisis exploratorio de datos (EDA)

#### A. Análisis temporal de pedidos  
- La mayoría de pedidos se realizan entre 9:00 y 17:00 horas, con pico a las 10:00.  
- Domingo y lunes son días más activos para pedidos.  
- Patrón recurrente de pedidos cada 7 días, indicando hábito semanal.

#### B. Comportamiento de usuarios  
- Comparando miércoles y sábados, el sábado tiene mayor dispersión horaria, con más actividad en la mañana.  
- La mayoría de clientes realizan entre 4 y 10 pedidos en total.  
- Los 20 productos más pedidos incluyen frutas frescas, leche, bananas orgánicas y pan.

#### C. Hábitos de reorden y carrito  
- Número promedio de artículos por pedido: 10 a 12 productos.  
- Productos más reordenados: bananas, leche, huevos.  
- Proporción de reorden calculada, destacando artículos con tasa >70%.  
- Identificación de productos añadidos primero al carrito, reflejando prioridades del usuario.

### Visualizaciones generadas  
- Histogramas comparativos por hora y día de la semana.  
- Gráficos de barras para productos populares y reordenados.  
- Diagramas de densidad para distribución de pedidos por cliente.  
- Gráficos de dispersión y tablas ordenadas para análisis de reorden.

Todas las visualizaciones incluyeron:  
✅ Títulos claros  
✅ Ejes etiquetados  
✅ Leyendas cuando fue necesario  
✅ Uso de plt.show() para correcta visualización en Jupyter Notebook

### Conclusiones clave  
- Los hábitos de compra siguen patrones semanales y horarios marcados, útiles para optimizar logística y campañas.  
- Productos con alto potencial de fidelización pueden integrarse en promociones o suscripciones.  
- Datos permiten segmentar clientes según frecuencia y tipo de producto, facilitando recomendaciones personalizadas y retención.

### Herramientas utilizadas  
- Python (pandas, numpy, matplotlib, seaborn)  
- Jupyter Notebook  
- Técnicas de EDA, limpieza, visualización y segmentación de clientes

---

# Customer purchasing behavior analysis — Instacart Project

## US English

**Role:** Data Analyst  
**Tools:** Python (pandas, numpy, matplotlib, seaborn), Jupyter Notebook

### Project description  
This project analyzed Instacart data, an online grocery delivery platform. Using a real dataset modified for educational purposes, we explored customer purchasing habits, cleaned the data, and generated visualizations to communicate key insights.

### Analysis objectives  
- Perform complete preprocessing: fix data types, missing values, and duplicates.  
- Analyze purchasing patterns by day of week, time, and order frequency.  
- Identify most popular products, reorders, and first-added cart items.  
- Understand recurring customer behavior through reorder rate and items per order.

### Data preparation and cleaning  
Five main files were used:  
- instacart_orders.csv  
- products.csv  
- order_products.csv  
- aisles.csv  
- departments.csv

#### Processing applied  
- Converted columns to appropriate data types (int, category, datetime).  
- Treated missing values, especially in days_since_prior_order.  
- Removed duplicates using logical criteria based on user and order IDs.  
- Documented decisions to ensure traceability and reproducibility.

### Exploratory data analysis (EDA)

#### A. Temporal analysis of orders  
- Most orders placed between 9 a.m. and 5 p.m., peaking at 10 a.m.  
- Sundays and Mondays are busiest days.  
- Orders recur every 7 days, indicating weekly habits.

#### B. User behavior  
- Saturdays show wider dispersion in order times compared to Wednesdays, with more morning activity.  
- Most customers place 4 to 10 orders total.  
- Top 20 products include fresh fruit, milk, organic bananas, and bread.

#### C. Reorder and cart habits  
- Average items per order: about 10 to 12.  
- Most reordered products include bananas, milk, and eggs.  
- Reorder rates calculated, highlighting items with repurchase rates above 70%.  
- Identified products most frequently added first to cart, reflecting user priorities.

### Visualizations generated  
- Comparative histograms by hour and day of week.  
- Bar charts for most popular and reordered products.  
- Density plots for order distribution by customer.  
- Scatter plots and sorted tables for reorder analysis.

All visualizations included:  
✅ Clear titles  
✅ Labeled axes  
✅ Legends when needed  
✅ plt.show() for proper display in Jupyter Notebook

### Key conclusions  
- Purchasing habits follow distinct weekly and hourly patterns, useful for logistics and marketing optimization.  
- Certain products show high loyalty potential for promotions or subscriptions.  
- Data enables customer segmentation by frequency and product type, supporting personalized recommendations and retention.

### Tools used  
- Python (pandas, numpy, matplotlib, seaborn)  
- Jupyter Notebook  
- EDA techniques, data cleaning, visualization, and customer segmentation
