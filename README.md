
Análisis del Teatro Musical en España (2010–2026)
Objetivo

Proyecto de análisis de datos sobre la evolución del teatro musical en España (2010–2026) orientado a identificar:

patrones de producción

concentración empresarial

dinámicas territoriales

explotación en gira

características artísticas del sector

Combina análisis cuantitativo, conocimiento sectorial y visualización en Power BI con foco en la toma de decisiones culturales y de negocio.

Dashboards en Power BI

El proyecto incluye dashboards interactivos centrados en:

Evolución del teatro musical (2010–2025)

Actividad de productoras

Pricing del teatro musical (2026)

Inicio geográfico de las producciones

Perfil artístico y estructural

Explotación y comportamiento de giras

Capturas y exportaciones disponibles en:

/dashboards/

Datasets finales utilizados

El modelo analítico se apoya en tres tablas principales:

Dataset	Contenido	Uso
maestro_musicales_final.csv	Obras, productoras, teatros, género, origen, años, gira	Estructura sectorial
precios_musicales_limpio_definitivo.csv	Precios anunciados en 2026	Pricing
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

Duración media y formatos dominantes.

Posicionamiento de precios.

Tecnologías

Python (Pandas, NumPy)

Jupyter Notebook

Matplotlib, Seaborn

Power BI

Git & GitHub

Principales insights

Predominio de franquicias (~73%).

Alta concentración empresarial.

Madrid como principal polo inicial.

Más del 50% de títulos en gira.

Duración media estabilizada (~138 minutos).

Estructura del repositorio
/
├─ data_raw/          # Datos originales
├─ data_interim/      # Versiones intermedias tras limpieza
├─ data_processed/    # Datasets finales para análisis y BI
├─ docs/              # Exportaciones finales y PDF del proyecto
├─ notebooks_eda/     # Exploratory Data Analysis
├─ notebooks_etl/     # Pipelines de preparación
├─ dashboards/        # Capturas / exportaciones Power BI
├─ .gitignore
└─ README.md

Cómo reproducir el proyecto:

Clonar el repositorio.

Ejecutar los notebooks de /notebooks_etl/.

Revisar análisis en /notebooks_eda/.

Conectar Power BI a los CSV de /data_processed/.

Explorar dashboards exportados en /dashboards/ o /docs/.

Documentación adicional

El PDF final del proyecto se encuentra en:

/docs/


Incluye resumen ejecutivo, storytelling sectorial y visualizaciones clave.

Estado del proyecto

✔ ETL documentado
✔ Modelo relacional con tres datasets
✔ Dashboards Power BI
✔ Storytelling sectorial

Posibles ampliaciones futuras:

Series temporales predictivas

Modelos de pricing

Análisis de supervivencia en cartel

Segmentación territorial avanzada

Casos de estudio por producción