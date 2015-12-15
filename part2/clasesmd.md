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

Estos hechos poseen las siguientes características principales:

* Nombre
* Fecha Inicio
* Fecha Termino 
* Lugar
* Descripción
* Tema

###Personajes

Los personajes corresponden a aquellas personas que debido a sus conocimientos y acciones, han influenciado en el devenir de la historia tanto regional como universal.

Estos contienen primeramente las siguientes características:

* Nombre
* Nacimiento
* Lugar Nacimiento
* Fallecimiento
* Lugar Fallecimiento 
* Causa de muerte
* Nacionalidad
* Ocupación
* Relevancia
* Tema

Ademas de estar clasificadas a su vez por el tema que lo identifica dentro del ramo del conocimiento o aporte que han realizado:

* **cultura**: artistas, filósofos.
* **científico**: inventores, descubridores.
* **politico**: gobernantes, guerreros, cargos políticos y  militares.
* **religioso**: sacerdotes, guías espirituales, teólogos.


