# Ping Xiao Po Portfolio
### Curso web HTML+CSS

##### Aspectos a tener en cuenta para facilitar la corrección:

1. Flexbox se usa en la mayoría de los contenedores con varios elementos, tanto para facilitar el comportamiento responsivo: jugando con propiedades como el flex-basis y el flex-grow para que los elementos crezcan junto con el contenedor pero que a la vez tengan un tamaño mínimo ya que si no acabarían todos en la misma línea (skills y formulario); como para alinear correctamente todo.

2. Teniendo en cuenta el punto anterior, en las media queries solo cambiamos los tamaños de los contenedores superiores, ya que solo con eso todos los demás elementos se van a adaptar solos para que se vea mejor en una resolución móvil. Además, para resoluciones pequeñas los elementos de la barra de navegación de la izquierda se ocultan y se centra la foto de la izquierda.

3. En el index.html, entrando al body, nos encontramos lo siguiente, en orden: 
  * Contenedor de la barra de navegación
  * Contenedor main con la secciones de la descripción y las habilidades
  * Sección banner, la imagen que nos lleva a los proyectos
  * Formulario en el que agrupamos los primeros 4 inputs en 1 contenedor, luego tenemos varios de tipo radio agrupados en otro contenedor, y 3 contenedores más, uno por cada pareja input+label restante y el tercero de estos se corresponde con el que contiene los botones
  * Por último tenemos el contenedor del footer

4. En el projects.html: 
  * Contenedor de la barra de navegación
  * Contenedor main, primero con un vídeo y luego la sección de proyectos, que es donde único se ha usado grid, en concreto un tipo que nos permite también que tenga un diseño responsivo ya que las celdas se "crean" automáticamente según el espacio disponible
  * Por último tenemos el contenedor del footer

5. En la descripción, en el final, la parte: "(spoiler)" es un checkbox oculto al que se le han creado en css elementos :checked y :hover

6. En principio el CSS no debe ser muy difícil de seguir pues he usado clases con nombres bastante representativos, además de que se ha tratado de seguir el orden de la estructura del HTML. En caso de pérdida buscar los comentarios del tipo /* -------footer------- */, que sirven de guía para los contenedores de orden superior. Los del tipo /* description----------- */ son para los subcontenedores.