# Java
### 1) ¿Qué son los modificadores de acceso?
Son los controladores de encapsulamiento de clases. Restringen el acceso entre clases a los metodos y objetos de otras.
En Java son 4.
- public   
- private  
- default  
- protected

### 2) Alcances
Se definen metodos exclusivos para una clase y se puede ocultar codigo para evitar el acceso. De ese modo se puede dar un comportamiento a una clase padre que no podra heredarse a las clases hijas.


### 3) ¿Cuándo se pueden usar y dónde?
- public

Se puede acceder desde cualquier clase, pertenezca o no al paquete en el que se encuentra el elemento.

- default

Si no se elige ningun modificador, solo se podra acceder a clases que estan dentro del mismo paquete.

- protected

Pueden usarse los elementos del mismo paquete y desde cualquier clase que extienda la clase en que se encuentra.

- private

Solo pueden ser accedidos desde la misma clase en la que se encuentran.

# CamelCase

### 1)¿Qué es CamelCase?, y ejemplos.

Un conjunto de reglas o convenciones para facilitar la lectura de codigo (a los programadores, ya que para el compilador no es necesario) y diferenciar una clase, metodo, variable o constante. El nombre viene de unir palabras (sin dejar espacios), lo cual asemeja la joroba de un camello.

### 2) ¿Qué es CamelCase Upper?, y ejemplos. (CamelCase)

En una sola linea, las iniciales de las palabras que unimos son en mayusculas y el resto de cada palabra ira en minusculas.
Esto sirve para las clases. como:

- default class EstoEsUnEjemplo;

- protected class AccesoAMetodo;

- private class TestDeCodigo;

### 3) ¿Qué es CamelCase Lower?, y ejemplos. (camelCase)

En este caso, la primera palabra estara en minusculas. Si consiste en más palabras, estas seguiran la convencion anterior. Es decir, escribiran su inicial en mayuscula y el resto de la palabra en minusculas.
Sirve para metodos y variables.

#### Metodo:

- Math.**sqrt**()

- Character.**isDigit**()


#### Variable:

- int **valorInicial** = 0;

- String **nombreDelPadre** = "John Doe";
