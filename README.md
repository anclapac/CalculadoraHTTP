# CalculadoraHTTP

En la URL http://malamen.dit.upm.es/calc hay desplegada una calculadora HTTP que sirve para sumar, restar, dividir y multiplicar dos números, obteniendo el resultado en formato JSON.

Para usar esta calculadora debe enviarse una petición HTTP de tipo POST a la URL anterior, y pasar en el cuerpo (body) los dos números y el operador que se quieran aplicar.

Hay muchas formas de realizar esa consulta: desde utilizar código Javascript en cliente, hasta el uso de herramientas específicas como cURL.
Sin embargo, todas ellas usan el protocolo HTTP por debajo.

En esta práctica, elaboraremos varias peticiones HTTP de manera manual que enviaremos al servidor, y comprobaremos que la respuesta obtenida es la esperada.
