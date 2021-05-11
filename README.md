# Neostella

# English-----------

This is a test performed for the technical test at NeoStella company. The wizard is non-transactional and also does not use an orchestrator queue.

The result is an Excel file with the specified search and the sum of total values for each invoice on the date specified in the config. This file will be stored in the path: C: \ Users \ Environment.SourceName \ Temp \ Results.xlsx. Given the case in which the date is not among the invoices, then a general summation will be made.

The configuration file is located in the Data folder of the bot, where routes, paths, credentials, type of client, dates, among others, can be changed, etc.
Each execution performed the wizard will clean the aforementioned folder.

Note: If the orchestrator is used, the credentials must be stored there or at least be encrypted so they are not exposed in the config file.

# Spanish--------------

Esta es una prueba realizada para el test técnico en la compañía NeoStella. El asistente no es transaccional y además no utiliza cola de orquestador. 

El resultado es un archivo de Excel con la busqueda especificada y con la sumatoria de valores totales para cada factura en la fecha especificada en el config. Dicho archivo quedará almacenado en la ruta: C:\Users\Environment.SourceName\Temp\Results.xlsx. Dado el caso en el que la fecha no se encuentre entre las facturas, entonces se hará una sumatoría general. 

El archivo de configuraciones se encuentra en la carpeta Data del bot, allí podran ser cambiadas rutas, paths, credenciales, tipo de cliente, Fechas, entre otros, etc. 
Cada ejecución que se realize el asistente hará limpieza de la carpeta mencionada anteriormente. 

Nota: De ser usado el orquestador, las credenciales deben estar almacenadas allí o por lo menos ser cifradas para que no esten expuestas en el archivo config.


