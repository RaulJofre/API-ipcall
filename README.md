# API-ipcall

api.ipcall Es una simple api JSON para el uso de sistema de envio de mensajes de chat.


### Propiedades
Todas las servicios api tiene la una estructura requerida principal y una asociada al tipo de servicio solicitado. Las peticiones pueden ser por GET o por POST

### Consultar [POST]

+ Attributes
    + tipo_documento (required, string) - Tipo de documento.
    + numero_documento (required, string) - Número de DNI del postulante.
    + correo (optional, string) - correo.
    

url: http://api-01.ipcall.com.ar

#### Parametros

controller: Controlador de servicio.
do: Acción de la petición.
contactoid

http://api.ipcall.com.ar/?controller=chat&do=getMensajes&idusuario=67&idlobby=79&contactoid=5491123224710@c.us&token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpcCI6IjE4MS4xMTguNjUuMTUwIiwiaWR1c3VhcmlvIjoiNjcifQ.Bp9GFZazrrjuDmO7LXySjsdTXOZ2aXGwfzFdY0hhu5w
