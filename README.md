# Portafolio de Análisis de Datos

Bienvenido a mi repositorio de proyectos de análisis de datos, procesamiento con Pandas y visualización.

## Proyectos
# Proyecto 1: Análisis Exploratorio de Datos (EDA) y Limpieza de Ventas E-commerce

## Resumen Ejecutivo
Este proyecto realiza un análisis exploratorio y de limpieza de datos sobre transacciones de comercio electrónico. Se abordaron inconsistencias en la captura de datos y se identificaron los patrones de compra principales por categoría de producto y métodos de pago.

## Metodología y Limpieza de Datos
- **Tratamiento de Nulos:** Imputación de precios vacíos utilizando la mediana condicional agrupada por categoría.
- **Filtrado de Anomalías:** Eliminación de registros inconsistentes con cantidades negativas en compras.
- **Estandarización:** Conversión de fechas a tipo `datetime` y casteo de identificadores de cliente.
- **Feature Engineering:** Cálculo de la variable `Venta_Total` (Precio * Cantidad).

## Hallazgos Clave (Key Insights)
- **Ropa y Electrónica** representan los principales motores de ingresos de la tienda, sumando más de $200,000 en ventas combinadas.
- **Tarjeta de Crédito** es la opción de pago con mayor adopción por parte de los clientes, duplicando las transacciones realizadas mediante PayPal.

## Visualizaciones Exportadas
Las visualizaciones generadas se guardaron en la carpeta `reports/`:
- `eda_ventas_categoria_pago.png`: Comparativa de ingresos por categoría y volumen por método de pago.

## Tecnologías Utilizadas
- Python 3
- Pandas & NumPy
- Matplotlib & Seaborn