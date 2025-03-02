# producer-hello-world
Este código en Go implementa un productor de mensajes para RabbitMQ
Este código en Go implementa un productor de mensajes para RabbitMQ. Se encarga de:

Conectarse a RabbitMQ usando las credenciales y dirección especificadas.
Abrir un canal de comunicación con el servidor de mensajes.
Declarar una cola llamada "hello".
Publicar un mensaje ("Hello World!") en la cola con un timeout de 5 segundos.
Manejar errores con la función failOnError.
Básicamente, envía un mensaje a RabbitMQ en una cola específica.
