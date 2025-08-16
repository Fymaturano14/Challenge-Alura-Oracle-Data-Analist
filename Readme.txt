<h1 align="center">📊 Análisis de Ventas</h1>

<p align="center">
  <em>Exploración y análisis de datos de ventas de cuatro tiendas diferentes.</em>
</p>

---

<h2>📥 Carga y Combinación de Datos</h2>

<ul>
  <li>Los datos provienen de <b>cuatro archivos CSV</b> (<code>tienda_1.csv</code>, <code>tienda_2.csv</code>, <code>tienda_3.csv</code>, <code>tienda_4.csv</code>).</li>
  <li>Se añade una columna <b><code>Tienda</code></b> a cada DataFrame para identificar su origen.</li>
  <li>Todos los datos se combinan en un único DataFrame: <b><code>df_combined</code></b>.</li>
</ul>

---

<h2>🧹 Limpieza y Preparación de Datos</h2>

<ul>
  <li>Conversión de <code>Fecha de Compra</code> a formato de fecha y hora.</li>
  <li>Creación de la columna <b><code>Total de la Compra</code></b> = Precio + Costo de envío.</li>
</ul>

---

<h2>🔎 Análisis Realizado</h2>

<ul>
  <li>✔️ <b>Análisis Temporal</b> → Ventas por año y mes.</li>
  <li>✔️ <b>Categoría de Producto</b> → Ventas, precio promedio y costo de envío.</li>
  <li>✔️ <b>Ubicación de Compra</b> → Ventas y comparativa de costos.</li>
  <li>✔️ <b>Métodos de Pago y Cuotas</b> → Influencia en las ventas.</li>
  <li>✔️ <b>Calificaciones</b> → Distribución y relación con categorías y vendedores.</li>
  <li>✔️ <b>Vendedores</b> → Ranking de ventas totales.</li>
  <li>✔️ <b>Productos</b> → Más vendidos y menos vendidos.</li>
  <li>✔️ <b>Coste de Envío Promedio</b> → Comparación entre tiendas.</li>
</ul>
