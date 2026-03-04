Módulo-5-SO3-CLI Comandos utilizados en Laboratorio Módulo 5 - Sistemas Operativos III

Este repositorio contiene los comandos prácticos con los cuales se desarrollaron las prácticas de el quinto laboratorio de la asignatura Sistemas Operativos III, impartida por el profesor Adrian Alcantara.

En el mismo se desarrollaron los siguientes temas:

Practica 1: Syncronizacion de carpetas con Rsync.
• Crear una carpeta en su servidor primario y dentro crear 100 archivos (con el comando touch).
• Utilizando rsync, copiar el contenido de la carpeta a el servidor remoto.
• Crear un script con el comando de sincronizacion de la carpeta y luego crear un crontab para que se sincronizen cada 1 minuto. cree un archivo en el server primario y luego compruebe que el crontab esta funcionando validando en el servidor secundario si la carpeta se creo.

Practica 2: Instalacion y configuracion del Cluster
• Instalar un Cluster de Alta disponibilidad (Utilizando la herramienta Heartbeat o Pacemaker) con 2 nodos (Servidor) en modo bridge. Configurar una IP flotante para que el cluster funcione utilizando una misma Direccion IP.
• Realizar las pruebas haciendo ping a la ip flotante provista por la solucion de HA y altarnando reinicios entre los servidores, el ping debe de mantenerse.

Practica 3: Cluster de Alta Disponibilidad HTTP
• Configura 2 servidores web (apache/NGINX). En cada uno desplieque una pagina html que especifique que servidor es (server1, Server2).
• Implementar HA en los servidores utilizando KeepAlived. Validar la Alta Disponibilidad del servicio apagando uno de los servidores y y accediendo al servicio de apache a traves de un navegador.

Este es el enlace a la lista de reproduccion en youtube: ↓
https://www.youtube.com/playlist?list=PLpcZGYtY2vZbAxJMAYxP0SjCJnB47vVLQ
