Proyecto Individual 2 - Data Analyst 🚀

Introducción

El presente proyecto analiza el sector de telecomunicaciones en Argentina, con especial énfasis en el acceso a internet, utilizando datos provenientes de ENACOM y otras fuentes complementarias. A través de un Análisis Exploratorio de Datos (EDA) en Python y visualizaciones interactivas en Power BI, se busca generar información valiosa que permita identificar oportunidades de inversión y mejoras.

Objetivo

El objetivo principal es analizar y visualizar el comportamiento del acceso a internet a nivel nacional, explorando tendencias, crecimiento y brechas existentes. Este análisis permitirá a la empresa identificar:

Áreas de oportunidad para mejorar el acceso a internet. Provincias clave para inversión en tecnologías de telecomunicaciones. Tendencias de consumo y adopción de nuevas tecnologías. Directorios y Archivos del Repositorio 📂 Datos/: Archivos de datos en su forma original.

Internet.csv: Datos sobre accesos a internet por provincia. mapa_conectividad.csv: Información geográfica y conectividad. Telefonia_movil.csv: Estadísticas sobre telefonía móvil. Datos_Procesados/: Archivos procesados listos para Power BI.

internet_procesado.csv: Datos limpios y enriquecidos. penetracion_hogares.csv: Porcentaje de penetración por hogares. EDA/: Archivo Jupyter Notebook para el análisis exploratorio.

EDA.ipynb: Limpieza, transformación y análisis visual inicial. PowerBI/: Reporte interactivo en Power BI.

dashboard.pbix: Dashboard dinámico con filtros y KPIs. Proyecto_Individual_2/: Entorno virtual y dependencias.

requirements.txt: Lista de librerías utilizadas.

Etapas del Proyecto 🛠️

1️⃣ Estudio de Datos y EDA

Fuentes de datos: Los datasets se obtuvieron desde la plataforma de ENACOM y otras fuentes como el Banco Mundial. Limpieza de datos: Eliminación de duplicados, tratamiento de valores faltantes y análisis de outliers. Exploración gráfica: Visualización inicial de patrones con Matplotlib y Seaborn.

2️⃣ Proceso ETL (Extract, Transform, Load)

Extracción: Carga de datasets en formato .csv. Transformación: Normalización, unificación de formatos y cálculo de variables adicionales (e.g., tasas de crecimiento). Carga: Generación de datasets procesados para su análisis en Power BI.

3️⃣ Construcción del Dashboard

La construcción del dashboard se centró en identificar y visualizar las tecnologías, velocidades y el acceso a internet en cada provincia de Argentina. Se analizaron los siguientes aspectos clave:

Visualización de Tecnologías y Accesos: Se mostraron los totales de ingresos y accesos por tipo de tecnología en cada provincia. Velocidades y Crecimiento Temporal: Se visualizó el consumo de velocidades, destacando el crecimiento de las tecnologías entre 2014-2024. Accesos en Hogares y Población: Se observaron los accesos a BAF en hogares y su distribución poblacional.

Conclusiones

Tras un exhaustivo EDA, ETL y la creación de gráficos en Power BI, los resultados muestran que en 2023, Argentina generó ingresos totales de $520 millones. Buenos Aires, Capital Federal, Santa Fe y Córdoba lideran en consumo de BAF, especialmente con tecnologías de Cable Módem y Fibra Óptica, mientras que ADSL muestra una disminución.

Accesos en Hogares: Si bien ambos, hogares y población, están en crecimiento, los accesos en hogares son más significativos y deben ser priorizados. Las provincias fuera de estas principales aún presentan una baja penetración tecnológica y de velocidad, lo que resalta la necesidad de una distribución más equitativa en el acceso a internet a nivel nacional.
