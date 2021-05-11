# Neostella

Esta es una prueba realizada para el test tecnico en la compañia NeoStella. El asistente no utiliza cola de orquestador y tampoco es transaccional. 

El resultado es un archivo de Excel con la busqueda especificada y con la sumatoria de valores totales para cada factura en la fecha especificada en el config. Dicho archivo quedará almacenado en la ruta: C:\Users\{0}\Temp\Results.xlsx. Dado el caso en el que la fecha no se encuentre entre las facturas, entonces se hará una sumatoría general. 

El archivo de configuraciones se encuentra en la carpeta Data del bot, allí podran ser cambiadas rutas, paths, credenciales, etc. 

Nota: De ser usado el orquestador, las credenciales deben estar almacenadas allí o por lo menos ser cifradas para que no esten expuestas en el archivo config.

Cada ejecución que se realize el asistente hará limpieza de la carpeta mencionada anteriormente. 
