<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Escribe un numero binario de 4 entradas, tenemos una salida a 7 segmentos

## How to test

1. Selecciona un número binario de 4 bits usando los primeros 4 interruptores de entrada (`ui_in[0..3]`).
2. Observa cómo el número correspondiente aparece encendido en el display de 7 segmentos conectado a `uo_out[0..6]`

## External hardware

* Display de 7 segmentos (cátodo común) conectado a los pines de salida `uo_out[0..6]` (o el display integrado en la placa demo de Tiny Tapeout).
