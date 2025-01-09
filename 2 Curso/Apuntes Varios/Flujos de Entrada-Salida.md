## CLASES OutputStream e InputStream - JAVA
# OutputStream:
  - Clase abstracta, define los métodos básicos para escribir datos a un destino:
    - **void write(int b)**, escribe un byte al flujo de salida.
    - **void write(byte[] b)**, escribe un arreglo completo de bytes.
    - **void flush()**, limpia cualquier dato almacenado en el buffer.
    - **void close()**, cierra el flujo y libera los recursos asociados.
# InputStrean:
  - Clase abstracta, define los métodos básicos para leer datos a un destino:
      - **int read()**, lee un byte y devuelve su valor como entero ó -1 si se alcanza el final del flujo.
      - **int read(byte[] b)**, lee múltiples bytes y los almacena como un arreglo.
      - **void close()**, cierra el flujo.
   
## CLASES DataOutputStream y DataInputStream - JAVA
Amplían las funcionalidades básicas de OutputStream e InputStream para facilitar el trabajo con datos primitivos y cadenas.
Permiten leer/escribir tipos de datos primitivos de forma más conveniente.
# DataOutputStream: -> DatainputStream(InputStream)
  - **void writeInt (int v)**, escribe un entero.
  - **void writeDoubl(double v)**, escribe un valor double.
  - **void writeUTF(Strigns)**, escribe una cadena en formato UTF-8.
# DataOutputStream: -> DataOutputStream(OutputStream)
  - **int readInt()**, lee un entero.
  - **String readUTF()**. lee una cadena en formato UTF-8.

## RELACIÓN Y FLUJO TÍPICO
  1. Se usa DataOutputStream para escribir datos en un archivo binario.
  2. Luego se usa DataInputStream para leer los datos del archivo, asegurándose de que el orden y tipos coinciden.
