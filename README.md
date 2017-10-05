# S-BOX: CoreXY 3D Printer


ATENCION ESTA VERSION SE ENCUENTRA EN DESARROLLO LEER los
detalles antes de utilizar los archivos de corte.



Este fork tiene como finalidad realizar una serie de
modificaciones a la excelente maquina diseñada por @aleioavanevcp que se
discuten en el hilo de Reprap argentina (link mas abajo)

A medida que se modifiquen los archivos se va a ir
especificando en cada revisión los cambios a realizar a saber:
 

Versión 2 ( S-BOX2)



* Posibilidad de tensionar los dos loops de correas de forma
individual luego de que todo está montado. (pendiente)

* Retoque de dimensiones para permitir configuraciones mas
flexibles (actualmente se estarían agregando 4 centímetros de ancho y 4 de
profundidad) (pendiente)

* Robustez del eje Z, se está convirtiendo el eje Z a barras
de 12mm, con dos alternativas de transmisión (varilla roscada de 5mm y tornillo
tipo Acme TR8) (pendiente)

* Modificación del carro X para hacerlo compatible con
diferentes diseños existentes de otras máquinas. (pendiente)

* Modificación del extrusor, el diseño de esa época quedo
anticuado para algunos filamentos, se van a proporcionar diferentes orificios
para montar algunas alternativas sugeridas, asi como el punto anterior
permitiría el montaje de un conjunto liviano (por ejemplo un titan) en el carro
X. (pendiente)


Versión 2.5 (S-BOX-XL)

* Mismos cambios que la versión 2 pero con
dimensiones ampliadas en el eje X para montar una cama caliente de 20x30cm
(también va a tener orificios para montar la cama de 20x20). Esto implica
también un refuerzo en el eje X y posiblemente implique migrar ambos ejes a
10mm.



Notas de versionado 

A medida que se modifique cada ítem se especificará en este
documento que se encuentra completado. Por último se realizará una prueba de
corte y ensamblado para dar por cerradas las versiones propuestas. Mi idea es
realizar las modificaciones que se discutan en el foro de reprap y mandar a
hacer un corte en mdf para probarlas, luego muy posiblemente convierta mi S-BOX
original en una S-BOX-XL 

Adicionalmente por ahora las instrucciones y
especificaciones van a estar en castellano por ahora.
 


![S-BOX](https://raw.githubusercontent.com/FabLabCordoba/S-Box-Core-XY/original/Doc/3D_Renders/isometric.png)


### Especificaciones
* Diseñada para corte por laser en acero de 1/8" 
* Estructura principal con pocas partes impresas
* Size: 380 mm(W) x 365 mm(D) x 395 mm(H) *** A MODIFICAR
* Posibilidad de cerrar con cortes de acrilico la maquina para mejorar la impresion de plasticos que requieran minimizar las corrientes de aire o necesien una atmósfera mas controlada
* RAMPS 1.4 ready
![S-BOX](https://raw.githubusercontent.com/FabLabCordoba/S-Box-Core-XY/original/Doc/3D_Renders/back.png)
* Print volume: 20 cm x 20 cm x ? cm  **** A MODIFICAR
![S-BOX](https://raw.githubusercontent.com/FabLabCordoba/S-Box-Core-XY/original/Doc/3D_Renders/bed.png)
* CoreXY system
![S-BOX](https://raw.githubusercontent.com/FabLabCordoba/S-Box-Core-XY/original/Doc/3D_Renders/coreXY.png)
* Bowden extruder for 1.75 mm filament *** A MODIFICAR
![S-BOX](https://raw.githubusercontent.com/FabLabCordoba/S-Box-Core-XY/original/Doc/3D_Renders/extruder.png)


### Subdirectorios

* Doc/ Documentacion 
* STL/ Partes impresas en el caso de que sean necesarias, asi como extras disponibles
* DXF/ Archivos para corte laser


### Links
* Link al hilo original del diseño en el foro Reprap: [[http://forums.reprap.org/read.php?276,533476](http://forums.reprap.org/read.php?276,533476)]
* Hilo de usuarios con construccion y mejoras propuestas: [[http://forums.reprap.org/read.php?276,563440](http://forums.reprap.org/read.php?276,563440)]


### LICENCIA
AGREGAR TIPO DE LICENCIA DE USO


### Créditos
* Alejandro Iovane [[@aleiovanevcp](https://github.com/aleiovanevcp)] - Creador 
* Alejandro Daniel Cragnolini [[@alejandrocragnolini](https://github.com/alejandrocragnolini)] - Documentation
* Karim Kfoure [[@karimkfoure](https://github.com/karimkfoure)] - Documentation

---
![S-BOX](https://raw.githubusercontent.com/FabLabCordoba/S-Box-Core-XY/original/Doc/3D_Renders/front.png)
