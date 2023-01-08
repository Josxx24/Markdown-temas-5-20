# **IDE de desarrollo con c y c++**
## **�Que son los IDE?**
Es la forma completa del entorno de desarrollo integrado, los programadores utilizan esta plataforma digital para software, hardware y otras tareas de desarrollo de programas.
Dicha herramienta ayuda a escribir y desarrollar nuevas aplicaciones sin una configuraci�n manual ni integraci�n de caracter�sticas, tambi�n son eficientes en la edici�n, compilaci�n y depuraci�n de c�digo.
[![IDE](https://www.headsem.com/wp-content/uploads/2017/05/eclipse-ide.png)](https://www.headsem.com/wp-content/uploads/2017/05/eclipse-ide.png)

## **Las funciones de los IDE**

Hacen que el proceso de desarrollo sea m�s r�pido y f�cil para los programadores. En �l, puede obtener acceso a las herramientas y paquetes m�s populares en un solo lugar. La USP de un IDE es ofrecer la m�xima comodidad a los usuarios durante la codificaci�n y el desarrollo.

[![funciones IDE](https://blog.bricogeek.com/img_cms/3234-arduino-pro-ide-un-editor-avanzado-con-funciones-mas-completas.jpg)](https://blog.bricogeek.com/img_cms/3234-arduino-pro-ide-un-editor-avanzado-con-funciones-mas-completas.jpg)
------
# **Introducci�n a c, variables, palabras reservadas**
El lenguaje C es un lenguaje para programadores en el sentido de que proporciona una gran flexibilidad de programaci�n y una muy baja comprobaci�n de incorrecciones, de forma que el lenguaje deja bajo la responsabilidad del programador acciones que otros lenguajes realizan por s� mismos.
Es un lenguaje estructurado en el mismo sentido que lo son otros lenguajes, C no es r�gido en la comprobaci�n de tipos de datos, permitiendo f�cilmente la conversi�n entre diferentes tipos de datos diferentes, por ejemplo, la expresi�n siguiente es v�lida en C:

float=a; **Declaro una variable para n�mero reales**

int=b; **Declaro otra variable para n�meros enteros**

b=a; **Asigno a la variable entera el n�mero real**

todo programa de C consta, b�sicamente, de un conjunto de funciones, y una funci�n llamada main, la cual es la primera que se ejecuta al comenzar el programa, llamando dentro de ella al resto de las funciones.

El lenguaje C posee un n�mero reducido de palabras reservadas (tan solo 32) que define el standard ANSI-C. Estas palabras reservadas pueden verse en la siguiente tabla:

|Columna 1|Columna 2|Columna 3|Columna 4|Columna 5|Columna 6|Columna 7|
|--------|--------|--------|--------|--------|--------|--------|
|auto|break|case|char|const|continue|default|
|do|double|else|enum|extern|float|for|
|goto|if|int|long|register|return|short|
|signed|sizeof|static|struct|switch|typedef|union|
|insigned|void|volatile|while|

# **Algoritmo, estructura de datos y programas**

Un algoritmo es una secuencia de acciones o pasos que permite resolver un problema. Un mismo problema puede ser resuelto con distintos algoritmos.

Un programa es una traducci�n o codificaci�n de un algoritmo a un lenguaje de programaci�n; o sea, una secuencia de instrucciones que indica las acciones que han de ejecutarse.

El lenguaje de programaci�n; o sea, una secuencia de instrucciones que indica las acciones que han de ejecutarse.

El lenguaje de la maquina es usado directamente por la computadora y compuesto de instrucciones codificadas en sistema binario.

El compilador es un programa que traduce un programa escrito en lenguaje de alto nivel a lenguaje de m�quina.

[![algoritmos](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/LampFlowchart-es.svg/1200px-LampFlowchart-es.svg.png)](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/LampFlowchart-es.svg/1200px-LampFlowchart-es.svg.png)

# **Analisis de algoritmos**
Se refiere al proceso de encontrar la complejidad computacional de un algoritmo que resuelva un problema computacional dado, con el objetivo de proveer estimaciones teoricas de los recursos que necesita.

# **Conceptos b�sicos y Estructura general de un programa**
Las partes principales de un programa estan relacionadas con dos bloques: declaraciones e instrucciones. En las instrucciones podemos diferenciar tres partes fundamentales.

## **Entrada de datos**
La constituyen todas las instrucciones que toman los datos de entrada desde un dispositivo externo y los almacena en la memoria principal para que puedan ser procesados

## **Proceso o algoritmo**
Esta formado por las instrucciones que modifican los objetos a partir de su estado inicial (datos de entrada) hasta el estaod final (resultados) dejando los objetos que lo contiene disponibles en la memoria.

## **Salida de resultados**
Conjunto de instrucciones que toman los datos finales resultado de la memoria principal y los envian a los dispositivos externos.

## **Estructura secuencial**
Una estructura de programa es secuancial si las instrucciones se ejecutan una tras otra, a modo de secuencia lineal, es decir que una instruccion no se ejecuta hasta que finaliza la anterior, ni se bifurca el flujo del programa.

## **Estructura selectiva o de selecci�n**
Permite que la ejecucion del programa se bifurque a una instruccion (o conjunto) u otra/s, segun un criterio o condicion logica establecida, solo uno de los caminos en la bifurcacion sera el tomado para ejecutarse.

# **Sentencias de asignaci�n**
Asigna el valor de la expresi�n que est� a la derecha del signo: =

Ejemplo: NUM: =6+R (siendo conocido el valor de R)

## **Operadores**
- "+" ---> suma
- "-" ---> resta
- "*" ---> multiplicaci�n
- "/"---> divisi�n real
- "DIV"---> divisi�n entera
- "MOD"---> resto de divisi�n entera
## **Operadores relacionales**
- "=" ---> igual
- "<>"---> distinto
- "<"---> menor
- ">"---> mayor
- "<="---> menor o igual
- ">="---> mayor o igual
- "OR"---> o l�gico
- "AND"--> y l�gico
- "NOT"---> no

# **Control de flujo**
En C las sentencias se ejecutan sucesivamente una tras otra. Esto define un camino o direccion segun la cual se va a desarrollar el programa. Sin embargo, habr� momentos en que el programa deba ejecutar determinadas partes dependiendo del estado en el que se halle el programa o de las variables externas.

Los mecanismos en C que permiten llevar esto a cabo son:
- la sentencia if
- el bucle while
- el bucle do-while
- el bucle for
- la sentencias break y continue
- la seleccion multiple switch

# **Array**

Es un medio de guardar un conjunto de objetos de la misma clase. Se accede a cada elemento individual del array mediante un n�mero entero denominado indice. 0 es el �ndice del primer elemento y n-1 es el indice del �ltimo elemento, siendo n, la dimension del array.

[![arrays](https://cdn.programiz.com/sites/tutorial2program/files/c-arrays.jpg)](https://cdn.programiz.com/sites/tutorial2program/files/c-arrays.jpg)

## **Declarar y crear un array**
Para declarar un array se escribe:
> tipo_de_dato[] nombre_del_array;

Para declarar un array de enteros escribimos:
> int[] numeros;

Para crear un array de 4 numero enteros escribimos:
> numeros = new int[4];

La declaraci�n y la creaci�n del array se puede hacer en una misma l�nea:
> int[] numeros = new int[4];

## **Inicializacion y usar los elementos del array**

Para inicializar el array de 4 enteros escribimos:
> numeros[0]=2;
> numeros[0]=-4;
> numeros[0]=15;
> numeros[0]=-25;

Se pueden inicializar en un bucle **for** como resultado de alguna operacion.
>for(int i=0;i<4;i++){
    numeros[i]=i*i+4;
}

Los arrays se pueden declarar, crear e inicializar en una misma l�nea, del siguiente modo:
> int[] numeros={2,-4,15,-25};
> string[] nombres={"Juan","Jos�","Miguel","Antonio"};

Para imprimir a los elementos de array nombres se escribe:
> for(int i=0;i<nombres.length;i++){
    System.out.println(nombres[i]);
}

## **Arrays multidimensionales**
Pueden tener varias filas y en cada fila no tiene porque haber el mismo n�mero de elementos o columnas.
> double[][] matriz={{1,2,3,4,},{5,6},{7,8,9,10,11,12},{13}};

# **Estructuras y uniones**
Una estructura contiene varios datos. La forma de definir una estructura es haciendo uso de la palabra clave **struct**. Aqu� hay un ejemplo de la declaracion de una estructura:
> struct mystruct
{int int_member;
double double_member;
char string_member[25];    
}variable;

"variable" es una instancia de "mystruct" y no es necesario ponerla aqu�. Se podria omitir de la declaracion de "mystruct" y mas tarde declararla usando:
> struct mystruct variable;

Tambien es una practica muy comun asignarle a un alias o sinonimo al nombre de la esturctura, para evitar el tener que poner "struct mystruct" cada vez. C nos permite la posibilidad de hacer esto usando la palabra clave typedef struct.
[![estructuras](https://www.aulafacil.com/uploads/cursos/1537/editor/37-1.es.png)](https://www.aulafacil.com/uploads/cursos/1537/editor/37-1.es.png)

La definicion de "uni�n" es similar a la de "estructura", la diferencia entre las dos es que en una estructura, los miembros ocupan diferentes �reas de la memoria, pero en una uni�n, los miembros ocupan la misma are de memoria. Entonces como ejemplo:
> union{
int i;
double d;
}u;

El programador puede acceder a trav�s de "u.i" o de "u.d", pero no de ambos al mismo tiempo. Como "u.i" y "u.d" ocupan la misma �rea de memoria, modificar uno modifica el valor del otro, algunas veces de manera impredecibles.

# **Enumeradores**
Una enumeracion (enum) es un tipo definido con  constante de tipo entero. En la declaracion de un tipo enum creamos una lista de tipo de datos que se asocian con las constantes enteras 0,1,2,3,4,5,... su forma de definirlas es la siguiente:
> enum
>{
    enumerador1,enumerador2,...enumeradorn
};

>enum Nombre
{
    enumerador1, enumerador2,... enumeradorn
};

En este caso al ser declaradas enumerador1 toma el valor entero de 0, enumerador2 el valor de 1 y asi sucesivamente para cada yna de las expresiones. Al declarar la enum se puede asocial a los tipos de datos a valores constantes en vez de la asociacion qu epor defecto se realiza(0,1,2,...).
[![enumeradores](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Enum-In-C.png)](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Enum-In-C.png)

# **Archivos**
El est�ndar de C contiene varisa funciones para la edici�n de ficheros, �stas est�n definidas en la cabecera stdio.h y por lo general empiezan con la letra f, haciendo referencia a file. Adicionalmente se agrega un tipo **FILE** el cual se usar� como apuntador a la informacion del fichero. La secuencia que usaremos para realizar operaciones sera la siguiente:
- Crear un apuntador del tipo **FILE***
- Abrir el archivo utilozando la funcion fopen y asign�ndole el resultado de la llamada a nuestro apuntador.
- Hacer las diversas operaciones(lectura, escritura, etc).
- Cerrar el archivo utilizando la funci�n fclose.

|Nombre|Funci�n|
|------|-------|
|fopen()|Abre un archivo|
|fclose()|Cierra un archivo|
|fgets()|Lee una cadena de un archivo|
|fputs()|Escribe una cadena en un archivo|
|fseek()|Busca un byte espec�fico de un archivo|
|fprintf()|Escribe una salida con formato en el archivo|
|fscanf()|Lee una entrada con formato desde el archivo|
|feof()|Devuelve cierto si se llega al final del archivo|
|ferror()|Devuelve cierto si se produce un error|
|rewind()|Coloca el localizador de posicion del archivo al principio del mismo|
|remove()|Borra un archivo|
|fflush()|Vac�a un archivo|

[![archivos](https://parzibyte.me/blog/wp-content/uploads/2019/10/Escribir-archivo-con-C.png)](https://parzibyte.me/blog/wp-content/uploads/2019/10/Escribir-archivo-con-C.png)

# **Aplicaciones con archivos y estructuras**
Para poder guardar un struct en un archivo debemos guardar todas sus propiedades, y separarlas de alguna manera. Al momento de recuperarlas debemos hacer el proceso inverso. Entonces lo �nico que hace falta es escribir todas las propiedades separadas por un delimitador, y luego separar cada struct con algo como un salto de l�nea.
Al momento de leer el archivo y convertirlo a la coleccion de structs separamos la l�nea le�da usando el delimitador, y vamos asignando las propiedades.
[![archivos_con_estructuras](https://parzibyte.me/blog/wp-content/uploads/2022/01/Guardar-y-recuperar-coleccion-de-struct-en-archivo-usando-C.png)](https://parzibyte.me/blog/wp-content/uploads/2022/01/Guardar-y-recuperar-coleccion-de-struct-en-archivo-usando-C.png)

# **Entradas y salidas**
Todos los procesos tienen abiertos, por defecto, los archivos 0(entrada), 1(salida) y 2(salida de errores), de manera que en C++ se corresponden con los objetos cin,cout y cerr. De estos �ltimos el primero pertenece a la clase ifstream, que a su vez desciende de istream(flujo de entrada). Los dos �ltimos pertenecen a la clase ofstream, que desciende de la clase ostream(flujo de salida).