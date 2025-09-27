# TallerRabbitMQ

Para iniciar el taller se crean los archivos "docker-compose.yml" "send.py" y "receive.py"

como primer paso, levantamos el docker-compose con rabbitMQ, como se ve en la imagen

![compose](https://github.com/julianceron64/TallerRabbitMQ/blob/main/Imagenes/compose.png?raw=true)

como paso opcional podemos comprobar que todo esta funcionando correctamente entrando al dashboard en el localhost:15672, entrando al dashboard de rabbit, tal como vemos
en la imagen
![rabbit](https://github.com/julianceron64/TallerRabbitMQ/blob/main/Imagenes/rabbit.png?raw=true)

ahora ejecutamos el send.js, para enviar el mensaje:

![send](https://github.com/julianceron64/TallerRabbitMQ/blob/main/Imagenes/send.png?raw=true)

y por ultimo ejecutamos el receive.js, y, vemos tanto que el mensaje es recibido como que el receive se mantiene corriendo, esperando recibir mas mensajes

![receive](https://github.com/julianceron64/TallerRabbitMQ/blob/main/Imagenes/receive.png?raw=true)
