# ASIG00202---Programacion-Avanzada---TP-Segundo-Modulo

Trabajo Practico del Segundo Modulo de programacion avanzada de UNICABA. 

############################################################

**Entrega del Alumno: Gastón Ezequiel Conessa** 

**Hice el trabajo SOLO, no en grupo** 

***Pertenezco al grupo Asado Analytics***

############################################################

**Dataset seleccionado**

Use un dataset publico de CABA, donde se detallan las farmacias de caba.

URL: https://data.buenosaires.gob.ar/dataset/farmacias 

El archivo a utilizar se llama ***farmacias.xlxs***

############################################################

**BD seleccionada**

Es la primera vez en mi vida que ustilizo una BD con Python. 

Al desarrollar todo en Colab implemente la BD **SQLlite3** que segun investigue tiene una facil implementacion para mi nivel de programacion.

############################################################

**Pasos para ejecutar**

Entrego un Colab por pasos segun vimos en clase para poder ir ejecutando cada paso.

Para corra, es necesario importar el archivo **farmacias.xlxs** al colab para que importe en la base de datos del sqllite3 y desde ahi pueda correr todos los graficos

***Detallo cada paso del colab***

1) SETUP --> Aca importo las librerias a utilizar y utilizo una funcion para cargar el achivo farmacias.xlxs a utilizar
2) CREACION BD --> Aca creo la conexion a la BD del sqllite3 y subo el excel importado a dicha BD
3) CALCULO KPI --> partiendo de la tabla en BD, arme un Qery y use esos datos para armar 3 KPIS. Los visualizo en este paso para ver como quedar
4) GRAFICO DE BARRAS --> partiendo de la tabla en BD, arme un Qery y use esos datos para armar un grafico de Barras de farmacias por Comuna. Lo visualizo para ver como se ve.
5) MAPA BARRIOS DE CABA --> Partiendo de la tabla en BD, arme un Qery y use esos datos para armar un mapa con la cantidad de farmacias por Barrio. Lo visualizo para ve como funciona
6) MAPA GEORGRAFICO --> Partiendeo de la tabla en BD, arme un Qery y use esos datos para armar un mapa con la ubicacion de cada farmacia en CABA. Lo visualizo para ve como funciona
7) DASHBOARD FINAL --> Uno todos los componentes del punto 3 al 7 para armar el Dashboar solicitado. Uso la funcion DASHBOARD vista en clase

