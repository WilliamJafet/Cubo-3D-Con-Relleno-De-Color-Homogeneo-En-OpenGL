# Cubo 3D Con Relleno De Color Homogéneo En OpenGL

La práctica consiste en realizar un programa donde se muestra un cubo 3D con relleno de color homogéneo.
Para ello primero se explica el código fuente del programa realizado.
En principio se realiza la importación de librerías necesarias para realizar la práctica.

![image](https://user-images.githubusercontent.com/72232712/145739061-dc17540e-5d2b-419c-9af8-205e289ce85f.png)

El siguiente bloque de código es la declaración de variables necesarias para realizar distintas acciones.

![image](https://user-images.githubusercontent.com/72232712/145739071-b10d2779-d72f-4fa1-a0f1-abd8700c80bb.png)

La función principal es importante debido a que es en esta parte donde empieza a ejecutarse el programa. En este bloque se realizan diversas configuraciones de la ventana para que se muestre al usuario.

![image](https://user-images.githubusercontent.com/72232712/145739079-dcd8e1b1-573d-4b93-a011-39413267e096.png)

La función init es parte de la librería OpenGL y se utiliza para inicializar los componentes del Canvas, este es un componente en el que se va a realizar el pintado del objeto.

![image](https://user-images.githubusercontent.com/72232712/145739097-d7d64a0e-5546-417d-898f-cd861078d433.png)

En la función reshape se realizan las configuraciones necesarias para que se pueda mostrar el objeto.

![image](https://user-images.githubusercontent.com/72232712/145739106-581535a0-dd6c-4475-93fa-3763854af1c1.png)

La función display es una de las funciones más importantes porque es aquí donde se programan las instrucciones para que el programa pinte lo que le estamos indicando.
Para esta práctica se pintan los distintos cuadros que forman el cubo, para ello se tiene en cuenta las coordenadas de cada vértice del cuadrado. En total se pintan seis cuadrados para formar el cubo.
Para indicar el color homogéneo, simplemente definimos el mismo color para todas las caras del cubo.

![image](https://user-images.githubusercontent.com/72232712/145739130-3736c4e5-da59-4f52-b5be-af0f8521644d.png)

![image](https://user-images.githubusercontent.com/72232712/145739139-7bf5f388-7723-4de9-96c2-66a014ededa1.png)

La última función por el momento no se realiza ninguna acción.

Ahora que se ha explicado el código fuente, la siguiente parte es mostrar el resultado.
Como resultado hemos obtenido lo que se muestra en la siguiente figura. 

![image](https://user-images.githubusercontent.com/72232712/145739165-4b56bd78-abf5-4ec1-84d8-672743a73956.png)
