Este proyecto fue creado por inspiración desde una materia cursada en la universidad, le doy gracias a mi maestro Rubén Estrada por sus enseñanzas y
actividades didacticas.

Para implementar este proyecto es indispensable contar con algunas cosas necesarias... 
  1.-ESP32 S3
  2.- Android 5 minímo
  3.- Conexión a wifi
  4.- Arduino IDE (versión más reciente de preferencia) 
  5.-Android Studio
  
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

--- IMPLEMENTACION ---
Para comenzar, debemos haber armado el carrito con las conexiones correspondientes como se mostró en la imágen. Una vez hecho esto se procede a
abrir el código de arduino llamado "Arduino.ino" y modificar la red Wifi por la tuya (Aproximadamente lineas: 29 y 30), después debes programar la ESP32 con los códigos
de arduino anexados en el repositorio (son 3, los 3 en conjunto hacen uno solo). Después de haber prigramado la ESP32 al correr el monitor serial de esta, vendrán algunos datos,
hay que fijarnos en el más importante que es LA DIRECCIÓN IP DE LA ESP32, esta dirección es importante para lograr la conectividad entre la ESP32 y la aplicación.

Al abrir el proyecto de en Android Studio lo único que hay que hacer es modificar la dirección IP por la de tu ESP32 (Aproximadamente linea: 89) y ya está, en la aplicación hay un bloque en el que nos dice 
cuando esta misma ha sido conectada o falló al conectar, ES IMPORTANTE QUE EL TELÉFONO EN EL QUE USEMOS LA APP Y LA ESP32 ESTÉN A LA MISMA RED DE WIFI.

 


