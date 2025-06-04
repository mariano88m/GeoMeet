# GeoMeet

Es un geolocalizador diseñado para identificar coincidencias entre abonados que registraron impactos en antenas (celdas) ubicadas a menos de 2 kilómetros de distancia y con una diferencia temporal no mayor a 5 minutos.

Este geolocalizador permite detectar si hubo abonados presentes en una misma ubicación en un mismo intervalo de tiempo.

El sistema funciona a partir de la carga de un archivo .csv, generado desde pgAdmin utilizando la base de datos del sistema de cruces. Este archivo se obtiene mediante la ejecución de una consulta SQL contenida en el archivo query.txt.

![imagen](https://github.com/user-attachments/assets/e2633750-2e17-4794-bcc3-b5627c71c3b1)

Esto permite filtrar por los abonados que figuran en el csv.



