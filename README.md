## Análisis de E-commerce — Olist (Brasil)

## Descripción
Análisis end-to-end del dataset público de Olist con +100k órdenes reales.
Incluye limpieza de datos, análisis exploratorio, segmentación de clientes y dashboard ejecutivo.

## Preguntas de negocio
- ¿Cuáles son las categorías más rentables?
- ¿Cómo varía la satisfacción del cliente según el tiempo de entrega?
- ¿Qué estados de Brasil concentran más ventas?
- ¿Qué perfil tienen los clientes con mayor valor?

## Herramientas utilizadas
- Python (pandas, matplotlib, seaborn)
- SQL (SQLite)
- Power BI
- GitHub

## Estructura del proyecto
- notebooks/ → Exploración y análisis en Python
- data/      → Muestra del dataset
- queries/   → Consultas SQL
- dashboard/ → Capturas del dashboard en Power BI

## Dataset
[Olist Brazilian E-commerce - Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Hallazgos principales

1. **Crecimiento sostenido:** Las ventas crecieron durante todo 2017, con un pico en noviembre (~$1.2M) probablemente por Black Friday.
2. **Categoría líder:** Health & Beauty es la categoría más rentable con ~$1.45M en ingresos totales.
3. **Concentración geográfica:** São Paulo concentra el triple de ventas que Rio de Janeiro.
4. **Entrega vs satisfacción:** Los pedidos con 1 estrella tardaron 19 días en promedio vs 10 días los de 5 estrellas.
5. **Segmentación RFM:** El 34% de los clientes son Potenciales o Leales. Hay 13.978 clientes en riesgo recuperables.

## Finalizado
