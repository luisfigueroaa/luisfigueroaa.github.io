---
title: "Convertir de una imágen convencional (ej. JPG) a un trazo o dibujo (ej. SVG, PNG?) con Inkscape"
date: 2022-06-11T12:47:17-05:00
tags: ["Inkscape",]
categories: ["Tutoriales",]
---

Primero debemos tener instalado inkscape lo podemos descargar del siguiente enlace:

Descargar [Inkscape](https://inkscape.org/release/inkscape-1.2/).

O si tienes Debian o Ubuntu, lo puedes instalar desde sus repositorios:

    sudo apt update && sudo apt upgrade
    sudo apt install inkscape

Ahora debemos ingresar la imágen que se quiera convertir a trazo, por ejemplo la siguiente:

Vamos a la Barra de herramientas y presionamos en Vectorizar mapa de bits. Se abrirá un menú a la derecha a continuación. Le damos click en Actualizar, para poder tener una preview de nuestra imágen a vectorizar. Por ultimo le damos en Aplicar.

![inkscape](/pix/inkscape-1.png)

Se tendrá una imágen como esta a continuación, sin embargo, para ponerla a solo trazo (o dibujo) tendremos que quitar el relleno y solo poner un trazo.

En la barra inferior presionamos click derecho en el color negro para elegir el trazo. Para eliminar el relleno tendremos que dar click derecho al primer casillero con una X y poner Fijar relleno.

![inkscape](/pix/inkscape-2.png)

Finalmente nos quedará una imágen como está a continuación.

Puedes guiarte del siguiente vídeo donde estan los mismos pasos explicados:

{{< youtube idGT5QVDZb4 >}}
