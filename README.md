# Robótica 2025-I Laboratorio-No.02
***Robótica Industrial - "Trayectorias, Entradas y Salidas Digitales"***  
  
Maria Lucia Arias Ortiz - `mariasor@unal.edu.co`  
Andrés Felipe Quenan Pozo - `aquenan@unal.edu.co`
***
# Video
A continuación se presenta el video del desarrollo de este laboratorio. 

# Introducción 

# Objetivos

* Conocer los elementos de un robot industrial.
* Realizar calibración de herramientas en el robot real, así como en RobotStudio.
* Identificar los tipos de movimientos en el espacio de la herramienta útiles para trabajos de manipulación.
* Ampliar el manejo de funciones proporcionadas por RobotStudio.
* Utilizar diversas funciones de RAPID.
* Utilizar el módulo de entradas y salidas digitales dispuesto en el controlador IRC5.

# Descripción de la solución planteada

El robot ABB IRB 140 fue programado para dibujar los nombres de los integrantes del grupo y un gato sobre un pastel (una caja con superficie de 23 cm x 15 cm) ubicado en una banda transportadora. Para ello, primero se diseñó e imprimió en 3D una herramienta personalizada en Inventor, adaptada a las dimensiones del marcador y del flange del robot. Posteriormente, en RobotStudio, se cargó esta herramienta para simular el proceso: se calibraron el workobject y la herramienta, se añadió la banda transportadora y se desarrolló el código en RAPID que definía las trayectorias y orientaciones, junto con las entradas y salidas digitales para iniciar la rutina y mover la banda. Una vez verificado el funcionamiento en la simulación, se implementó el programa en el robot real, donde se recalibraron la herramienta y el workobject manualmente, y se cargó el módulo de código al controlador para ejecutar los dibujos.

# Diseño de la herramienta 
Se diseñó en Inventor una herramienta modular con ángulo ajustable que permitía seleccionar el ángulo óptimo para el proceso de dibujo; este ángulo se adaptó finalmente a 30° en la práctica. El diseño se compone de tres partes principales: la base, que se atornilla al flange del robot; el portaherramientas, encargado de sujetar el marcador y el resorte; y la tapa, que asegura que ni el resorte ni el marcador se salgan durante el proceso. Para el diseño, se tuvieron en cuenta las dimensiones del marcador, los agujeros del flange del robot y las tolerancias dimensionales, garantizando así que el marcador encajara correctamente y que la herramienta pudiera atornillarse al robot. Se agregó un resorte para permitir una presión constante y uniforme del marcador sobre la superficie, asegurando trazos consistentes sin importar pequeñas variaciones en la altura del "pastel" o el desgaste de la punta. Este modelo fue impreso en PLA utilizando una impresora 3D.


# Diagrama de flujo de acciones del robot

# Plano de planta de la ubicación de cada uno de los elementos

![image](https://github.com/user-attachments/assets/1d3711cd-1fae-4aed-a44d-16e2b8e43b35)


# Descripción de las funciones utilizadas

# Código en RAPID del módulo

# Conclusiones
