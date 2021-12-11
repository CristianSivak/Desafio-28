# Desafio-28
Programacion Backend - Coderhouse

>> Consigna:

En base al último proyecto entregado, permitir ingresar por línea de comandos el puerto local de escucha del servidor, luego el TWITTER_CLIENT_ID y el TWITTER_CLIENT_SECRET.
Si no se ingresan estos valores, se tomarán valores default presentes en el programa.
El servidor imprimirá en consola el código de salida del proceso de node.js

Asimismo, se dispondrá de una nueva ruta get '/info', que devolverá una vista con los siguientes datos:
- Argumentos de entrada                                       
- Path de ejecución
- Nombre de la plataforma (sistema operativo)                 
- Process id
- Versión de node.js                                          
- Carpeta corriente
- Uso de memoria

Se creará una ruta '/randoms' que permita calcular un cantidad de números aleatorios en el rango del 1 al 1000 especificada por query params, por ej. ..../randoms?cant=20000. Si dicho parámetro no se ingresa, calcular 100000000 números.
El dato devuelto al frontend será un objeto que contendrá como claves los números random generados junto a la cantidad de veces que salió cada uno. Esta ruta no será bloqueante (utilizar el método fork de child process). Comprobar el no bloqueo con una cantidad de 500000000 de randoms.

