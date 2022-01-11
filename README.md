# Deteccion-de-signos
![portada presentacion](https://user-images.githubusercontent.com/92582462/148980736-569a4827-0730-4223-ad1d-50b415275a06.jpg)


El objetivo de este cuaderno es realizar un primer acercamiento a la detección de los gestos de la lengua de signos española. Para ello se ha seleccionado un conjunto limitado de palabras (Hola,Autobus,Abajo,Coche,Yo,Querer,Mesa,Adios,Agua,Amigo, Casa, Sentir, Colegio,Cerveza,) y se han realizado diferentes vídeos para plasmar sus movimientos. Estos movimientos se capturarán con la ayuda de la biblioteca de Mediapipe.

Mediapipe es una biblioteca de código abierto desarrollada por Google que realiza la detección automática de diferentes partes del cuerpo. Gracias a esta biblioteca, la posición relativa de cada punto en una imagen o un video se puede detectar fácilmente. El objetivo, o más bien la idea principal, es obtener las coordenadas de los diferentes gestos y de estos, poder inferir qué gestos se están realizando.


![Mediapipe](https://google.github.io/mediapipe/images/mobile/holistic_sports_and_gestures_example.gif)

Para obtener las coordenadas se ha utilizado el modelo Holistic de MediaPipe. Este modelo es capaz de detectar 21 puntos relevantes en cada mano, 33 en cuerpo y cara, y una malla de 468 puntos en la cara. Como la mayoría de estos puntos no aportan información relevante para el objetivo que se busca, se han seleccionado un total de 57 puntos (21 puntos para cada una de las manos y 15 para cuerpo y cara).


![hands puntos](https://user-images.githubusercontent.com/92582462/148983346-ec1ee97d-059d-4339-a9f9-48d12f1fab09.jpg)

![pose puntos](https://user-images.githubusercontent.com/92582462/148983351-74933920-4d51-4a70-a431-1f11244e22f2.jpg)

Enlaces externos:  

Articulo medium:
https://medium.com/@luis.urresti.alas/560e518f8ae2

Mediapipe holistic:  
https://google.github.io/mediapipe/solutions/holistic.html

