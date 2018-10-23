# HERRAMIENTAS DE DESARROLLO

## Para que sirve un compilador? ¿Qué tipo de archivo obtenemos tras compilar?

**¿Para que sirve un compilador?**

Es un Software que traduce un programa escrito en un lenguaje de programación de alto nivel (C / C ++, COBOL, etc.) en lenguaje de máquina. Un compilador generalmente genera un lenguaje ensamblador primero y luego traduce el lenguaje ensamblador al lenguaje máquina. Con esto podemos hacer un programa que valga para todos los sistemas .

**Tipo de archivo tras compilar**

Tras compilar primero hace un archivo en lenguaje ensamblador y luego lo termina de compilar haciéndolo en lenguaje maquina, segun el modo en que se compile (si es un sistema de 32 o 64 bits y del sistema operativo) el archivo sera leido por unas maquinas u 
otras.

## ¿Para que sirve un enlazador? ¿Qué tipo de archivo obtenemos tras enlazar?

**¿Para que sirve un enlazador?**
Es un programa que toma los objetos generados en los primeros pasos del proceso de compilacion, la informacion de todos los recursos necesarios (bibliotecas), quita aquellos recursos que no necesita y enlaza el codigo objeto con su biblioteca, con lo que pruduce 
un fichero ejecutable o una biblioteca.

**Tipo de archivo que genera tras enlazar**
Tras enlazar las bibliotecas el archivo que optenemos es un fichero ejecutable, donde se hallan enlazadas las bibliotecas. Generalmente, son archivos con la extension EXE o COM,si los han de ejecutar computadoras con sistema operativo windows o con bits de marca 
que trae linusx para ser ejecutado.
El beneficio de tener el código ejecutable, es que se puede saber que la compilación fue realizada correctamente y que el programa, si no tiene errores de manejo, puede funcionar correctamente, porque está libre de errores de variables, signos y demás.

## Para que sirve un interprete? ¿Obtenemos algún archivo tras interpretar?

**¿Para que sirve un interprete?**

Es un programa informático capaz de analizar y ejecutar otros programas. Los interpretes se diferencia de los compiladores o los ensambladores es que mientras estos traducen un programa desde su descripción en un lenguaje de programación al código maquina del sistema, los intérpretes sólo realizan la traducción a medida que sea necesaria, típicamente, instrucción por instrucción, y normalmente no guardan el resultado de dicha traducción.

**¿Obtenemos algún archivo tras interpretar?**
El interprete leer los archivos pero no crea ninguno resultante.

## Explica cada uno de los siguientes conceptos e indica la relación entre ellos.

-   Código fuente: El código fuente de un programa o software es un conjunto de lineas de texto con los pasos que debe seguir la computadora para ejecutar dicho programa. Dicho programa esta escrito en un lenguaje de programación.
-   Código objeto. Se llama código objeto al código que resulta de la compilación del código fuente.
-   código binario. El código binario es el sistema numérico usado para la representación de textos, o procesadores de instrucciones de computadora, utilizando el sistema binario (sistema numérico de dos dígitos, o _bit el "0" /cerrado/ y el "1" /abierto/).


##  ¿Qué tipo de código es el bytecode generado por el compilador de Java?

El bytecode Java es el tipo de instrucciones que la máquina virtual Java espera recibir, para posteriormente ser compiladas a lenguaje de máquina, mediante un compilador JIT  a la hora de su ejecución. Usualmente es el resultado de utilizar un compilador del Lenguaje de programación (como javac), pero puede ser generado desde otros compiladores.

## Ejecuta el programa "Hola mundo" en los siguientes lenguajes:

-   bash ( #!/bin/bash
  echo "Hola mundo" )
  
-   python ( print "Hola Mundo" )

-   php (  <?php echo 'Hola Mundo!'; ?> )

-   javascript (nodejs) ( //Caso write()
document.write("Hola Mundo!");
//Caso alert()
alert("Hola Mundo!");
//Caso console.log()
console.log("Hola Mundo!");)

-   c (   #include <stdio.h>
int main(void)
{
 printf("¡Hola, mundo!");
}   )
-   c++  ( #include <iostream>
using namespace std;
int main()
{
   cout << "¡Hola, mundo!" << endl;
   return 0;
}
-   java class ( HolaMundo
{
    public static void main(String[] args)
    {
        System.out.println("Hola Mundo")
    }
}    )
-   ruby (  puts "Hola Mundo" )
-   go ( package main
import "fmt"
func main() {
    fmt.Println("hello world")
}  )
-   rust ( fn main() {
    println("¡Hola, mundo!");
} )
-   lisp (  (format t "¡Hola, mundo!") )
