 **PROYECTO ANALISIS DATA SCIENCE - CODERHOUSE**

### "Reconomiento de patrones y tendencias en los torneos locales Argentinos (2015/2022)"

<br><br>
Este proyecto parte de un analisis de un set de datos que contiene datos de los torneos argentinos de futbol desde el año 2015 hasta el año 2022. Contiene informacion detallada de 2821 partidos de primera division.
<br>

El dataset fue obtenido de la pagina:
<br>

https://www.kaggle.com/datasets/camussonif/argentinian-football-results-20152022?select=afa_2015_2022_spa.csv

<br>

De acuerdo al creador del dataset, la informacion obtenida y plasmada en el dataset fue obtenida de las webs:
<br>

[PROMIEDOS](https://www.promiedos.com.ar/ )	
 
[TRANSFERMARKT](https://www.transfermarkt.com/ )

[ODDSPORTAL](https://www.oddsportal.com/)

<br><br>



##  **DESCRIPCION DEL DATASET**
<br>
El dataframe posee en su mayoria variables cuantitativas que analizan en profundidad las situaciones dadas en cada uno de los partidos de la liga. Es un dataset que consta de 34 columnas.

Para mejor compresion a primera vista, la primer columna indica el torneo o campeonato en el cual se disputo el partido, la segunda el equipo local, la tercera el equipo visitante y las restantes indican las diferentes situaciones dentro del partido indicando si fueron situaciones para el local o para el visitante.

En especial voy a destacar para el analisis: 'posesion_local','posesion_visitante', 'goles_local', 'goles_visitante', 'tiros_arco_local', 'tiros_arco_visitante'

Variables cualitativas que van a ser utilizadas: 'equipo_local', 'equipo_visitante', 'torneo'.

Se aclara que en el dataset original, los datos de posesion y tiros al arco se encuentran detallados desde el torneo 2017/2018. Razon por la cual durante el analisis exploratorio de datos se filtraran los mismos partiendo desde el torneo en donde se comienzan a detallar.
<br>
<br>
<br>




## **DEFINICION DE OBJETIVO, CONTEXTO:**
<br>
El objetivo del analisis es mediante la relacion entre las diferentes variables llegar a conclusiones que puedan ayudar en el aspecto directivo a desarrollar estrategias futbolisticas a los fines de lograr mejores resultados deportivos.

El analisis puede ayudar a todos los equipos tecnicos a identificar las variables que tienen el mayor impacto en el resultado y asi tener mejor informacion para desarrollar una estrategia ya sea de juego, para futuras compras de jugadores, etc. 

Quizas las variables de este analisis, relacionando posesion, tiros al arco y cantidad de goles resulten algo obvias para los conocedores futboleros..., o quizas tengamos sorpresas.
<br>
<br>
<br>



