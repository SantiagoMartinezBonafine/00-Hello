# 00-Hello

Usuario github: SantiagoMartinezBonafine
◦ Legajo: 177.727-0
◦ Apellido: Martinez Bonafine
◦ Nombre: Santiago
• Número y título del trabajo: "Hello, World!" en C
• Transcripción del enunciado: 
2) 
a. Seleccione, instale, y configure, y pruebe un compilador C11 ó C18. Los
más osados pueden buscar un compilador que soporte C23 ó C2x.
b. Registre los resultados anteriores
c. Indique en el readme.md el compilador seleccionado, su versión, y la
versión de C que compila.
    . Pruebe el compilador con un programa hello.c que envíe a stdout
    la línea Hello, World! o similar.
    iii. Ejecute el programa y verifique que la salida es la esperada.
    iv. Ejecute el programa con la salida redireccionada a un archivo
    output.txt; verifique su contenido.


*• Hipótesis de trabajo que surgen luego de leer el enunciado:*
Se registrarán los resultados de la instalación, configuración y pruebas realizadas con el compilador de C seleccionado, en un archivo README.md.

c. 
El compilador seleccionado fue C18 (ISO/IEC 9899:2018): C18 es la versión del estándar C publicada en 2018.

*Codigo del archivo .c para imprimir la línea: "Hello, World!"* 

#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}

*Ejecutado en terminal:* 
$ gcc hello.c -o hello
$./hello

*La consola imprimio exitosamente:*
"Hello, World!" 

