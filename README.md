# ComandoSSH

Este proyecto en Java permite realizar conexiones SSH a un servidor remoto y ejecutar comandos en él. Utiliza la biblioteca JSch para gestionar la conexión SSH y ejecutar comandos de manera remota.

## Requisitos

- **Java 8 o superior**.
- **JSch Library**: La biblioteca `JSch` es necesaria para realizar las conexiones SSH. Puedes descargarla desde su [página oficial](http://www.jcraft.com/jsch/) o agregarla a tu proyecto mediante Maven o Gradle.

Descripción
El código consiste en una clase principal (ComandoSSH) que se conecta a un servidor remoto a través de SSH usando el usuario y la contraseña proporcionados. Luego ejecuta un comando en el servidor, captura su salida y la muestra en la consola.

El proceso de conexión y ejecución de comandos está encapsulado en la clase SSHConnector.
