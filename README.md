# webxocket

Aquí se trabajó con websockets, que viene siendo una especie de capa de más alto nivel que opera sobre el protocolo HTTP para emular el modelo cliente-servidor donde las conexiones son persistentes.

Se utilizó un framework para node que "sobrecarga" el protocolo de websockets por lo que sirve mientras el cliente se ejecute en algún dispositivo con capacidades no tan limitadas, por lo que serviría para simular una comunicación entre un dispositivo HTTP digamos puro con otro que sea vía websockets, pero en un caso real pues no.

También se encuentra montado en Heroku, el enlace es: https://webxocket.herokuapp.com/

Se puede ejecutar desde el navegador pero para observar su funcionamiento requiere habilitar la ventana de ejecución/desarrollador.
