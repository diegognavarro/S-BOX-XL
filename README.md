# S-BOX-XL: CoreXY 3D Printer


ATENCION ESTA VERSION SE ENCUENTRA EN DESARROLLO LEER los
detalles antes de utilizar los archivos de corte.



Este fork tiene como finalidad realizar una serie de
modificaciones a la excelente maquina diseñada por @aleioavanevcp que se
discuten en el hilo de Reprap argentina (link mas abajo)

A medida que se modifiquen los archivos se van a ir
especificando en cada revisión. Los cambios propuestos a realizar a son:
 

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
también un refuerzo en el eje X y posiblemente implique migrar ambos ejes a 10mm. (Pendiente) Recién va a ser realizada una vez completados los puntos de la version 2, la idea es solamente extender 10 centímetros el diseño de la 2 y generar un soporte de cama con los nuevos orificios.


### En Principio posiblemente la versión 2.0 no se publique, dado que ya se está actualizando la version mk2 por Karim Kfoure y Alejandro Daniel Cragnolini por lo que esta rama luego quedará depurada como S-BOX-XL directamente uniendo las versiones 2.0 y 2.5

Notas de versionado 
A medida que se modifique cada ítem se especificará en estedocumento que se encuentra completado. Por último se realizará una prueba decorte y ensamblado para dar por cerradas las versiones propuestas. La idea esrealizar las modificaciones que se discutan en el foro de reprap y mandar ahacer un corte en mdf para probarlas. Luego se documentará una versión definitiva (ya sea con la version 2.5 o la 2) con el corte realizado en acero con su respectiva pintura al horno. 
Adicionalmente por ahora las instrucciones yespecificaciones van a estar en castellano por ahora, dado que todas las discuciones se originan en el foro de argentina, luego se podría generar una traducción al inglés. 


### Especificaciones
* Diseñada para corte por laser en acero de 1/8" 
* Estructura principal con pocas partes impresas
* Size: 380 mm(W) x 365 mm(D) x 395 mm(H) *** A MODIFICAR
* Posibilidad de cerrar con cortes de acrilico la maquina para mejorar la impresion de plasticos que requieran minimizar las corrientes de aire o necesien una atmósfera mas controlada
* RAMPS 1.4 ready
* Print volume: 20 cm x 20 cm x ? cm  **** A MODIFICAR
* CoreXY system
* Bowden extruder for 1.75 mm filament *** A MODIFICAR


### Subdirectorios

* Doc/ Documentacion 
* STL/ Partes impresas en el caso de que sean necesarias, asi como extras disponibles
* DXF/ Archivos para corte laser


### Links
* Link al hilo original del diseño en el foro Reprap: [[http://forums.reprap.org/read.php?276,533476](http://forums.reprap.org/read.php?276,533476)]
* Hilo de usuarios con construccion y mejoras propuestas: [[http://forums.reprap.org/read.php?276,563440](http://forums.reprap.org/read.php?276,563440)]


### LICENCIA
CC BY-SA 3.0
https://creativecommons.org/licenses/by-sa/3.0/

#### Créditos S-BOX-XL
S-BOX-XL está basada directamente sobre el diseño original de Alejandro Iovane de la S-BOX (https://github.com/aleiovanevcp/S-Box-Core-XY), asi commo la documentación original y el armado del repositorio corresponden a Karim Kfoure y Alejandro Daniel Cragnolini. 

La versión S-BOX-XL fué actualizada según discusiones en el thread de RepRap Argentina:

* Reprap Argentina [[http://forums.reprap.org/read.php?276,563440](http://forums.reprap.org/read.php?276,563440)]


