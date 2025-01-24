Esto es un archivo de configuración para un servidor web Nginx, que especifica cómo manejar las solicitudes HTTP.

#Función general
Este archivo de configuración actúa como un proxy inverso:

1. Redirige todas las solicitudes del cliente que llegan al puerto 80 hacia un servidor backend en http://localhost:8000.
2. Ajusta encabezados HTTP y tiempos de espera para manejar conexiones largas y solicitudes grandes.
