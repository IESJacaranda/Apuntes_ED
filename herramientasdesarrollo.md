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




## Para cada uno de los lenguajes anteriores, indica el proceso realizado para conseguir ejecutar el código: ¿compilación o interpretación?

BASH:   Interpretado.
1.  Ejecutamos el intérprete.
  Este paso no es necesario aquí, puesto que ya estamos en el terminal.
2.  Escribimos las sentencias y luego pulsamos INTRO.
echo "Hola Mundo"
3.  Para salir del intérprete pulsamos CTRL+D.
    No pulsar esta combinación si no queremos cerrar el terminal.

PYTHON: Interpretado.
1.  Ejecutamos el intérprete.
python
2.  Escribimos las sentencias y luego pulsamos INTRO.
print "Hola Mundo"
3.  Para salir del intérprete pulsamos CTRL+D.

PHP: Interpretado.
1. Ejecutamos el intérprete.
php
2.  Escribimos las sentencias.
<?php 
 echo "Hola mundo\n"
?>
3.  Para salir del intérprete pulsamos CTRL+D. Después veremos el resultado de la ejecución.

 JAVASCRIPT (nodejs): Interpretado.
1.  Ejecutamos el intérprete.
node
2.  Escribimos las sentencias y luego pulsamos INTRO.
console.log('Hola mundo');
3.  Para salir del intérprete pulsamos CTRL+D.


C: Compilado.
1.  Editamos archivo **hola.c**
#include <stdio.h>
int main()
{   printf("¡Hola, mundo!");
    return 0; }
2.  Compilamos y enlazamos
gcc  -o  hola  hola.c      # Compilamos y enlazamos
3.  Ejecutamos
./hola  #Ejecutamos

C++: Compilado.
1.  Editamos archivo **hola.cpp**
#include <iostream>
using namespace std;
int main()
{   cout << "¡Hola, mundo!" << endl;
   return 0; }
   
2.  Compilamos y enlazamos

g++  -o  hola  hola.cpp    # Compilamos y enlazamos
3.  Ejecutamos

./hola                     # Ejecutamos

JAVA: Compilado.

1.  Editamos archivo **Hola.java**
class Hola
{  public static void main(String[] args)
    {  System.out.println("Hola Mundo");
    }
}

2.  Compilamos
javac  Hola.java      # Compilamos

3.  Interpretamos y ejecutamos

java  Hola            # Interpretamos y ejecutamos

RUBY: Interpretado.

1.  Ejecutamos el intérprete.

Ruby
2.  Escribimos las sentencias y luego pulsamos INTRO.
puts "Hola Mundo"
3.  Para salir del intérprete pulsamos CTRL+D.

GO: Compilado.

1.  Editamos archivo **hola.go**
package main
import "fmt"
func main() {
        fmt.Println("Hola mundo desde Go")
}
2.  Compilamos y enlazamos
go  build  hola.go   # Compilamos y enlazamos
3.  Ejecutamos
./ hola              # Ejecutamos
4.  Si lo deseamos,en Go también es posible interpretar el código
go  run  hola.go     # Interpretamos y ejecutamos

RUST: Compilado.
1.  Editamos archivo hola.rs
fn main() {
    println!("¡Hola, mundo! Desde RUST ");
}
2.  Compilamos y enlazamos
rustc  hola.rs              # Compilamos y enlazamos

3.  Ejecutamos
./hola                      # Ejecutamos

LISP: Interpretado.
1.  Ejecutamos el intérprete.
clisp
2.  Escribimos las sentencias y luego pulsamos INTRO.

(format t "¡Hola, mundo!")

3.  Para salir del intérprete pulsamos CTRL+D.


ENSAMBLADOR (NASM): Compilado.

1.  Editamos archivo **hola.asm**
  section .data
 msg     db "¡Hola Mundo!",  0Ah
 len     equ     $ - msg 
  section .text
 global _start
 _start:
  mov  eax,  04h
  mov  ebx,  01h
  mov  ecx, msg
  mov  edx, len
  int  80h
  mov  eax,  01h
  mov  ebx,  00h
  int  80h
2.  Ensamblamos y enlazamos
nasm  -f  elf64  hola.asm        # Ensamblado para ELF64
ld  hola.o  -o  hola             # Enlazado y generación de ejecutable
3.  Ejecutamos
./hola                           # Ejecución



## Para cada uno de los lenguajes anteriores, indica el nombre del compilador o interprete utilizado en GNU/Linux.

-   bash: Shell .
-   python: Python.
-   php: php.
-   javascript (nodejs): Node.
-   c: gcc.
-   c++: g++.
-   java: javac.
-   ruby: ruby.
-   go: go build.
-   rust: rustc.
-   lisp: clisp.
-   ensamblador (nasm): nasm.



## Investiga y averigua que extensión tienen los archivos de código fuente de los siguientes lenguajes:

-   bash: extensión .sh
-   python: extensión .py
-   php: extensión .php
-   javascript extensión .js
-   c extensión .c
-   c++ extensión .cpp
-   java extensión .java
-   ensamblador extensión .asm
-   ruby extensión .rb
-   go extensión .go
-   rust  extensión .rs
-   lisp extensión .lisp




## Scripts ejecutables para los lenguajes interpretados. Edita los scripts para los siguientes lenguajes:

-   BASH: 
Script ejecutable
1.  Editamos archivo **hola.sh**
#!/usr/bin/env bash
echo "Hola mundo"
2.  Damos permisos de ejecución
chmod  +x  hola.sh
3.  Ejecutamos
./hola.sh
-  PYTHON:

Script ejecutable
1.  Editamos archivo **hola.py**
#!/usr/bin/env python
print "Hola mundo"
2.  Damos permisos de ejecución
chmod  +x  hola.py
3.  Ejecutamos
./hola.py

-  PHP:

Script ejecutable
1.  Editamos archivo **hola.php**
#!/usr/bin/env php
<?php 
 echo "Hola mundo\n"  ?>
2.  Damos permisos de ejecución
chmod  +x  hola.php
3.  Ejecutamos
./hola.php


-  JAVASCRIPT:

 Script ejecutable
1.  Editamos archivo **hola.js**
#!/usr/bin/env node
console.log('Hola mundo');
2.  Damos permisos de ejecución
chmod  +x  hola.js
3.  Ejecutamos
./hola.js

-   JAVA:

Script ejecutable

> Realmente no es un script, sino **bytecode empaquetado en JAR** e interpretado por la JVM (Java Virtual Machine).
1.  Empaquetamos
jar  cvfe  hola.jar  Hola  Hola.class  # Empaquetamos 
NOTA: Las opciones utilizadas en el comando jar son:
c: Create      (Crear archivo jar)
v: Verbose     (Mostrar información)
f: File        (Nombre de archivo jar, en este caso hola.jar)
e: Entry point (Punto de entrada, en este caso la clase Hola)
Como último parámetro indicamos el bytecode a incluir, en este caso Hola.class.
2.  Damos permiso de ejecución
chmod  +x  hola.jar                    # Damos permiso de ejecución
3.  Ejecutamos
./hola.jar                             # Ejecutamos



-   RUBY:

 Script ejecutable
1.  Editamos archivo **hola.rb**
#!/usr/bin/env ruby
puts "Hola Mundo"
2.  Damos permisos de ejecución
chmod  +x  hola.rb
3.  Ejecutamos
./hola.rb


-   LISP

 Script ejecutable
1.  Editamos archivo **hola.lisp**
#!/usr/bin/env clisp
(format t "¡Hola, mundo!")
2.  Damos permisos de ejecución
chmod  +x  hola.lisp
3.  Ejecutamos
./hola.lisp
