1. Resuma en un párrafo corto el modelo que decidió resolver:

 En este modelo se tiene una clase padre llamada Vehiculo, esta clase tiene com atributos base la marca, el color y el año de fabricacion del vehiculo que son atributos que comparten la mayoría de los vehiculos hoy en día. Luego, esta clase padre se divide en 3 diferentes clases hijas llamdas Moto, Carro y Bus. Estas clases, a parte de tener los atributos que heredan de su padre, también poseen los siguientes atributos:

Moto: 
- Tipo de llantas (si es de montaña, pista, etc).
- Cilindraje del motor cantidad en centímetros cúbicos (entero).
- Tiempos del motor (2 o 4 tiempos).

Carro:
- Número de puertas.
- Tipo de combustible (diesel, gasolina).
- Número de cambios.

Bus:
- Número de pasajeros que caben en el bus.
- Número de pisos, en el caso de que haya buses de dos pisos por ejemplo.
- Un booleano para saber si el bus cuenta con wifi incorporado.

2. Explique por qué se puede aplicar herencia en este caso: 

Como se vio anteriormente, acá la herencia es útil, ya que, a pesar de que cada vehículo cuenta con sus propias características que lo distinguen de los demás, hay otras que se comparten entre todos, como lo puede ser el color. De esta forma se puede reutilizar el código y no se tiene que crear una clase desde cero cada vez, sino que ya se cuenta con una base sobre la cual trabajar.
Este modelo presenta la forma de Vehiculo->Moto, Vehiculo->Carro y Vehiculo->Bus. Lo cual hace este ejemplo perfecto para explicar la herencia de un solo padre a varios hijos a la vez.



