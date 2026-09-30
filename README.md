# Dashboard de Ventas - Power BI

## 🎯 Objetivo
Construir un dashboard interactivo en Power BI que permita visualizar el
comportamiento de ventas de una empresa de ropa a nivel nacional (por región,
categoría, producto y vendedor), para apoyar la toma de decisiones comerciales.

## 📂 Dataset
`ventas_ropa.csv` — dataset simulado de ventas trimestrales (enero-marzo 2024)
de una empresa de confección con operación en varias ciudades de Colombia,
inspirado en procesos reales de análisis comercial.

Columnas:
- `fecha`: fecha de la venta
- `producto`: nombre del producto
- `categoria`: categoría del producto
- `region`: ciudad donde se realizó la venta
- `vendedor`: nombre del vendedor
- `cantidad`: unidades vendidas
- `precio_unitario`: precio por unidad (COP)
- `total_venta`: valor total de la venta (COP)

## 🛠️ Herramientas
- **Power BI Desktop** (versión gratuita)
- **Power BI Service** (para publicar y compartir el dashboard en línea)

## 📊 Visualizaciones incluidas
1. **KPI de ventas totales** — tarjeta con el valor total vendido en el periodo.
2. **Tendencia de ventas mensual** — gráfico de líneas (ventas por mes).
3. **Ventas por región** — gráfico de barras comparando ciudades.
4. **Ventas por categoría de producto** — gráfico de barras.
5. **Ranking de vendedores** — gráfico de barras horizontales.
6. **Filtros interactivos ** — por región, categoría y vendedor.

## 💡 Hallazgos clave
- La categoría Ropa Superior representa el mayor porcentaje de ventas, 
- Cali es la región con mayor crecimiento mes a mes,
- El vendedor Carlos Ruiz es quien tiene mayor porcentaje de ventas general.


## 🔗 Dashboard en línea
https://app.powerbi.com/datahub/datasets/4a9780be-04a4-4484-9dc3-d0d7db3f6191?ctid=fd766edd-8bea-4c99-8672-56d1cabc2706&pbi_source=linkShare

## 🚀 Cómo reproducirlo
1. Abre Power BI Desktop.
2. Importa `ventas_ropa.csv` como origen de datos.
3. Crea las visualizaciones descritas arriba.
4. Publica en Power BI Service para obtener un enlace compartible.
