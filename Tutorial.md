# Git (Control de Versiones)
***
El desarrollo de proyectos donde se tienen que manejar multiples archivos trae inherentemente una dificultad para mantener un "rastreo" de los mismos. Es aquí donde aparece una herramienta que se conoce como Control de Versiones.

**Control de Versiones:** El Control de Versiones es un sistema que registra los cambios hechos a un archivo o un conjunto de archivos a lo largo del tiempo, esto lo le permite a quien este desarrollando el proyecto mantener un registro con el que a su vez puede, si es que lo llegase a necesitar, regresar a una version no modificada o parcialmente modificada del proyecto.

**Un símil** comúnmente aceptado que ejemplifica el funcionamiento del Control de Versiones se remite al uso de ordenadores, cuando se desea restaurar una version del mismo, debido a algún mal funcionamiento de un programa que no fue correctamente instalado o una mala manipulación de los archivos del sistema, en estos casos es común encontrar la opción ***Restaurar a la ultima version estable del sistema.***
        
**Sistema de Control de Versiones Local:** una de las primeras practicas de control de versiones usadas fue el hecho de copiar la version actual del proyecto dentro de una carpeta local nueva, de esta forma tendríamos en una carpeta almacenada la version base del proyecto y en otra carpeta la version que entraremos a editar, de esta forma si el proyecto que estamos editando falla, podemos regresar a la version base en lugar de iniciar de cero.

Esta manera de controlar las versiones de los proyectos es bastante común debido a que es sencilla (cuando se tienen pocas versiones), sin embargo también es fácil cometer errores usando este sistema, podemos sobreescribir archivos que no queremos o copiar el archivo equivocado y dañar la cronología del proyecto.

Existen variedad de formas para realizar un control de versiones, entre ellas están una herramienta llamado [RCS](https://es.wikipedia.org/wiki/Revision_Control_System) (Revision Control System) pre instalada en gran cantidad de computadores, CVCS (Centralized Version Control System), DVCS(Distributed Version Control System) siendo esta ultima la forma en la que Git funciona.

# Cómo descagarlo
***

Git es un software libre que puede ser obtenido en este [link](https://git-scm.com/downloads), aunque para los usuarios de OS (MAC), esta herramienta puede instalarse de forma nativa mediante la descarga de las ***Command line Tools***, el archivo de descarga puede obtenerse en este [enlace](https://developer.apple.com/download/more/) alli seleccionan una versió de *Command Line Tools for Xcode* y empezará la descarga, una vez descargado dependiendo del sistema operativo se realizará la intalación del software para poder usar git en nuestros ordenadores.

# Git Basics
***

En el sistema DVCS de Git existen cuatro estados en los que un archivo puede encontrarse


| Untracked | Unmodified | Modified | Staged |
|:--------- |:---------- | :------- | :----- |
| Archivos sin "rastrear" | Archivos rastreados sin modificar | Archivos rastreados modificados | Archivo rastreado sin nuevos cambios |

Dentro de nuestro proyecto almacenado en una carpeta, vamos a tener que cualquier archivo dentro de la carpeta se va a encontrar en uno de esos cuatro estados.
