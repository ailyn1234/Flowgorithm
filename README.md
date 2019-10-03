# Aprendiendo lógica con Flowgorithm :computer: 

_Autor: Luis Angel Monge_
profesor@luismonge.com.mx

_Adaptado: @IoTeacher_

## Descripción

_Este es un curso de metodología de la programación de apoyo a introducción al aprendizaje de lógica. La herramienta que se utilizará es  Flowgorithm, que permite a generar  diagramas de flujo y exportar distintos lenguajes_

### Pre-requisitos :white_check_mark: POR FAVOR USARLO EN INGLES, IMPORTANTE PARA TODO PRINCIPIANTE.

* [Flowgorithm](http://www.flowgorithm.org/) - Software a utilizar Windows 7 o 10 de 32 y 64 bits, (laboratorio ITT es 32 bits). Y su tutorial http://www.flowgorithm.org/documentation/tutorial

### Temario

1. Entrada y salida de datos
	* ***Salida(Output):*** Es un simbolo en forma de rectangulo inclinado, que sirve para realizar preguntas, dar instrucciones, mostrar resultados. Los datos de entrada deben escribirse entre comillas, la excepción es cuando quieres mostrar el resultado de una variable
	* ***Entrada(Input):*** Es un simbolo en forma de rectangulo inclinado, que sirve para obtener información desde el teclado de la computadora. Dentro del rectangulo inclinado debe proporcionarse un nombre de variable. Esta almacenará la información que la persona escriba desde su teclado
	* ***Ejemplo:*** [Entrada y Salida](https://github.com/IamLAM/Flowgorithm/blob/master/Entrada_Salida.fprg)
	* ![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/entrada_salida.jpg "ES")

2. Declaración y asignación de variables
	* ***Declaración***: Es la acción de indicar el tipo de dato que tendrá una variable, en consecuencia, dependiendo del tipo de dato, será el valor que puede almacenar.Por ejemplo
	en el lenguaje de programación C tiene la siguiente estructura: [tipo de dato][nombre de variable]=[inicialización]. Equivalente a: int respuesta=1;
	
	* ***¿Como se hace en Flowgorithm?***. Al igual que en el lenguaje de programación C. En este programa se pueden agregar cuatro tipos de datos: ***Enteros,Reales,Cadenas y Booleanos***
	
		* Agregar simbolo ***Declare*** :<br>
		![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/agregandoSimboloDeclare.jpg "Agregando simbolo")

		* Dar doble click sobre el simbolo ***Declare***, escribir nombre de variable y seleccionar tipo de dato :
		![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/agregandoTipoDatoDeclare.jpg "Agregando tipo de dato")
		* Aceptar cambios  ***Declare***, resultado final:<br>
		![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/agregandoDeclareCompleto.jpg "Declare completo")
	
	* ***Tipos de datos en Flowgorithm***: 
	
Tipo de dato | Significado
----------|------------
Enteros | 1,2,3....n
Reales (decimales) | 1.0,1.1,33.5....n
Cadenas(Alfanumericos entre comillas) | "Hola", "A", "1"
Booleanos | true, false,1,0


	
3. Estructuras de control
	* ***Rombo (if):*** Es un simbolo que sirve para la toma de decisiones. Dentro de este simbolo se deben añadir expresiones relacionales o lógicas como: a<6, (a==n)||(a>10),a!=5, a>=8, a<=1, entre muchas otras. Por lo tanto, los valores que hayas capturado previamente, se comparan dentro de este "rombo"<br>![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/Control.jpg "If")
	* ***Agregar una expresión y dos mensajes de salida***. Si la expresión es ***VERDADERA*** se irá por el camino del SI o TRUE o VERDADERO, si no, se irá por el camino del NO o FALSE o FALSO. Por ejemplo. En este diagrama, se evalua si la persona se siente mal. Es decir, si alguien escribe desde su teclado la palabra mal,la expresión será verdadera por que dentro de la variable respuesta se guardara "mal". Por lo tanto en el rombo se evalua respuesta=="mal",comparandose "mal"=="mal". ![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/Control_Respuesta.jpg "Expresiones")
	
	* ***Resultado final:***<br>
	![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/Control_Completo.jpg "Expresiones Completo")

	* [Descargar Ejercicio Completo](https://github.com/IamLAM/Flowgorithm/blob/master/EstructuradeControl.fprg)

4. Estructuras Iterativas
	* ***Hexágono (while):*** Es un simbolo que sirve ciclar o repetir n veces un conjunto de instrucciones. Dentro de este simbolo se deben añadir expresiones relacionales o lógicas como: a<6, (a==n)||(a>10),a!=5, a>=8, a<=1, entre muchas otras. Por lo tanto, los valores que hayas capturado previamente, se comparan dentro de este "hexágono". Si la condición es válida,estará repitiendose el ciclo (TRUE), de lo contrario será FALSE<br>
		* ![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/CicloWhile.jpg "while")
		* [Descargar Ejercicio Completo](https://github.com/IamLAM/Flowgorithm/blob/master/EstructuraIterativaWhile.fprg)
	* ***Hexágono (do):*** Es un simbolo que sirve ciclar o repetir n veces un conjunto de instrucciones. La diferencia respecto a while, es que por lo menos ingresará una vez antes de validar  la expresión relacional dentro del "Hexágono". Por lo tanto, los valores que hayas capturado previamente, se comparan dentro de este "hexágono". Si la condición es válida,estará repitiendose el ciclo (TRUE), de lo contrario será FALSE<br>
		* ![alt text](https://github.com/IamLAM/Flowgorithm/blob/master/img/CicloDoWhile.jpg "do")
		* [Descargar Ejercicio Completo](https://github.com/IamLAM/Flowgorithm/blob/master/EstructuraIterativaDoWhile.fprg)

# Documentacion

en el programa es importante, para la formalidad del codigo antes de entregarlo a revision.

![](img/Comentarios.png)


5. Serie de ejercicios
    * [Sumar valores](https://github.com/IamLAM/Flowgorithm/blob/master/01_SumarValores.fprg)
    * [Area Triangulo](https://github.com/IamLAM/Flowgorithm/blob/master/02_AreaTriangulo.fprg) 
    * [Expresión Matemática](https://github.com/IamLAM/Flowgorithm/blob/master/03_Expresi%C3%B3nMatem%C3%A1tica.fprg) 
    * [Josefina:Strings](https://github.com/IamLAM/Flowgorithm/blob/master/04_Josefina.fprg) 
    * [Josefina:Integers](https://github.com/IamLAM/Flowgorithm/blob/master/05_JosefinaN.fprg) 
    * [Obtener promedios](https://github.com/IamLAM/Flowgorithm/blob/master/06_ObtenerPromedio.fprg	) 
	* [Entrenador](https://github.com/IamLAM/Flowgorithm/blob/master/07_Entrenador.fprg) 
	* [Fiesta](https://github.com/IamLAM/Flowgorithm/blob/master/08_Fiesta.fprg)
 	* Catalogo de ejercicios:Preparar una hamburguesa  
    * Ordenamientos
    * Par e impar
    * Solicita una pizza
    * Adivina el numero
    * Algebra básica
    * Gestión de agenda
    * Calculo de figuras
    * Adivina el acertijo
    * Conversiones 
    * Simular un reloj digital
    * Tienda de autoservicio
	
 
# PROBLEMA NIVEL INTERMEDIO
   Escriba un programa que tome una matriz de enteros de entrada que contenga números positivos y negativos y descubra el promedio de positivo y promedio de números negativos.(este problema es candidato a ciclos o bucles)

Ejemplo:
_Si el usuario proporciona la entrada 9, -1, -1, -4, 1.5, -4.2, -3.1, 
la salida será:
Promedio de números positivos: 5.25
PRomedio de números negativos: -2.66_

```
//Poner los comentarios pertinentes, es parte de la evaluación.
//
#include <iostream>
using namespace std;
int main()
{
  int arr[10];  //Arreglo de 10 posiciones
  float avg_pos=0.0,avg_neg=0.0;

  for(int i=0;i<10;i++)
  {
    cout << "Enter Number: " << "[" << i << "]:\n";
    cin >> arr[i];   // llenar el arreglo
  }

// Escriba su lógica aqui abajo





//end
  cout << " positivenumbers: \n" << avg_pos;
  cout << "negativenumbers:\n" << avg_neg;  
  return 0;
}

