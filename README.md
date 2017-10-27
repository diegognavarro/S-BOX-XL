# S-BOX-XL: CoreXY 3D Printer


ATENCION ESTA VERSION SE ENCUENTRA EN DESARROLLO LEER los
detalles antes de utilizar los archivos de corte.



Este fork tiene como finalidad realizar una serie de
modificaciones a la excelente maquina diseñada por @aleioavanevcp que se
discuten en el hilo de Reprap argentina (link mas abajo)

A medida que se modifiquen los archivos se van a ir
especificando en cada revisión. Los cambios propuestos a realizar a son:
 
 
![SBOX-XL](https://i.imgur.com/tgVSHT1.png)


Versión 2.5 ( S-BOX-XL)



* Posibilidad de tensionar los dos loops de correas de forma
individual luego de que todo está montado. (modificado)

![SBOX-XL](https://i.imgur.com/4Ty3gyB.png)

* Ampliacion de las dimensiones para permitir configuraciones mas
flexibles de carro y soporte de cama calientes de 20x20 o 20x30. (modificado)


Nuevas dimensiones:
El recorrido teórico del carro es de x = 305, Y=230 Z=275
*** ACTUALIZAR!!! Las dimensiones de la maquina son: 528 x 410 x 420
Varillas de 10 en eje X e Y
Varillas de 12 en eje Z

* Robustez del eje Z, se está convirtiendo el eje Z a barras
de 12mm, con dos alternativas de transmisión (varilla roscada de 5mm y tornillo
tipo Acme TR8) (modificado)

Varillas de 12 en eje Z

![SBOX-XL](https://i.imgur.com/wF26sgF.png)


* Modificación del carro X para hacerlo compatible con
diferentes diseños existentes de otras máquinas. (modificado)

![SBOX-XL](https://i.imgur.com/nP22Bky.png)


* Modificación del extrusor, el diseño de esa época quedo
anticuado para algunos filamentos, se van a proporcionar diferentes orificios
para montar algunas alternativas sugeridas, asi como el punto anterior
permitiría el montaje de un conjunto liviano (por ejemplo un titan) en el carro
X. (modificado)

Dado que la maquina en general se opera por delante, se considera mas "comodo" (es subjetivo pero queda asi) que el extrusor (o posibles 2 extrusores) queden en los laterales de la maquina en vez de la parte posterior. En los cortes laterales se va a dejar la posibilidad de montar un soporte para rollos o una varilla para usarla de soporte, asi como un sector para montar el extrusor. Esto da flexibilidad de usar ambos, uno solo o directamente montar un extrusor sobre el carro que ahora es mas grande y lo soportaría.


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

La versión S-BOX-XL está actualizada según discusiones en el thread de RepRap Argentina:
* Reprap Argentina [[http://forums.reprap.org/read.php?276,563440](http://forums.reprap.org/read.php?276,563440)]

S-BOX-XL está basada directamente sobre el diseño original de Alejandro Iovane de la S-BOX (https://github.com/aleiovanevcp/S-Box-Core-XY), asi commo la documentación original y el armado del repositorio corresponden a Karim Kfoure y Alejandro Daniel Cragnolini. 
