# Pruebas de validación

En este documento se muestran algunas de las pruebas de validación realizadas sobre el sistema de conducción autónoma desarrollado. 

El objetivo de estas pruebas es por un lado comprobar que se han cumplido los objetivos del proyecto, y por otro lado, determinar el alcance del sistema desarrollado. 

## Resultado normal

Primero se muestra un resultado de una reconstrucción correcta bajo condiciones normales:

<img src="media/validacion_normal.png" alt="Resultados normales" width="800"/>

&nbsp;

## Resultados bajo diferentes iluminaciones
En este caso el objetivo es probar si el sistema encargado de extraer las caracteristicas de las lineas es capaz de funcionar correctamente bajo situaciones especiales de iluminación.

&nbsp;

- **Reflejos en el recorrido:**

A continuación, se muestran algunos ejemplos de reconstrucciones bajo la presencia de reflejos.

<img src="media/validacion_reflejos.png" alt="Resultados prueba de reflejos" width="800"/>

&nbsp;

- **Sombras en el recorrido:**

A continuación, se muestran algunos ejemplos de reconstrucciones bajo la presencia de sombras.

<img src="media/validacion_sombras.png" alt="Resultados prueba de sombras" width="800"/>

&nbsp;


- **Iluminación reducida:**

A continuación, se muestran algunos *frames* de las reconstrucciones realizadas en casos de baja iluminación.

<img src="media/validacion_iluminacion.png" alt="Resultados prueba de baja iluminacion" width="800"/>

&nbsp;

También se aporta un **vídeo** de estos resultados: 

<a title="Validacion: baja iluminacion" href="https://youtu.be/eoNWFBYqqeo" target="_blank"><img src="https://img.youtube.com/vi/eoNWFBYqqeo/maxresdefault.jpg" alt="Validacion_iluminacion" width="500"/></a>

Enlace: https://youtu.be/eoNWFBYqqeo

&nbsp;

## Resultados ante modificaciones en el escenario

- **Objetos en medio del circuito:**

Algunas reconstrucciones con objetos en medio del circuito:

<img src="media/validacion_obj_dentro.png" alt="Resultados prueba con objetos en medio del circuito" width="800"/>

&nbsp;

- **Objetos fuera del circuito:**

A continuación, se muestran algunos ejemplos de reconstrucciones con objetos en la parte exterior del circuito.

<img src="media/validacion_obj_fuera.png" alt="Resultados prueba con objetos fuera del circuito" width="800"/>

&nbsp;

## Resultados ante lineas parcialmente ocultas

A continuación, se muestran algunos *frames* de las reconstrucciones realizadas con las líneas del circuito parcialmente ocultas.

<img src="media/validacion_lineas_ocultas.png" alt="Resultados prueba con objetos en medio del circuito" width="800"/>

&nbsp;

Estos resultados también se aportan en **vídeo**: 

<a title="Validacion: Lineas parcialmente ocultas" href="https://youtu.be/YT2HjIt6cu4" target="_blank"><img src="https://img.youtube.com/vi/YT2HjIt6cu4/maxresdefault.jpg" alt="Validacion_lineas_ocultas" width="500"/></a>

Enlace: https://youtu.be/YT2HjIt6cu4

&nbsp;

Por otro lado, también se aporta un **vídeo** mostrando el funcionamiento real del vehículo en estos casos: 

<a title="Validacion: Prueba real lineas parcialmente ocultas" href="https://youtu.be/PdNhqsk8-N0" target="_blank"><img src="https://img.youtube.com/vi/PdNhqsk8-N0/maxresdefault.jpg" alt="Validacion_lineas_ocultas_real" width="500"/></a>

Enlace: https://youtu.be/PdNhqsk8-N0

&nbsp;

## Resultados en escenario diferente

A continuación, se muestran algunos *frames* de la reconstrucción realizada por el sistema al cambiar el escenario:

<img src="media/validacion_obj_lineas.png" alt="Resultados prueba cambio escenario" width="800"/>
