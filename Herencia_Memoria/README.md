1. Resuma en un párrafo corto el modelo que decidió resolver:

- En este caso, se decidió resolver el modelo de Memoria, basicamente es un conjunto de tipos de memoria. La clase Padre tiene como atributos el precio y la capacidad de la memoria. Esta clase padre tiene 3 clases hijas, las cuales son RAM, Cache y MemoriaPrincipal, cada una con sus atributos propios. Memoria principal, a su vez, tiene dos clases hijas llamadas SSD y HDD las cuales tambien tienen sus atributos propios sumados a los heredados de las dos clases que están arriba de ellas.


2. Explique por qué se puede aplicar herencia en este caso: 

- En este caso la herencia se puede usar porque existe una jerarquía de clases, Memoria hereda sus atributos a RAM, Cache y MemoriaPrincipal, además, se cuenta con un segundo nivel de herencia donde MemoriaPrincipal hereda sus atributos a las clases HDD y SSD. Esto permite ahorrar tiempo y líneas de código en mayor o menor medida, dependiendo de cuantas clases, atributos y métodos sean partícipes de esta herencia. Todos los caminos que se podrían recorrer desde el padre hasta la clase más baja de la jerarquía serían: Memoria->RAM, Memoria->Cache, Memoria->MemoriaPrincipal->HDD, Memoria->MemoriaPrincipal->SDD.

Los atributos de cada una de las clases de esta jerarquía son:

Memoria:
- Precio
- Capacidad de la memoria

RAM:
- Frecuencia
- Tipo de DDR

Cache:
- Tipo de cache 

MemoriaPrincipal:
- Tipo de conexión (PCI-E, SATA)

HDD:
- RPM

SSD:
- Velocidad de lectura
- Velocidad de escritura