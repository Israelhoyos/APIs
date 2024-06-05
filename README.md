# APIs


Las APIs (Application Programming Interfaces, o Interfaces de Programación de Aplicaciones) son conjuntos de definiciones y protocolos que permiten que diferentes sistemas de software se comuniquen entre sí. Las APIs facilitan la integración y la interacción entre aplicaciones, servicios y plataformas, proporcionando métodos definidos para solicitar y enviar datos.

## Componentes Principales de una API
* Endpoints:

Puntos específicos de una API donde se pueden acceder a los recursos. Cada endpoint tiene una URL única que identifica el recurso y la operación a realizar.
* Métodos HTTP: Las APIs suelen usar métodos HTTP para realizar operaciones CRUD (Create, Read, Update, Delete). Los métodos más comunes son:
- GET: Recuperar datos de un servidor.
- POST: Enviar datos al servidor para crear un nuevo recurso.
** PUT: Actualizar un recurso existente.
**DELETE**: Eliminar un recurso.

* Solicitudes y Respuestas:

Solicitud (Request): Incluye la URL del endpoint, el método HTTP, y puede contener encabezados y un cuerpo de mensaje con datos.
Respuesta (Response): El servidor devuelve una respuesta que incluye un código de estado HTTP, encabezados y, a menudo, un cuerpo de mensaje con los datos solicitados o información sobre la operación realizada.
Códigos de Estado HTTP:

Los códigos de estado indican el resultado de la solicitud. Algunos ejemplos comunes son:
200 OK: La solicitud fue exitosa.
201 Created: Un nuevo recurso fue creado.
400 Bad Request: La solicitud es incorrecta.
401 Unauthorized: La autenticación es necesaria.
404 Not Found: El recurso no fue encontrado.
500 Internal Server Error: Error en el servidor.
Autenticación y Autorización:

Las APIs pueden requerir autenticación (verificar la identidad del usuario) y autorización (verificar los permisos del usuario) mediante tokens, claves API, OAuth, etc.
Ejemplos de Uso de APIs
Integración de Servicios:

Conectar diferentes servicios web, como integrar un sistema de pago con una tienda en línea.
Acceso a Datos Externos:

Obtener datos de terceros, como obtener información meteorológica de una API de clima.
Automatización de Procesos:

Automatizar tareas como enviar correos electrónicos a través de una API de servicios de correo.
Desarrollo de Aplicaciones:

Utilizar APIs para integrar funcionalidades como mapas (Google Maps API) o autenticación (OAuth).
