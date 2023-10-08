# BackEndModulo1

# Caso básico

Este es el caso básico: 

![imagen](./content/casobasico.png)


Lo que he tenido en cuenta: 

- He creado la entidad "Course", he tenido las siguientes consideraciones: 
    1. He embebido la información necesaria de las lecciones, en la cual, asu vez, he embebido el nombre del autor.
    2. He creado el campo calculado isNovelty para considerarlo novedad. 
    

- He creado la entidad "Lesson", he tenido en cuenta las siguientes consideraciones: 
    1. He embebido la información del autor e id para poder navegar a su biografía.
    2.He embebido la información del curso para poder mostrar el índice.

- He creado la entidad "Autor": 
    - La entidad tiene una colección de ids de los cursos. Supongo que no es necesario embeber la información de los cursos ya que no se va a consultar con frecuencia. 
