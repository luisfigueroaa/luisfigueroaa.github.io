+++
date = '2026-05-24T13:33:46-05:00'
draft = false
title = 'RF día cero'
categories = ['Electrónica']
tags = ['rf', 'kicad', 'skrf', 'ngspice']
+++

Empecemos para definir que es RF ó Radiofrecuencia. Vamos a buscar una definición práctica en Wikipedia antes de adentrarnos a los libros.

> El término radiofrecuencia (RF) (también, espectro de radiofrecuencia) se aplica a la porción menos energética del espectro electromagnético, situada entre los 3 hercios (Hz) y 300 gigahercios (GHz).

Entonces podemos definir que es cualquier espectro de la frecuencia entre esos rangos, aplicado a cualquier energía.

Ahora, no vamos a adentrarnos en definiciones complejas aún. Sin embargo vamos a manejar dos libros en este recorrido:

1. Microwave Engineering - David M. Pozar
2. Microwave Transistor Amplifiers 2nd Edition - Guillermo Gonzales

Ambos libros por favor pedirmelos por correo al **[luis_figueroa_morales@yahoo.com](mailto:luis_figueroa_morales@yahoo.com)**

Además el software que usaremos será:

1. Ngspice.
2. SCRFKit.

Pueden usar cualquier calculadora o software de análisis numérico. En este caso les podría recomendar Octave. Ya que es gratuito y puede hacer gráficas avanzadas.

## Ngspice

KiCad incluye **ngspice** dentro de su motor. Nos va a permitir probar y validar partes de nuestro circuito de manera simulada. Sin necesidad de gastar dinero en hacer una PCB.

En este caso podemos usar una herramienta que ya tiene esto incluido, como la que es KiCad. Pueden bajarlo desde el siguiente [enlace](https://www.kicad.org/), la versión para este caso no es importante.

## SKRF

scikit-rf (también conocido como skrf) es un paquete de código abierto para ingeniería de RF/microondas, desarrollado el lenguaje de programación Python.

