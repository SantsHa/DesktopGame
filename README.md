# DesktopGame

El funcionamiento del juego se basa en la comunicacion serial entre un Arduino UNO y una Raspberry Pi. El Arduino transmite la información recibida de un teclado matricial 4x4. 
Las únicas teclas funcionales para le juego son las siguientes:
* [2] - arriba
* [8] - abajo
* [4] - izquierda
* [6] - derecha
* [5] - golpear

La Raspbery recine los datos por UART y los procesa para poder mover un objeto en la pantalla para poder darle un golpe al ratón, el cual se mueve aleatoriamente en toda la pantalla.

* Si se falla un golpe -20pts
* Se golpeas al ratón +10pts
* El programa de juego durará 2 minutos y aparecerá en cuenta regresiva
* Cada 20 segundos aumenta la velocidad del ratón

Todos los archivos deben estar ubicados en una misma carpeta para su correcto funcionamiento.

![excRasp](https://user-images.githubusercontent.com/70683976/120696444-30dc6c80-c472-11eb-9c3c-a39b37462867.png)
![deskRasp](https://user-images.githubusercontent.com/70683976/120696447-31750300-c472-11eb-8bf7-82678dc6e090.png)
![gameRasp](https://user-images.githubusercontent.com/70683976/120696449-31750300-c472-11eb-870c-87676984553f.png)
