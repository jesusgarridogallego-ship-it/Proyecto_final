Football Player Performance Analysis
Descripción

Este proyecto analiza el rendimiento ofensivo de jugadores de fútbol en las principales ligas europeas mediante técnicas de análisis de datos y visualización en Power BI.

El objetivo es identificar jugadores con mayor impacto ofensivo a partir de métricas como goles, asistencias y contribución total (G+A), incluyendo métricas normalizadas por 90 minutos.

Dataset

Datos de eventos de partidos de fútbol:

Jugadores
Partidos
Eventos
Goles
Asistencias
Minutos jugados

Periodo: 2011–2016

Estructura del proyecto
/data
    final_dataset.csv
    player_stats.csv

/notebooks
    data_cleaning.ipynb

/powerbi
    Dashboard_final.pbix
Proceso de análisis
1. Limpieza y transformación (Python)

Se utilizó Pandas para:

Limpiar datos
Eliminar nulos en player_id
Transformar tipos
Agregar estadísticas por jugador

2. Modelado de datos

Se crearon dos tablas:

final_dataset → nivel evento
player_stats → nivel jugador

Se evitó mezclar granularidades para garantizar consistencia.

3. Visualización (Power BI)

Se desarrolló un dashboard con:

Rankings de jugadores
Métricas agregadas
Gráficos de dispersión
Segmentadores interactivos

Métricas

Goles
Asistencias
G+A
Goles por 90
Asistencias por 90
G+A por 90

Cómo reproducir el proyecto

1. Ejecutar el notebook:

data_cleaning.ipynb

2. Se generan:

final_dataset.csv
player_stats.csv

3. Abrir Power BI:

Dashboard_final.pbix

Insights principales:

Messi destaca como jugador más completo
No siempre el máximo goleador es el más influyente
Existen perfiles diferenciados (finalizador vs creador)

Limitaciones:

Datos agregados sin segmentación por contexto
Posibles inconsistencias en identificadores
No se incluyen métricas avanzadas (xG, xA)
