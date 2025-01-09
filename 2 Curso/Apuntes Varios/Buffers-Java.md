# BUFFERS EN JAVA
## DEFINICIÓN
Un **buffer** es un área de almacenamiento temporal de memoria utilizada para almacenar datos mientras se tranfieren de un lugar a otro.
Se usa para compensar diferencias en la velocidad de procesamiento entre dos dispositivos o procesos.
*Actúa como intermediario entre el programa y la fuente/destion de datos, reduciendo las operaciones de I/O costosas*

## FUNCIONAMIENTO
  1. Cuando se leen datos desde un archivo o red, el buffer primero llena su espacio con un bloque de datos desde el origen.
  2. El programa lee los datos del buffer, no directamente desde el origen, lo que es más rápido.
  3. Para la escritura, el buffer almacena los datos temporalmente en memoria y los escribe en el destino cuando está lleno o cuando se invoca el método flush().

## CLASES PRINCIPALES BufferedInputStream & BufferedOutputStream:
Trabajan con flujos de bytes ([InputStream](Flujos-Entrada-Salida.md#InputStream) y [OutputStream](Flujos-Entrada-Salida.md#OutputStream)) agregando un buffer para leer/escribir datos de manera más eficiente.
### BufferedInputStream
  * BufferedInputStream(FileInputStream())
### BufferedOutputStream
  * BufferedOutputStream(FileOutputStream())

## CLASES BufferedReader y BufferedWriter
Trabajan con flujos de caracteres (Reader y Writer), facilitanto la lectura y excritura de texto.
  * BufferedReader, lee lineas completas en lugar de caracteres individuales.
  * BufferedWriter, escribe en un buffer antes de volcar los datos al archivo.
