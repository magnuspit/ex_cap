MEMORIA - WEB SEMÁNTICA Y DATOS ENLAZADOS

1. INTRODUCCIÓN

El propósito de este trabajo es desarrollar y explicar el proceso de enlazar datos de acuerdo a lo aprendido a lo largo de la asignatura. Una vez los datos estén adecuadamente 
enlazados se comentará también cómo se podrían explotar.

La idea base del proyecto ha sido la de utilizar una lista de las mejores películas de la historia con la idea de enlazarlas sobre una base de conocimiento existente que 
facilitase más detalles sobre cada título. Se simplificará el trabajo (volumen de datos) para ganar eficiencia, pero se pondrá especial atención en que todos los puntos de la memoria sean satisfechos.

2. PROCESO DE TRANSFORMACIÓN

A. FUENTE DE DATOS

Se ha utilizado la lista el ranking TSPDT’s 1,000 Greatest Films que se puede encontrar en el siguiente enlace en formato Microsoft Excel: https://www.theyshootpictures.com/resources/1000GreatestFilms.xls (se ha incluido en la carpeta "Anexos"). Esta lista se actualiza con carácter anual y es utilizada frecuentemente por los medios de comunicación.

B. ANÁLISIS DE LOS DATOS

El conjunto de datos consiste en 10 columnas y 1.0001 registros, siendo el primero una cabecera. A continuación se muestra un resumen de la información de cada columna:
- Pos: muestra la posición numérica de la película en un rango de 1 a 1000. 
- 2019: lo mismo que la columna anterior, pero en la lista de 2019.
- 2018: lo mismo que la columna anterior, pero en la lista de 2018.
- Title: el título de la película. Los artículos van al final, después de ",".
- Director: el director de la película en formato: Apellido, Nombre.
- Year: el año de lanzamiento de la película.
- Country: el país de la producción.
- Length: duración de la película.
- Genre: el género al que pertenece la película. Puede ser multigénero separado por "-".
- Colour: indica si es en color (Col), blanco y negro (BW) o ambos (Col-BW).

Con respecto a la licencia de los datos, la web no especificaba el tipo de licencia bajo el que podían ser usadas las listas. Se ha contactado al administrador para aclarar este punto. Se actualizará en cuanto responda.

C. ESTRATEGIA DE NOMBRADO

