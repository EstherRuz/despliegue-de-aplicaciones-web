# despliegue-de-aplicaciones-web
#### 3.Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los datos sensibles que se envían.
Al poner la contraseña y inspeccionar los tokens sale lo siguiente:

anchor: 

logintoken: EwNXBrvOORCKF0R6QSYaUwbvIylkCiHK

username: eruz@campus.eug.es

password: dbgh

Los datos sensibles son aquellos protegidos por RGPD, es decir, datos personales.

#### 4.¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP, UDP, e IP?
El http se recive en el puerto 80, en canvio el https en el 443.
El protocolo http se encuentra en la capa 7 que es la de aplicación, los protocolos TCP i UDP en la capa 4, la capa de tranporte. El IP en la capa 3 la network.

#### 5.¿Cuál es el significado de la siguiente respuesta de un servidor?
##### HTTP/1.1 302 Found
El código de estado de respuesta HTTP 302 encontrado es una forma común de realizar la redirección de URL.

#### 6.Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.

72	20.604469	192.168.1.69	80.58.61.254	DNS	74	Standard query 0x988d A www.google.com

Mi direcció ip:192.168.1.69, dirección IP del servidor: 80.58.61.254.
Al acceden desde el navegador a la direccion ip da un timeout.
