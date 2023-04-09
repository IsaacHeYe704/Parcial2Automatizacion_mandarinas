# Parcial 2 de automatización y control de procesos.

*Isaac Herrera Yepes, Nicolas Canchon,Laura mayork y Sebastian Rivera*

## Introducción 

La automatización de procesos se ha convertido en una herramienta clave para aumentar la eficiencia y la productividad en todo tipo de organizaciones. Esta tecnología consiste en la aplicación de software y hardware para realizar tareas repetitivas y monótonas de forma autónoma, lo que permite que los empleados se centren en tareas de mayor valor agregado y creatividad. La automatización de procesos puede utilizarse en diversas áreas, desde la fabricación hasta la atención al cliente, pasando por la gestión de recursos humanos y finanzas. Gracias a sus beneficios, cada vez son más las empresas que están implementando esta tecnología en sus procesos, con el objetivo de mejorar su competitividad y adaptarse a un entorno cada vez más digitalizado.

Teniendo esto encuenta se ha desarrollado la implementación de la automatización del proceso de empaque de mandarinas de exportación para la empresa Fruver1A S.A.

## Proceso a automatizar: 

unos operarios reciben contenedores  con las  cosechas.  Seguido,  los  operarios colocan lasmandarinascon  calidad  de  exportación  (sin manchas,  grandes)sobre  una primera banda  transportadora.Otros  operarios recogenlas mandarinasde  laprimerabanda y las empacandentro de cajas, de a 50 mandarinascada una. Las cajas(vacías)están dispuestassobre una  segunda banda  transportadora,activada  de  forma  manual por  un  operarioa  medida  que  se  van llenandolascajas,para su posterior alistamiento y despacho. Las mandarinasque no son de exportación, pasan por un proceso similarpara el consumo local. Con la automatización, se busca aumentar la producción con calidad de exportación a 100 cajas diarias.


## Requerimientos del proyecto:

|Identificación del requerimiento funcional|RF-1|
|------------------------------------------|----|
|Nombre|Automatización del proceso.|
|Características|El sistema debe contar con sensores y actuadores.|
|Descripción|Automatizar el proceso utilizando PLC, sensores y actuadores.|
|Prioridad|Alta.|

|Identificación del requerimiento funcional|RF-2|
|------------------------------------------|----|
|Nombre|Banda transportadora contador|
|Características|El sistema debe contar con una banda transportadora.|
|Descripción|Se requiere una banda transportadora para trasladar las mandarinas desde la zona de recepción hasta la zona de empaque..|
|Prioridad|Alta.|

|Identificación del requerimiento funcional|RF-3|
|------------------------------------------|----|
|Nombre|Sistema de conteo|
|Características|El sistema debe contar las mandarinas en la caja ctual|
|Descripción| Se necesita un sistema de empaque automático que permita empacar las mandarinas en cajas de forma eficiente y precisa. |
|Prioridad|Alta.|

|Identificación del requerimiento funcional|RF-4|
|------------------------------------------|----|
|Nombre|Sistema de activación de banda transportadora|
|Descripción|Se necesita un sistema para activar la banda transportadora de las mandarinas para pasar a su conteo |
|Prioridad|Alta.|

|Identificación del requerimiento funcional|RF-5|
|------------------------------------------|----|
|Nombre|Funcionamiento seguro e inmediato|
|Descripción|El botón de pausa debe estar diseñado para detener el proceso de manera inmediata y segura ante cualquier contingencia o problema que se presente durante la producción |
|Prioridad|Alta.|

## Etapas del diseño


Los siguientes pasos se llevaron a cabo para implementar el diseño de la solución:

1.	Identifiación de entradas, salidas y variables internas:


![Diagrama de variables](/diagramas/diagrama%20de%20variables.png)

2.	Diseño del diagrama de estados para indentificar los estados de las entradas y salidas del proceso:

![Diagrama de estados](/diagramas/diagramaDeEstados.png)

3. diseño de la logica lader

**Definición de variables en CODESYS:**




 
**Diseño del sistema en CODESYS:**
 





**Definición de las variables en PLC: **
   


**Diseño del sistema PLC: **


4. Diseño del diagrama de las conecciones electrcas




 

5.	Prototipo fisico: 





**Diagrama de actividades: **

[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](https://youtu.be/T-D1KVIuvjA)
