# Entrega Laboratorio 5

El laboratorio 5 - Cinemática Inversa, tiene como objetivo determinar inicialmente la cinemática inversa del robot Phantom X y posteriormente generar trayectorias para poder escribir en un  plano, esto mediante el uso de Python en conjunto con ROS.

## Autores

- [Wilder Ofrey Bello Herrera](https://github.com/WilderBello)
- [Javier Eduardo Gutierrez Serrano](https://github.com/jaegutierrezser)

## Solución

Para la solución propuesta se partió inicialmente del cálculo de la cinemática inversa del robot, de la siguiente manera:

## Cinemática Inversa

Para la implementación del laboratorio, realizaron las mediciones de longitudes de cada eslabón para posteriormente obtener el diagrama del robot y los parámetros DH, contrastando con los valores obtenidos del datasheet del fabricante del manipulador.

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Space_Work.png)

Con estos datos se procede a determinar los marcos y parámetros del manipulador de acuerdo con la convención Denavit-Hartenber estandar.

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Marcos_DH1.png)

- Parámetros DH

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/DH.png)

También se obtuvo el diagrama simulado en Matlab haciendo uso del Toolbox de Peter Corke:

- Posición 1: 0, 0, 0, 0, 0

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Posicion_N%C2%B001.png)

- Posición 2: -20, 20, -20, 20, 0

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Posicion_N%C2%B002_1.png)
![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Posicion_N%C2%B002_2.png)

- Posición 3: 30, -30, 30, -30, 0

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Posicion_N%C2%B003.png)

- Posición 4: -90, 15, -55, 17, 0

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Posicion_N%C2%B004.png)

- Posición 5: -90, 45, -55, 45, 10

![](https://github.com/WilderBello/Robotica_Laboratorio_4/blob/main/MatLab/Imagenes/Posicion_N%C2%B005.png)

## ROS con Python

Para la implementación de la cinemática inversa, se realizó la programación en Python como se puede ver en la siguiente imagen:

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Cinematica_Inversa.png)

Posteriormente se generó la cantidad de puntos para cada una de las rutinas:

- Recoger marcador

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_0.png)

- Máximo Alcance

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_1.png)

- Mínimo Alcance

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_2.png)

- Dibujo de Iniciales

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_3.png)

- Dibujo de triángulo

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_4.png)

- Dibujo de Circunferencia

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_5.png)

- Dibujo de tres líneas rectas paralelas

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_6.png)

- Dibujo de 5 puntos equidistantes

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_7.png)

- Dibujo de figura libre

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_8.png)

- Retorno de marcador

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trayectoria_9.png)

Todo el código implementado se puede ver ![aquí](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Scripts/Lab_5.py).
## Implementación

Finalmente, el trazado de las trayectorias fue el siguiente:

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Trazo_Total.jpeg)

La implementación del código se puede observar en el video:

[![Ver el video](https://drive.google.com/file/d/1QhI-nAJg5XgqxbzmVyoA0x-kBUTsYf57/view?usp=sharing)](https://drive.google.com/file/d/1QhI-nAJg5XgqxbzmVyoA0x-kBUTsYf57/view?usp=sharing)