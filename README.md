![c708d443-d98a-429c-af57-3ca795dbb1a7](https://github.com/Bellezatabaskena/Simulacion/assets/114634159/515cb40b-872f-47a5-824d-b2597bf7e7c9)


                                                       

                                                           Perla Mendo López

                                      6A Licenciatura en Ingeniería en Sistemas Computacionales
                                 
                                                  Universidad del Sur, Plantel Cancún

                                      
                                                   Ing. Luis Fernando Villafaña Rejón
                                                  
                                                         Ingeniería de Software
                                              
                                                         28 de Octubre del 2023
# Ordenar Números

Programa en Python que recibe una cantidad por dia de la semana y devuelve la lista ordenada de menor a mayor y viceversa, suma el total de las cantidades recibidas y devuelve el dia con menor cantidad y el dia con mayor cantidad.

## Tabla de Contenido

- [Introducción](#introducción)
- [Características](#características)
- [Instalación](#instalación)
- [Uso](#uso)
- [Licencia](#licencia)

## Introducción

Es un programa súper sencillo en python en el cual, se le pide al usuario ingresar su nombre y posteriormente ingresar una cantidad entera o con decimales, por dia de la semana, el programa los ordenará de menor a mayor y también de mayor a menor, despues sumara las cantidades y tambien devolvera el dia con menor cantidad ingresada y el dia con mayor cantidad ingresada. Solo puede ingresar números, de otra manera el programa rompera el ciclo y pedira que ingrese una cantidad.

## Características
*  Se utiliza un arreglo definiendo los dias de la semana y otro para guardar las cantidades a ingresar, las cuales seran una por dia de la semana.
*  Se utiliza un ciclo "for", el cual contiene un ciclo "while" adentro, para ingresar las cantidades por día de la semana, y con condicionales "if", se localizan los días con mayor y menor cantidad. Tambien se utiliza un 
   "try , except" para identificar errores de usuario.
*  Con la función "sorted", ordena los números en una lista de una manera ascendente.
*  Con la función "reverse", ordena la lista de una manera descendente.
*  Con la función "sum" suma el total de las cantidades ingresadas.
  
## Instalación

Se ejecuta en google colab, sin instalación adicional.

## Uso
* Código inicial
* La ambigüedad es la cualidad de aquel lenguaje que puede entenderse de varios modos o admitir distintas interpretaciones y dar, por consiguiente, motivo a dudas, incertidumbre o confusión (La Ambigüedad - Pregrados Y Posgrados En Bogotá, n.d.).
* Lo que yo comprendo por ambigüedad en un sistema, es que el programador o desarrollador puede crear un programa, en el cual las instrucciones no son muy claras y al momento de llegar al usuario, este no sabe en si que es exactamente lo que necesita hacer, pues se crea una confusión.
* En el código que realicé en colab, el mes pasado, había declarado dos veces la variable "usuario", en la cual en la línea 3, se guardaba un nombre, y en el de la línea 6, se guardaba una serie de 5 números, a mi parecer , ahi yo misma tuve un problema de ambigüedad ya que la misma variable almacenaba dos cosas totalmente distintas, y como se puede apreciar en la línea 24 del código, al momento de volver a imprimir lo que estaba guardado en la variable “usuario”, pues el sistema imprimía lo último que se guardó lo cual era la serie de números a ordenar y no el nombre real del usuario.

![image](https://github.com/Bellezatabaskena/IngSoftware/assets/114634159/d3f021bd-c4c7-4df0-8619-e6b40abf6454)

* Entonces, fué necesario cambiar una de las variables, la que almacena la lista de números, ahora se llama “lista” y es de esta manera como el sistema funciona de manera adecuada, ya que imprime un nombre de usuario cuando es necesario, como se puede apreciar en las líneas 3 y 24, y también imprime una lista de números, como se nota en la línea 6.
  
![image](https://github.com/Bellezatabaskena/IngSoftware/assets/114634159/cf34aef9-384e-4943-9d28-b348faa2e79c)

* Código actualizado
* Continué trabajando en el código para mejorar su usabilidad y eficiencia, ya que se me ocurrió mejorarlo de manera, que pida un numero a ingresar por dia de la semana, ya que al momento de imprimir los resultados, pueda dar más detalles acerca de la lista de números ya ordenados, a parte de una lista de números ascendentes y otra descendente, este también proporciona al usuario información sobre cuál dia de la semana se ingresó un número mayor y cuál dia de la semana se ingreso el número menor, a parte de la suma total de los números ingresados, todo esto con el fin de tener una idea de cómo es que funciona un sistema para llevar algún tipo de contabilidad, obvio este sistema son los pasos de bebé de un sistema completo que  pudiera crear y desarrollar más adelante.
  
![image](https://github.com/Bellezatabaskena/IngSoftware/assets/114634159/818a4b90-4294-44c3-89f9-9834111373a9)

## Licencia

"Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles."
