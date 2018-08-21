# Metodo-de-Relajacion

## Descripción del Método. 

El método de relajación, más comunmente conocido como SOR por sus siglas es inglés, es una variante que se obtiene a partir de extrapolación del método de Gauss-Seidel[1], que una técnica para resolver sistemas de n ecuaciones lineales de la forma:  <a href="https://www.codecogs.com/eqnedit.php?latex=A\mathbf&space;x&space;=&space;\mathbf&space;b" target="_blank"><img src="https://latex.codecogs.com/gif.latex?A\mathbf&space;x&space;=&space;\mathbf&space;b" title="A\mathbf x = \mathbf b" /></a> , mediante la iteración: 


<a href="https://www.codecogs.com/eqnedit.php?latex=L_*&space;\mathbf{x}^{(k&plus;1)}&space;=&space;\mathbf{b}&space;-&space;U&space;\mathbf{x}^{(k)}f" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L_*&space;\mathbf{x}^{(k&plus;1)}&space;=&space;\mathbf{b}&space;-&space;U&space;\mathbf{x}^{(k)}f" title="L_* \mathbf{x}^{(k+1)} = \mathbf{b} - U \mathbf{x}^{(k)}f" /></a>





En SOR, la extrapolación se hace mediante un promedio ponderado entre la solución en la iteración previa y iteración actual obtenida a partir de método de Gass-Seidel[2]. 

## Algoritmo.  

## Deducción de la fórmula. 

## Condiciones de Convergencia. 

## Implementación. 


## Bibliografía. 

[1]. https://en.wikipedia.org/wiki/Gauss–Seidel_method

[2]. http://mathworld.wolfram.com/SuccessiveOverrelaxationMethod.html

[3]. https://en.wikipedia.org/wiki/Successive_over-relaxation#Convergence
