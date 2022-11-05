# Entrega Laboratorio 5

El laboratorio 5 - Cinemática Inversa, tiene como objetivo determinar inicialmente la cinemática inversa del robot Phantom X y posteriormente generar trayectorias para poder escribir en un  plano, esto mediante el uso de Python en conjunto con ROS.

## Autores

- [Wilder Ofrey Bello Herrera](https://github.com/WilderBello)
- [Javier Eduardo Gutierrez Serrano](https://github.com/jaegutierrezser)

## Solución

Para la solución propuesta se partió inicialmente del cálculo de la cinemática inversa del robot, de la siguiente manera:

## Cinemática Inversa


## ROS con Python

Para la implementación de la cinemática inversa, se realizó la programación en Python como se puede ver en la siguiente imagen:

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Cinematica_Inversa.png)


El script desarrollado tiene el siguiente menú en el cual espera una entrada (input) de tipo entero para acceder a cada una de las rutinas:

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/Images/Rutina.png)

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

[![Ver el video](https://drive.google.com/file/d/1WhTPV6rfoY3DFIj117vyRS2vMmLFnTv2/view?usp=sharing)](https://drive.google.com/file/d/1WhTPV6rfoY3DFIj117vyRS2vMmLFnTv2/view?usp=sharing)

[Implementación Cinemática Inversa](https://www.youtube.com/watch?v=ktwIJOaMfWQ&ab_channel=JavierEduardoGutierrezSerrqno)
# [![Alt text](https://img.youtube.com/vi/ktwIJOaMfWQ/0.jpg)](https://www.youtube.com/watch?v=ktwIJOaMfWQ)

## Verificación Dimensional

Finalmente, con el trazado de las trayectorias y la trayectoria previamente definida se determina la verificación de la trayectoria generada en la implementación.

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/Error.png)
![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/Error2.png)

Usando el softwware de análisis de imagen se determina el error dimensional del limite inferior generado por medio del manipulador y el limite inferior generado por medio de puntos en el software Autocad.

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/ErrorL1.png)
![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/ErrorL2.png)

Para el análisis se toman 22 puntos de comparación para determinar el error longitudinal con respecto al centro del espacio de trabajo.

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/An%C3%A1lisisE_L.png)

Por lo tanto, se tiene un error porcentual promedio de los datos de 33.4 %, y la desviación estandar del conjunto de datos es:

![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/desv1.png)

![Análisis para una línea paralela P1](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/p1.png)
![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/Errorp1.png)

![Análisis para una línea paralela P3](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/p3.png)
![](https://github.com/WilderBello/Robotica_Laboratorio_5/blob/main/IMG.%20Laboratorio%20N%C2%B005/Errorp3.png)


![]()
![]()
![]()
![]()
![]()
