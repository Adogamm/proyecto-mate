# Conceptos de WEB services.

¿Qué son los WEB service? 

Un web service facilita un servicio a través de Internet: se trata de una interfaz mediante la que dos máquinas (o aplicaciones) se comunican entre sí. Esta tecnología se caracteriza por estos dos rasgos:

  1. Multiplataforma: cliente y servidor no tienen por qué contar con la misma configuración para comunicarse. El servicio web se encarga de hacerlo posible.
  2. Distribuida: por lo general, un servicio web no está disponible para un único cliente, sino que son diferentes los que acceden a él a través de Internet.

Cuando se utiliza un web service, un cliente manda una solicitud a un servidor, desencadenando una acción por parte de este. Posteriormente, el servidor devuelve una respuesta al cliente.

REST se caracteriza por no tener estado. Es decir, el servidor no es capaz de recordar el estado de la anterior solicitud REST que pudo, o no, hacer un cliente. Por ello, el cliente tiene que enviar en cada solicitud todo el estado de su sesión, lo que se suele hacer mediante un token que le «ayude a recordar» al servidor.

REST tiene a simplificar las cosas y en esa misma línea se suele usar un lenguaje diferente para representación de los datos, el lenguaje JSON. Hoy REST y JSON se han convertido en la opción más sencilla y por tanto más recomendable para implementar un servicio web.

XML Vs JSON

XML está basado en etiquetas, como HTML. Es más tradicional pero también es un lenguaje más avanzado, que presenta diversas utilidades para su extensión, validación de la información y sintaxis de los datos, etc.

JSON es un lenguaje más nuevo, basado en sintaxis Javascript. Generalmente, es más ligero y requiere mucho mejor carga del servidor para su procesamiento.
