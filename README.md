# Metodo-de-Relajacion

## Descripción del Método. 

El método de relajación, más comunmente conocido como SOR por sus siglas es inglés, es una variante que se obtiene a partir de extrapolación del método de Gauss-Seidel[1], que es una técnica para resolver sistemas de <a href="https://www.codecogs.com/eqnedit.php?latex=n" target="_blank"><img src="https://latex.codecogs.com/gif.latex?n" title="n" /></a> ecuaciones lineales de la forma:  <a href="https://www.codecogs.com/eqnedit.php?latex=A\mathbf&space;x&space;=&space;\mathbf&space;b" target="_blank"><img src="https://latex.codecogs.com/gif.latex?A\mathbf&space;x&space;=&space;\mathbf&space;b" title="A\mathbf x = \mathbf b" /></a> , mediante la iteración: 


<a href="https://www.codecogs.com/eqnedit.php?latex=x^{(k&plus;1)}_i&space;=&space;\frac{1}{a_{ii}}&space;\left(b_i&space;-&space;\sum_{j=1}^{i-1}a_{ij}x^{(k&plus;1)}_j&space;-&space;\sum_{j=i&plus;1}^{n}a_{ij}x^{(k)}_j&space;\right),\quad&space;i=1,2,\dots,n" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x^{(k&plus;1)}_i&space;=&space;\frac{1}{a_{ii}}&space;\left(b_i&space;-&space;\sum_{j=1}^{i-1}a_{ij}x^{(k&plus;1)}_j&space;-&space;\sum_{j=i&plus;1}^{n}a_{ij}x^{(k)}_j&space;\right),\quad&space;i=1,2,\dots,n" title="x^{(k+1)}_i = \frac{1}{a_{ii}} \left(b_i - \sum_{j=1}^{i-1}a_{ij}x^{(k+1)}_j - \sum_{j=i+1}^{n}a_{ij}x^{(k)}_j \right),\quad i=1,2,\dots,n" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=L_*&space;\mathbf{x}^{(k&plus;1)}&space;=&space;\mathbf{b}&space;-&space;U&space;\mathbf{x}^{(k)}f" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L_*&space;\mathbf{x}^{(k&plus;1)}&space;=&space;\mathbf{b}&space;-&space;U&space;\mathbf{x}^{(k)}f" title="L_* \mathbf{x}^{(k+1)} = \mathbf{b} - U \mathbf{x}^{(k)}f" /></a>

Donde: 

<a href="https://www.codecogs.com/eqnedit.php?latex=A=\begin{bmatrix}&space;a_{11}&space;&&space;a_{12}&space;&&space;\cdots&space;&&space;a_{1n}&space;\\&space;a_{21}&space;&&space;a_{22}&space;&&space;\cdots&space;&&space;a_{2n}&space;\\&space;\vdots&space;&&space;\vdots&space;&&space;\ddots&space;&&space;\vdots&space;\\a_{n1}&space;&&space;a_{n2}&space;&&space;\cdots&space;&&space;a_{nn}&space;\end{bmatrix},&space;\qquad&space;\mathbf{x}&space;=&space;\begin{bmatrix}&space;x_{1}&space;\\&space;x_2&space;\\&space;\vdots&space;\\&space;x_n&space;\end{bmatrix}&space;,&space;\qquad&space;\mathbf{b}&space;=&space;\begin{bmatrix}&space;b_{1}&space;\\&space;b_2&space;\\&space;\vdots&space;\\&space;b_n&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?A=\begin{bmatrix}&space;a_{11}&space;&&space;a_{12}&space;&&space;\cdots&space;&&space;a_{1n}&space;\\&space;a_{21}&space;&&space;a_{22}&space;&&space;\cdots&space;&&space;a_{2n}&space;\\&space;\vdots&space;&&space;\vdots&space;&&space;\ddots&space;&&space;\vdots&space;\\a_{n1}&space;&&space;a_{n2}&space;&&space;\cdots&space;&&space;a_{nn}&space;\end{bmatrix},&space;\qquad&space;\mathbf{x}&space;=&space;\begin{bmatrix}&space;x_{1}&space;\\&space;x_2&space;\\&space;\vdots&space;\\&space;x_n&space;\end{bmatrix}&space;,&space;\qquad&space;\mathbf{b}&space;=&space;\begin{bmatrix}&space;b_{1}&space;\\&space;b_2&space;\\&space;\vdots&space;\\&space;b_n&space;\end{bmatrix}" title="A=\begin{bmatrix} a_{11} & a_{12} & \cdots & a_{1n} \\ a_{21} & a_{22} & \cdots & a_{2n} \\ \vdots & \vdots & \ddots & \vdots \\a_{n1} & a_{n2} & \cdots & a_{nn} \end{bmatrix}, \qquad \mathbf{x} = \begin{bmatrix} x_{1} \\ x_2 \\ \vdots \\ x_n \end{bmatrix} , \qquad \mathbf{b} = \begin{bmatrix} b_{1} \\ b_2 \\ \vdots \\ b_n \end{bmatrix}" /></a>


En SOR, la extrapolación se hace mediante un promedio ponderado entre la solución en la iteración previa y iteración actual obtenida a partir de método de Gass-Seidel[2]. 

<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{x}^{(k)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{x}^{(k)}" title="\mathbf{x}^{(k)}" /></a> es la k-ésima iteración o aproximación de  es la siguiente iteración y la matriz  se descompone en una matriz triangular superior y en una matriz que es la suma de una matriz triangular inferior y una matriz diagonal. 


## Algoritmo.  

## Deducción de la fórmula. 

## Condiciones de Convergencia. 

## Implementación. 


## Bibliografía. 

[1]. https://en.wikipedia.org/wiki/Gauss–Seidel_method

[2]. http://mathworld.wolfram.com/SuccessiveOverrelaxationMethod.html

[3]. https://en.wikipedia.org/wiki/Successive_over-relaxation#Convergence
