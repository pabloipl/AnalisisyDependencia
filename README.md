Integrantes: Pablo Pérez

1.- Clases:

Calculadora: Representa una calculadora con las operaciones sumar y multiplicar.

CarroCompra: Genera una simulación de un carro de compra donde usará la clase Calculadora para sumar y multiplicar los productos a incluir en el total.

2.- 

Calculadora:

-Atributos: int n1 y n2
Métodos: 
Calculadora(),Calculadora(int num1, int num2), sumar(), multiplicar(), setN1(), setN2()

CarroCompra:

Atributos: 
int[][] productos

Métodos: 
CarroCompra(), calcularTotal(), subTotal(), mostrarTotal().

En ambos casos tenemos atributos private ya que estos serán usadas en la misma clase y no externamente.

También se ve que CarroCompra dependerá de Calculadora y que necesitará llamar  sus métodos para cumplir ciertas funciones.