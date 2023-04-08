# Parcial 2 de automatización y control de procesos.

*Isaac Herrera Yepes, Nicolas Canchon,Laura mayork y Sebastian Rivera*

## Introducción 



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

2.	Diseño del diagrama de estados para indentificar los estados de las entradas y salidas del proceso

3. diseño de la logica lader

**Definición de variables en CODESYS:**




 
**Diseño del sistema en CODESYS:**
 





**Definición de las variables en PLC: **
   


**Diseño del sistema PLC: **


4. Diseño del diagrama de las conecciones electrcas




 

5.	Prototipo fisico: 





**Diagrama de actividades: **

