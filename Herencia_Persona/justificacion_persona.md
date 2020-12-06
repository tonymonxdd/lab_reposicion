1. Resuma en un párrafo corto el modelo que decidió resolver:

En este caso, se decidió resolver el modelo de Persona, la cual tiene como atributos base, la Edad y el Nombre. De Persona se heredan estos dos atributos para otra clase, llamada Estudiante, la cual, va a tener también dos atributos extra que serán la nota y el número de carné estudiantil. Por último, de Estudiante se heredan estos 4 atributos ya mencionados (los 2 de Persona y los 2 nuevos de Estudiante) para crear una nueva clase llamada EstudianteUniversitario, el cual posee un nuevo atributo que define la carrera que cursa el estudiante.

El modelo quedaría así:

Persona: 
- Nombre.
- Edad.

Estudiante:
- Nombre.
- Edad.
- Número de carné.
- Nota.

Estudiante Universitario:
- Nombre.
- Edad.
- Número de carné.
- Nota.
- Carrera

2. Explique por qué se puede aplicar herencia en este caso: 

La herencia en este modelo es útil ya que se puede derivar a partir de persona muchas clases distintas con la ventaja de ahorrar tiempo reutilizando código. No solo se puede derivar en estudiante y tipos de estudiante, sino que también se podría derivar en otros tipos de personas, como profesores, conserjes, personal administrativo, etc. En este caso se decidió hacer la secuencia Persona->Estudiante->EstudianteUniversitario solamente para mostrar lo que sería la herencia a más de un nivel, ya que en otros ejemplos se mostrará tambien la herencia a varias clases distintas a un solo nivel y a varios niveles.

