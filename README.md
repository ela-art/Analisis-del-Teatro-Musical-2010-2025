
Análisis del Teatro Musical en España (2010–2026)
Objetivo

Proyecto de análisis de datos sobre la evolución del teatro musical en España (2010–2026) orientado a identificar patrones de producción, concentración empresarial, dinámicas territoriales, explotación en gira y características artísticas del sector.

Combina análisis cuantitativo, conocimiento sectorial y dashboards en Power BI con foco en toma de decisiones culturales y de negocio.

Dashboards en Power BI

El proyecto incluye dashboards interactivos:

Evolución del teatro musical (2010–2025)

Actividad de productoras

Pricing del teatro musical (2026)

Inicio geográfico de las producciones

Perfil artístico y estructural

Explotación y comportamiento de giras

Capturas disponibles en:

/dashboards/

Datasets finales utilizados

El modelo se basa en tres datasets conectados:

Dataset	Contenido	Uso
maestro_musicales_final.csv	Obras, productoras, teatros, género, origen, años, gira	Estructura sectorial
precio_entradas_musicales_final.csv	Precios anunciados 2026	Pricing
teatro_musical_habitos_2011_2025_limpio.csv	Asistencia y hábitos	Demanda

Ubicación:

/data_processed/

Proceso analítico
ETL y preparación

Integración de fuentes institucionales y sectoriales.

Normalización de nombres y marcas históricas.

Eliminación de duplicados.

Validación de tipos y estados.

Enriquecimiento con género, origen, ciudad y métricas temporales.

Exploración y análisis

Auditoría de calidad.

Análisis territorial.

Estudio de giras y escalabilidad.

Concentración empresarial.

Duración y formatos dominantes.

Tecnologías

Python, Pandas, NumPy

Jupyter Notebook

Matplotlib, Seaborn

Power BI

Git y GitHub

Principales insights

Predominio de franquicias (~73%).

Alta concentración empresarial.

Madrid como principal polo inicial.

Más del 50% de títulos en gira.

Duración media estabilizada (~138 minutos).

Estructura del repositorio
/
├─ data_raw/
├─ data_interim/
├─ data_processed/
├─ notebooks_eda/
├─ notebooks_etl/
├─ dashboards/
├─ .gitignore
└─ README.md

Cómo reproducir el proyecto

Clona el repositorio.

Ejecuta los notebooks de ETL.

Usa los CSV finales en Power BI.

Explora dashboards exportados.

Estado del proyecto

✔ ETL documentado
✔ Modelo con tres datasets
✔ Dashboards Power BI
✔ Storytelling sectorial
⏳ Posibles ampliaciones futuras