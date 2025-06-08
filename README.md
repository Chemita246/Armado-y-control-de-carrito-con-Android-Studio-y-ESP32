Este proyecto fue creado por inspiración desde una materia cursada en la universidad, le doy gracias a mi maestro Rubén Estrada por sus enseñanzas y
actividades didacticas.

Para implementar este proyecto es indispensable contar con algunas cosas necesarias... 
  1.-ESP32 S3
  2.- Android 5 minímo
  3.- Conexión a wifi
  4.- Arduino IDE (versión más reciente de preferencia) 
  
El diagrama de conexión estará proporcionado por una imágen anexada aquí mismo, el diseño del carrito dependerá de ti.
La interfaz de la aplicación es bastante intuitivá tanto que la resumiremos en:
   1.- Adelante
   2.- Atrás
   3.- Derecha
   4.- Izquierda
   5.- Girar Servomotor
   6.- Medir distancia
   7.- Prender luces
   8.- Dar vuelta
   9.- Conectarse a la IP de la ESP32

--- IMPLEMENTACION ---
Para comenzar, debemos haber armado el carrito con las conexiones correspondientes como se mostró en la imágen. Una vez hecho esto se procede a
abrir el código de arduino llamado "Arduino.ino" y modificar la red Wifi por la tuya (Aproximadamente lineas: 29 y 30), después debes programar la ESP32 con los códigos
de arduino anexados en el repositorio (son 3, los 3 en conjunto hacen uno solo). Después de haber prigramado la ESP32 al correr el monitor serial de esta, vendrán algunos datos, hay que fijarnos en el más importante que es LA DIRECCIÓN IP DE LA ESP32, esta dirección es importante para lograr la conectividad entre la ESP32 y la aplicación.

Después es indispensable descargar el APK proporcionado en este repositorio, la aplicación permitirá el control de las funciones del carrito, cuyas mismas son las que fueron enlistadas. La aplicación se instala como cualquier APK, Pedirá si es una fuente confiable, solamente hay que aceptar (En lo absoluto tiene algún tipo de malware).
Una vez instalada la aplicación y con el carrito ya armado, programado y prendido es necesario (en la aplicación) presionar el botón que tiene la leyenda "Enter ESP32 IP", hay pondremos la IP que nos dió la ESP32 y después presionamos en "Aceptar".
Cualquier estado de "debug" se encontrarán en pantalla de la aplicación y mostrará algunas guías de peuqeños problemas que pudiera haber.

Espero que disfruten del proyecto tanto como yo. Puedo anexar el proyecto de Android Studio, para que puedan sentirse libres de modificarlo para funciones extras, comenten si lo quieren.

------------------------ Gracias por leer y visitar - Chemita 246 ------------------------

 

