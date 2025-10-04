# Método de Newton-Raphson
## $\to$ O Fundamento Matemático:
* O objetivo do método de Newton-Raphson é encontrar as raízes (ou "zeros") de uma função $f(x)$, ou seja, encontrar os valores de $x$ para os quais $f(x)=0$.
 
* A ideia é começar com uma "chute" inicial $x_{0}$ que acreditamos estar próximo da raiz. A partir daí, usamos a reta tangente ao gráfico de $f(x)$ no ponto $(x_{0}, f(x_{0}))$ para encontrar uma aproximação melhor, $x_{1}$. 

* A raiz dessa reta tangente será a nossa próxima estimativa. Repetimos esse processo iterativamente. 

* A fórmula de recorrência que define o método é:

$$\boxed{x_{n+1} = x_{n} - \frac{f(x_{n})}{f'(x_{n})}}$$

$\to$ Onde:

- $x_{n+1}$ é a próxima (e melhor) aproximação da raiz;
- $x_{n}$ é a aproximação atual;
- $f_{x_{n}}$ é  valor da função atual;
- $f'(x_{n})$ é o valor da derivada da função na aproximação atual.

Paramos o processo quando $x_{n+1}$ e $x_{n}$ se torna muito pequena, ou seja, quando atingimos a precisão desejada.
