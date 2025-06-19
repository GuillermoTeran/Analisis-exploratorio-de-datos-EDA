# Análisis de comportamiento de compra de clientes — Proyecto Instacart

## ES Español

Descripción del proyecto:

Este proyecto consistió en el análisis de datos de Instacart, una plataforma de entrega de comestibles en línea. Utilizando un conjunto de datos real modificado para fines educativos, el objetivo fue explorar los hábitos de compra de los clientes, limpiar los datos y generar visualizaciones que comuniquen los principales hallazgos.

## Objetivos del análisis:
Realizar un preprocesamiento completo del dataset, corrigiendo tipos de datos, valores ausentes y duplicados.

Analizar patrones de compra en función del día de la semana, la hora del día y la frecuencia de pedidos.

Identificar los productos más populares, reordenados y añadidos primero al carrito.

Comprender el comportamiento recurrente del cliente mediante métricas como la proporción de reorden y la cantidad de artículos por pedido.

## Preparación y limpieza de datos
Se trabajó con cinco archivos principales:

instacart_orders.csv

products.csv

order_products.csv

aisles.csv

departments.csv

### Procesamiento aplicado:

Conversión de columnas a tipos de datos apropiados (int, category, datetime).

Identificación y tratamiento de valores ausentes, especialmente en columnas como days_since_prior_order.

Eliminación de duplicados con criterios lógicos según ID de usuario y orden.

Documentación de decisiones tomadas para garantizar trazabilidad y reproducibilidad.

## Análisis exploratorio de datos (EDA)
### A. Análisis temporal de pedidos
La mayoría de los pedidos se realizan entre las 9:00 y 17:00 horas, con un pico a las 10:00.

El domingo y el lunes son los días más activos para hacer pedidos.

Se observó un patrón de recurrencia de pedidos cada 7 días, indicando hábitos de compra semanales.

### B. Comportamiento de los usuarios
Comparando miércoles y sábados, el sábado mostró una mayor dispersión de horas de pedido, con más actividad en la mañana.

La mayoría de los clientes realizan entre 4 y 10 pedidos en total.

Los 20 productos más pedidos incluyen frutas frescas, leche, bananas orgánicas y pan.

### C. Hábitos de reorden y carrito
El número promedio de artículos por pedido es de aproximadamente 10 a 12 productos.

Los productos más comúnmente reordenados incluyen artículos de consumo frecuente como bananas, leche y huevos.

Se calculó la proporción de reorden por producto, destacando artículos con tasas de recompra superiores al 70%.

Se identificaron los productos más frecuentemente añadidos como el primer artículo al carrito, lo cual puede reflejar prioridades de los usuarios.

## Visualizaciones generadas:
Histogramas comparativos por hora y día de la semana.

Gráficos de barras para productos más populares y más reordenados.

Diagramas de densidad para distribución de pedidos por cliente.

Gráficos de dispersión y tablas ordenadas para análisis de reorden.

Todas las visualizaciones incluyeron:

✅ Títulos claros
✅ Ejes etiquetados
✅ Leyendas cuando fue necesario
✅ plt.show() para correcta visualización en Jupyter Notebook

## Conclusiones clave:
Los hábitos de compra siguen una estructura semanal y horaria muy marcada, útil para optimizar operaciones logísticas y campañas publicitarias.

Existen productos con alto potencial de fidelización y recurrencia que pueden formar parte de promociones o suscripciones.

Los datos permiten segmentar a los clientes según frecuencia y tipo de productos, abriendo la puerta a recomendaciones personalizadas y mejoras en retención.

## Herramientas utilizadas:

Python (pandas, numpy, matplotlib, seaborn)

Jupyter Notebook

Técnicas de EDA, limpieza de datos, visualización y segmentación de clientes


# Customer purchasing behavior analysis — Instacart Project

## US English

Project description:

This project consisted of analyzing data from Instacart, an online grocery delivery platform. Using a real dataset modified for educational purposes, the goal was to explore customer purchasing habits, clean the data, and generate visualizations that communicated the main findings.

## Analysis objectives:
Perform a complete preprocessing of the dataset, correcting data types, missing values, and duplicates.

Analyze purchasing patterns based on the day of the week, time of day, and order frequency.

Identify the most popular products, reorders, and items added to the cart first.

Understand recurring customer behavior using metrics such as reorder rate and number of items per order.

## Data preparation and cleaning
We worked with five main files:

instacart_orders.csv

products.csv

order_products.csv

aisles.csv

departments.csv

### Processing applied:

Conversion of columns to appropriate data types (int, category, datetime).

Identification and treatment of missing values, especially in columns such as days_since_prior_order.

Elimination of duplicates with logical criteria based on user ID and order.

Documentation of decisions made to ensure traceability and reproducibility.

## Exploratory data analysis (EDA)
### A. Temporal analysis of orders
Most orders are placed between 9:00 a.m. and 5:00 p.m., with a peak at 10:00 a.m.

Sunday and Monday are the busiest days for placing orders.

A pattern of recurring orders every 7 days was observed, indicating weekly purchasing habits.

### B. User behavior
Comparing Wednesdays and Saturdays, Saturdays showed a greater dispersion of order times, with more activity in the morning.

Most customers place between 4 and 10 orders in total.

The 20 most ordered products include fresh fruit, milk, organic bananas, and bread.

### C. Reorder and cart habits
The average number of items per order is approximately 10 to 12 products.

The most commonly reordered products include frequently consumed items such as bananas, milk, and eggs.

The reorder rate per product was calculated, highlighting items with repurchase rates above 70%.

The products most frequently added as the first item to the cart were identified, which may reflect user priorities.

## Visualizations generated:
Comparative histograms by hour and day of the week.

Bar charts for the most popular and most reordered products.

Density diagrams for order distribution by customer.

Scatter plots and sorted tables for reorder analysis.

All visualizations included:

✅ Clear titles
✅ Labeled axes
✅ Legends when necessary
✅ plt.show() for correct display in Jupyter Notebook

## Key conclusions:
Purchasing habits follow a very distinct weekly and hourly pattern, which is useful for optimizing logistics operations and advertising campaigns.

There are products with high potential for loyalty and recurrence that can be included in promotions or subscriptions.

The data allows customers to be segmented according to frequency and type of products, opening the door to personalized recommendations and improvements in retention.

## Tools used:

Python (pandas, numpy, matplotlib, seaborn)

Jupyter Notebook

EDA techniques, data cleaning, visualization, and customer segmentation


