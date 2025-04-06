# Practica Comandos de Linux
## 1. Titulo
**Practica No 1**: Comandos Linux en la Terminal
## 2. Tiempo de duración
Se utilizo un tiempo de 3 horas para la realización de esta práctica
## 3. Fundamentos:

En esta práctica, se aprenderán conceptos básicos de manejo de archivos y carpetas, redirección, concatenación, y eliminación en la terminal de Linux. El sistema operativo macOS es basado en Unix y su terminal funciona de manera muy similar a la de Linux, por lo que los mismos comandos son aplicables. En esta ocasión, se utilizó **Warp**, un terminal moderno para macOS, para llevar a cabo las operaciones.

Uno de los comandos más comunes es `mkdir`, que se utiliza para crear directorios. En esta práctica, se utilizará para crear una estructura de carpetas dentro de un proyecto. Además, aprenderemos a crear y manipular archivos con `touch`, `cp`, `mv`, y `echo`. Para la redirección de la salida de comandos a archivos, se usarán los operadores `>`, `>>`, y el comando `cat` para concatenar archivos.

La eliminación de archivos y carpetas se lleva a cabo con los comandos `rm` y `rmdir`.Estos  comandos permiten borrar archivos y carpetas de manera controlada


## 4. Conocimientos previos.
   
Para realizar esta practica es necesario conocer sobre Linux, que se define según **Richardson, D.** (2019) como un sistema operativo (SO) open source que creó Linus Torvalds en 1991. y que gracias a su comunidad internacional de aficionados, hoy podemos encontrarlo en todo tipo de dispositivos, desde sistemas de puntos de venta hasta las supercomputadoras más potentes del mundo. 

Un comando Linux es un programa o utilidad que se ejecuta en la CLI, una consola que interactúa con el sistema a través de textos y procesos. Es similar al Símbolo del sistema en Windows, algunos comandos básicos de Linux como `cd`, `ls`, `cp`, y `mv`, según Sánchez Anguix, V. (2021).

Los comandos de Linux se ejecutan en el terminal pulsando "Enter" al final de la línea. Puedes ejecutar comandos para realizar diversas tareas, desde la instalación de paquetes hasta la gestión de usuarios y la manipulación de archivos.

También se usara la terminal de Warp que es un terminal moderno para desarrolladores, diseñado especialmente para sistemas macOS, afirma Khattab, A., Camp, J., Hunter, C., Murphy, P., Sabharwal, A., & Knightly, E. W. (2008).

## 5. Objetivos a alcanzar
   
- Crear una estructura de carpetas en un directorio.
- Manipular los archivos como crear, copiar, mover, eliminar.
- Aplicar redirección y concatenación de archivos.
- Eliminar archivos y directorios de manera controlada.
- Volcar el historial de comandos a un archivo y presentarlo como parte de la entrega.
  
## 6. Equipo necesario:
  
- Computador con sistema operativo **MacOS:** 13.7.1 
- **Procesador:** 2,3 GHz Intel Core i5
- **Memoria:** 8 GB 
- Conexión a Internet para el material de apoyo
- Terminal en Warp

## 7. Material de apoyo.
   
- **Guía oficial de comandos Linux**: Linux Command Cheat Sheet
- **Documentación de Warp** para macOS.
- **Cheat sheet de Linux**: Para recordar comandos rápidos. 
- Video Material de Apoyo 
  
## 8. Procedimiento

**Paso 1:** Verificación de la ruta completa del directorio actual en la que se esta trabajando, a través de pwd .

Figura 1. Comando **"pwd"**.
![[paso1.png]]

**Paso 2:** Se creo  una carpeta denominada `proyecto_comandos` y dentro de ella, tres subcarpetas denominadas `documentos`, `imagenes` y `scripts`.

Figura 2. Comando **"mkdir"**.
![[paso2.png]]

**Paso 3:** Dentro de la carpeta `documentos`, se creó un archivo llamado `notas.txt` y se  añadieron  tres líneas de texto usando el comando `nano`

Figura 3. Comando **"touch"**..
![[paso3 1.png]]
![[paso3.1.png]]

**Paso 4:** Se copio `notas.txt` a la carpeta `scripts` y se modifico su nombre a `backup_notas.txt`.

Figura 4. Comando **"mv"**..
![[paso4.png]]

**Paso 5:** Se envió el archivo`backup_notas.txt` a la carpeta `imagenes`.

Figura 5. Comando **"mv"**.
![[paso5.png]]

**Paso 6:** Se creó un nuevo archivo llamado `resumen.txt` dentro de la carpeta `documentos` y se redirecionó el contenido de `notas.txt` a este archivo.

Figura 6. Comando **"cat"**.
![[paso6.png]]

**Paso 7:** Se añadió una nueva línea de texto sin sobrescribir lo que ya estaba en `resumen.txt`

Figura 7. Comando **"echo"**.
![[paso7.png]]

**Paso 8:** Se eliminó el archivo `backup_notas.txt` de la carpeta `imagenes` usando el comando `rm`, y luego eliminé la carpeta `imagenes` con `rmdir`estando vacía.

Figura 8. Comando **"rm"**.
![[paso8.png]]

![[paso8.1.png]]

**Paso 9:** Se extrajo el historial de todos los comandos que se ejecutaron  en un archivo llamado `tarea-s1-nombre_apellido.txt` usando el comando `history`

Figura 9. Comando **"history"**.
![[paso9.png]]

**Paso 10:** Se sustituyó el nombre_apellido" por mi nombre y apellido correspondiente.

Figura 10. Comando **"mv"**.
![[paso10.png]]
## 9. Resultados esperados:
    
La práctica no solo permitió aplicar comandos esenciales en la terminal, sino que también fortaleció la lógica de navegación, organización y control de archivos y carpetas en entornos Unix/Linux.

Después de completar todos los pasos, pude manejar mejor la terminal. Logré crear carpetas organizadas y moverme entre ellas sin problema. Practiqué cómo crear archivos, copiar, mover, renombrar y también cómo borrar cosas sin afectar lo demás.

También entendí cómo funciona la redirección y cómo combinar contenido de un archivo a otro, lo cual fue súper útil para automatizar tareas básicas. Finalmente, guardé todo mi historial de comandos en un archivo, lo que me ayudó a revisar qué hice paso a paso. 

El uso de **Warp** en macOS brindó una experiencia más fluida, moderna y visual al trabajar con la terminal, pero sin alterar la esencia de los comandos tradicionales.

En resumen, fue una buena práctica para comprender y dominar de mejor manera los comandos de Linux y aprender a organizarme mejor desde la terminal.

![[resultado.png]]

## 10. Bibliografía

- Khattab, A., Camp, J., Hunter, C., Murphy, P., Sabharwal, A., & Knightly, E. W. (2008). WARP: A flexible platform for clean-slate wireless medium access protocol design. _ACM SIGMOBILE Mobile Computing and Communications Review_, _12_(1), 56-58.

- **Richardson, D.** (2019). _Introducción a la Terminal de Linux_. Linux Foundation.

- Sánchez Anguix, V. (2021). Comandos básicos de Linux para trabajar con el sistema de ficheros.