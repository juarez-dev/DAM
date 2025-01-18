## DISTRIBUCIÓN DE APLICACIONES.
## DEFINICIÓN Y COMPOSICIÓN DE UNA DISTRIBUCIÓN - SISTEMA DE GESTIÓN DE PAQUETES.
Una distribución de software es un conjunto de programas específicos que se presenta compilado y configurado.

**Sistema de gestión de paquetes**, colección de herramientas que sirven para automatizar el proceso de instalación, actualización, configuración y eliminación de paquetes software.

## INSTALADORES.
Programas especiales que realizan las tareas de instalación de software de forma automática.

Un programa normalmente esá formado por un conjunto de archivos, que normalmente necesitan ser copiados en determinados directorios, y en muchos casos, deben registrarse en el registro de Windows, si utilizamos este S.O.

Los instaladores realizan todas estas operaciones de forma transparente al user, copiará los archivos de la app en los directorios adecuados, registrará la aplicación, creará los menús y los accesos directos al Escritorio.

Pasos en la instalación:
  1. Verificación de la Compatibilidad.
  2. Verificación de la Integridad.
  3. Creación de los Directorios Requeridos.
  4. Creación de los Usuarios Requeridos.
  5. Copia, Desempaque y Descompresión de los Archivos desde el Paquete de Software.
  6. Compilación y Enlace con las Bibliotecas Requeridas.
  7. Configutación.
  8. Definición de las variables de entorno requeridas.
  9. Registro de la Aplicación.


## PAQUETES AUTOINSTALABLES.
Cuando se deccide distribuir una app en un paquete autoinstalable, se está empaquetando la app en un único archivo, que contendrá todos los archivos y directoris que formarán la aplicación.


## HERRAMIENTAS PARA CREAR PAQUETES DE INSTALACIÓN.
En la actualidad existe un amplio abanico de herramientas de creación de paquetes de instalación.

Si se trabaja con Linux, es necesario crear un paquete de instalación acorde con la distro donde queramos instalarlo.


### CANALES DE DISTRIBUCIÓN

En Windows o Mac los programas se suelen buscar en Internet y se encuentran mayormente en forma de instaladores ejecutables.

En sistemas open source se encuentra esta fomra de distribución, pero la mayoria se encuentra empaquetado en ficheros .deb que contienen programas y las bibliotecas que necesitan.

Los **repositorios** son servidores que contienen conjuntos de paquetes, a estos servidores se accede con herramientas como **Centro de Software.**

En los dispositivo smóviles, es comun la distribución a traves de las **stores de aplicaciones**, canales de distribución principales para este tipo de aplicaciones móviles.


## PERSONALIZACIÓN DE LA INSTALACIÓN



























