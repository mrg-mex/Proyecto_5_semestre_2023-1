# Proyecto_5_semestre_2023-1
# Diseño y simulación de un robot manipulador móvil

# Robótica serial adaptable

# Participantes
- Erik Peña Medina (responsable)
- Martin Chilpa
- David Altamirano

# Introducción 

 

# Migración de proyecto

Al tener acceso al repositorio, se pudo apreciar que los diferentes componentes se encontraban en una extensión diferente a la deseada. El proyecto se planteó retomar desde el programa de Fusion 360. El proceso que se llevó acabo fue abrir los nuevos componentes desde Fusion 360 y salvar con la extensión reconocida por el software (.dwg)

![Texto alternativo](ruta_de_la_imagen)
![Descripción de la imagen](/images/posicion_llantas.jpg)


# Metas

---
# Productos
- Diseño a detalle del la plataforma móvil.
- Desarrollo de los elementos de una simulación Virtual del robot en formato URDF.
- Diseño y realización de los circuitos de control y de potencia del robot en formato PCB.
- Desarrollo de los elementos para la construcción del manipulador móvil de manera física.

---




---
## Lun 12/12/2022 fue puente
---
## Tercer dia, mie 14/12/22
- cads de partes faltantes
- distribucion de los elementos en los pisos
- tamaño de los pisos y alturas chance

Abajo se muestran las dimensiones preliminares del tamaño de los pisos

![Descripción de la imagen](/images/dims_preliminares.jpg)

![Descripción de la imagen](/images/distribucion_v1.png)

---


## Cuarto día, mie 11/01/23
- La placa inferior del diseño comercial tiene unas dimensiones de 280 mm x 150 mm. Sin embargo, estas medidas no pueden ser tomadas debido al tamaño de la batería que chocaría con los motores.
Se propuso una placa inferior de 200 mm x 320 mm basándonos en las medidas del primer prototipo fabricado con MDF por el profesor Erik Peña Medina. La placa seguía siendo pequeña para posicionar la batería en la parte inferior.
Al final se propuso una placa de 320 mm x 170 mm la cual permitió tener el suficiente espacio para distribuir los componentes y realizar los respectivos agujeros para el cableado.

![Descripción de la imagen](/images/quince.png)

### Distancia entre motores
Para la propuesta de la distancia entre motores el equipo se basó en la distancia del robot comercial la cual es de 44 mm. Esta distancia entre motores es importante ya que le dará estabilidad al robot móvil.

![Descripción de la imagen](/images/uno.jpg)

### Orientación de IBT2
Por cada motor existirá un IBT2 y la para proponer la orientación más óptima de estos componentes se consideró las conexiones entre componentes.

![Descripción de la imagen](/images/tres.jpg)

A continuación, se muestra el diagrama de conexiones entre componentes:

![Descripción de la imagen](/images/dos.jpg)

### Orientación final propuesta:

![Descripción de la imagen](/images/dieciseis.png)

### Propuesta montaje de PCB
Al no conocer las dimensiones de la PCB se propuso crear un piso intermedio en voladizo. Se muestra la propuesta en la siguiente imagen:
 
![Descripción de la imagen](/images/seis.jpg)

 
Para simular la PCB y realizar el montaje de los componentes se insertaron dos protoboards.

![Descripción de la imagen](/images/Protoboard.jpg)


### Ensamble de componentes principales
Nos encontramos con el problema de no poder ensamblar los componentes a la placa inferior debido a todo el espacio que ocupa la batería. Para solucionar esto, se propuso un piso superior en donde se montaron cada uno de los IBT2. 

![Descripción de la imagen](/images/once.jpg)

Los IBT2 se montaron en voladizo esto ayudará a mejorar el paso del aire a través de los disipadores.

![Descripción de la imagen](/images/trece.jpg)

### Diseño del segundo Piso del Robot, para ensamblaje del brazo.
En este punto, se contempló que nuestro diseño (una vez optimizado el espacio) debería contener unas columnas que nos permitieran dejar un piso libre
para ensamblar el brazo del modelo comercial.

![Descripción de la imagen](/images/Garra.jpg)

### Implementación del segundo piso del robot
Una vez planificado el espacio donde se implementarán las columnas, se procedió a realizar el modelado final:
![Imagen de una segunda plataforma sobre el diseño previamente mostrado](/images/Segundo_piso.jpg)


### Ensamble del brazo robotico:
Para esta parte, se buscó establecer la pieza cercano al centro de masa, de tal modo que no afectara la localización de la Nvidia y pudiera cubrir los requerimientos 
planteados por el profesor.




