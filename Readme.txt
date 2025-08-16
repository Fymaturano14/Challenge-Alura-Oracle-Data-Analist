Análisis de Ventas
Este notebook analiza los datos de ventas de cuatro tiendas diferentes.

Carga y Combinación de Datos
Los datos de cuatro archivos CSV independientes (que representan tienda_1, tienda_2, tienda_3 y tienda_4) se cargan en DataFrames de Pandas. Se añade una columna "Tienda" a cada DataFrame para identificar la tienda de origen antes de concatenarlos en un único DataFrame llamado df_combined.

Limpieza y Preparación de Datos
La columna "Fecha de Compra" se convierte a formato de fecha y hora para el análisis temporal.
Se crea una columna "Total de la Compra" sumando las columnas "Precio" y "Costo de envío".
Análisis Realizado
Se realizaron los siguientes análisis:

Análisis Temporal: Análisis de las tendencias de ventas a lo largo del tiempo (por año y mes).
Análisis de Categoría de Producto: Examinando las ventas, el precio promedio y el costo promedio de envío por categoría de producto.
Análisis de Ubicación: Análisis de las ventas, el precio promedio y el costo promedio de envío por ubicación de compra. Análisis de métodos de pago y cuotas: Investigación de la influencia de los métodos de pago y el número de cuotas en las ventas.
Análisis de calificaciones: Análisis de la distribución de las calificaciones de los productos y su relación con las categorías de productos y los vendedores.
Análisis de vendedores: Análisis de las ventas totales por vendedor.
Análisis del rendimiento del producto: Identificación de los productos más y menos vendidos en función de las ventas totales.
Coste de envío promedio por tienda: Cálculo del coste de envío promedio para cada tienda.
Hallazgos clave (Ejemplo: puede completar este campo según los resultados de su análisis)
Las ventas totales varían significativamente entre las diferentes categorías de productos, siendo [mencione las categorías de alto rendimiento] y [mencione las categorías de bajo rendimiento] las de mayor y menor rendimiento, respectivamente.
[Mencione cualquier tendencia temporal interesante observada en las ventas].
[Mencione cualquier dato sobre las ventas por ubicación].
[Mencione cualquier dato sobre los métodos de pago y las cuotas].
[Mencione cualquier observación sobre las calificaciones de los clientes].
[Mencione cualquier dato sobre el rendimiento del vendedor]. El producto más vendido es [mencione el producto más vendido] y el menos vendido es [mencione el producto menos vendido].
El costo promedio de envío varía según la tienda, con [mencione las tiendas con costos promedio de envío altos/bajos].
Cómo ejecutar el notebook
Asegúrese de tener instalado Jupyter Notebook o Google Colab.
Abra el archivo del notebook en su entorno.
Ejecute las celdas secuencialmente para reproducir el análisis.
Dependencias
pandas