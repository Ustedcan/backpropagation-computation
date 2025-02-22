# __Backpropagation Computation with Micrograd__

__Implementación de una Computación con Backpropagation usando Micrograd__  

__Indicaciones:__  
Implementar la expresión matemática dada en Python utilizando la biblioteca micrograd, asegurando que los valores sean correctamente almacenados como nodos computacionales y que el cálculo de gradientes se realice de manera automática mediante backpropagation. 

La ecuación a implementar es:  

$$ L = \left( (a \times b + c)^2 + d + e \times f \right) \times g $$


Donde: 

$$
a = 2, \quad b = 3, \quad c = 1, \quad d = 1, \quad e = 4, \quad f = 2, \quad g = 5
$$

Se debe realizar el cálculo del gradiente de L con respecto a todas las variables mediante backpropagation

Requerimientos: 
1. Definir las variables como instancias de Value de micrograd, asegurando que cada 
variable tenga una etiqueta representativa. 
2. Construir la expresión matemática paso a paso en código, asegurando que cada 
operación intermedia tenga una etiqueta clara. 
3. Realizar la backpropagation para obtener los gradientes de todas las variables 
involucradas en la ecuación.
