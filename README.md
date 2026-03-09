Football Player Performance Analysis

Descripción del proyecto
Este proyecto analiza el rendimiento ofensivo de jugadores de fútbol en las principales ligas europeas utilizando técnicas de análisis de datos y visualización interactiva en Power BI.

El objetivo es identificar a los jugadores con mayor impacto ofensivo a partir de métricas como goles, asistencias y contribución total al gol.

Dataset
El proyecto utiliza datos de eventos de partidos de fútbol correspondientes a las principales ligas europeas.

El dataset incluye información de:
jugadores
partidos
eventos de juego
goles
asistencias
minutos jugados

Periodo analizado:
2011-2016

Herramientas utilizadas
Python
Pandas
Power BI

Proceso de análisis

1. Limpieza y preparación de datos
Los datasets originales se procesaron utilizando Python y Pandas.

Se realizaron las siguientes tareas:
limpieza de valores nulos
transformación de tipos de datos
agregación de estadísticas por jugador
creación de datasets finales para análisis

2. Creación del dataset final
Se generaron dos tablas principales:
final_dataset
Tabla de eventos de partido utilizada para análisis detallado.
player_stats
Tabla agregada por jugador con:
goles
asistencias
minutos jugados

3. Modelado de datos en Power BI
Se cargaron los datasets en Power BI y se creó el modelo de datos.

Se realizaron:
relaciones entre tablas
creación de medidas DAX
cálculo de métricas agregadas

4. Métricas utilizadas

Principales métricas analizadas:
Goles
Número total de goles anotados por jugador.
Asistencias
Número total de asistencias realizadas por jugador.
Goles + Asistencias (G+A)
Contribución ofensiva total del jugador.

5. Visualizaciones del dashboard

El dashboard incluye:
ranking de goleadores
ranking de asistentes
ranking de generadores de gol (G+A)
gráfico de dispersión goles vs asistencias
gráfico combinado de goles y asistencias
tarjetas de métricas globales
segmentador de jugadores

Resultados
El análisis permite identificar los jugadores con mayor impacto ofensivo y analizar diferentes perfiles de jugadores en función de su capacidad goleadora y creativa.
