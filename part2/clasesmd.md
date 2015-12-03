# Mapa de Clases


## Clases de objetos



Para la propuesta de diseño de esta plataforma hay que tener en cuenta los elementos que interactúan y se relacionan los cuales forman parte de esta plataforma. Estos elementos son denominados objetos, los cuales poseen características propias denominadas atributos, los cuales permiten la identificación de tipos de objetos.

Los objetos que forman parte de esta plataforma web son:


### Usuarios



La plataforma define a los usuarios de la siguiente manera:

**usuarios**: Son las personas registradas en la plataforma, habilitadas para crear presentaciones y editar. Este se clasifica en dos tipos de usuarios:

**alumno**: Usuario principal de la plataforma, son los que crean, editan, comparten las presentaciones. Pueden editar las propias y si están en colaboración.

**profesor**: Usuario habilitado para supervisar varias presentaciones. Es responsable de la creación de grupos.

Estos dos tipos de usuarios se subclasifican en dos tipos:

**autor**: Usuario creador de una presentación.

Estos usuarios pueden agruparse de la siguiente manera:

**institución**: Agrupación mayor, la cual está identificada por el nombre de la institución a la que pertenecen los usuarios alumno/profesor.

**cursos**: agrupación dentro de institución, la cual está identificada según el curso o clase a la que pertencen los usuarios alumno/profesor

**grupos**: agrupación dentro de curso, la cual está definida por el tema de la presentación, otorgada por los usuarios alumno/profesor.

Estos usuarios tras una previa investigación ingresan a la plataforma unos elementos para organizar cronológica y espacialmente para crear la presentación. Estos elementos son denominados “*hechos*”.


### Hechos



Un **hecho** es un “*acontecimiento; interrupción o alteración histórica, social o política del curso normal de los sucesos, y que por sus efectos contemporáneos o influencia en hechos futuros, exige ser recordado*”.

Por lo que estos son los elementos los cuales a través de su relación con otros hechos puede visualizarse en un recorrer cronológico de sucesos en distintos periodos y lugares alrededor del mundo.

Estos hechos poseen las siguientes características principales:


#### Tiempo



Una de las carteristas de los hechos es su ubicación cronológica en el devenir del tiempo, por ello estos hechos pueden contar con las siguientes características temporales:

**día, mes, año, década, siglo, milenio, a.c** y **d.c**

Con el propósito de facilitar la organización y búsqueda de información, me he basado en la organización historeográfica organizando la información de la siguiente manera:

* Historia por edades:
1. Edad Antigua
2. Edad Contemporánea
3. Edad Media
4. Edad Moderna

Historia por Grandes Civilizaciones:
Griega
Egipcia
Romana
Babilónica
Persa
China
India
Mayas
Inca
Azteca

Historia por Grandes Eventos:
Colonialismo
Imperialismo
Revolución Industrial
Revolución Francesa
Revolución Rusa
Primera Guerra Mundial
Segunda Guerra Mundial

Así como segementar la búsqueda con la selección temporal centrada sólo en los continentes:

Siglos por Continente:
Siglos en África
Siglos en América
Siglos en Asia
Siglos en Europa
Siglos en Oceanía

