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
