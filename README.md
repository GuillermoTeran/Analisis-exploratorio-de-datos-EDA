# Análisis de comportamiento de compra de clientes — Proyecto Instacart
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


