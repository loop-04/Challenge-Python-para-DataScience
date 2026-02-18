# Challenge-Python-para-DataScience
Challenge - Alura 
1. Propósito del análisis.
Este proyecto fue desarrollado para evaluar el desempeño comercial de las cuatro sedes de Alura Store. El objetivo principal es transformar datos brutos de ventas en información estratégica para la gerencia, respondiendo a preguntas clave sobre rentabilidad, satisfacción del cliente y eficiencia logística y reportar a don Juan los hallazgos finales.
Se han analizado cinco elemntos:
Facturación: Determinación de la tienda con mayor volumen de ingresos.
Popularidad: Identificación de las categorías de productos más vendidas.
Satisfacción: Análisis del promedio de calificación otorgado por los clientes.
Inventario: Ranking de los productos con mayor y menor rotación.
Logística: Evaluación de los costos promedio de envío por cada sede.
2. Estructura del Proyecto
El proyecto se organiza de la siguiente manera:
2.1. Datasets:
url = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv"
url2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv"
url3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv"
url4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"
2.2. Notebook:
Challenge-Python.ipynb: Documento principal que contiene el código de Python.
2.3. Documentación:
   README.md: Descripción general y guía del Challenge.
3. Gráficos e Insights:
Para este análisis se utilizaron estilos visuales  (seaborn whitegrid) y se generaron los siguientes tipos de gráficos:
1. Facturación por Tienda (Gráfico de Barras)Insight: Existe una disparidad considerable entre la facturación de las tiendas. La Tienda 1 suele liderar los ingresos, impulsada principalmente por la venta de productos de alto valor unitario en la categoría de Electrónicos.
2. Mix de Productos (Gráfico Circular)Insight: Aunque los Electrodomésticos generan mayor facturación, categorías como Libros y Artículos para el hogar representan un mayor volumen de transacciones individuales, siendo esenciales para el flujo de caja diario.
3. Eficiencia Logística (Gráfico de Dispersión/Scatter)Insight: El costo promedio de envío es inversamente proporcional a la densidad de ventas en ciudades principales. Se detectó que las zonas con envíos de $\$0$ suelen estar vinculadas a promociones de fidelización que aumentan la calificación promedio del cliente.

4. Instrucciones para Ejecutar
Para visualizar los resultados correctamente en Google Colab, sigue estos pasos:
1. Carga de Archivos: importa el archivo https://github.com/loop-04/Challenge-Python-para-DataScience.git
2. Preparación del Entorno: Asegúrate de ejecutar la primera celda que contiene las librerías necesarias (pandas, matplotlib, seaborn).
3. Ejecución: Corre las celdas de forma secuencial (puedes usar el comando Ctrl + F9 para ejecutar todo el notebook automáticamente).
4. Visualización: Los gráficos y tablas de resumen aparecerán inmediatamente debajo de cada bloque de código de análisis.
