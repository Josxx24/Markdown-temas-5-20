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

[![archivos](data:image/png;base64,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)](data:image/png;base64,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)

# **Aplicaciones con archivos y estructuras**
Para poder guardar un struct en un archivo debemos guardar todas sus propiedades, y separarlas de alguna manera. Al momento de recuperarlas debemos hacer el proceso inverso. Entonces lo �nico que hace falta es escribir todas las propiedades separadas por un delimitador, y luego separar cada struct con algo como un salto de l�nea.
Al momento de leer el archivo y convertirlo a la coleccion de structs separamos la l�nea le�da usando el delimitador, y vamos asignando las propiedades.
[![archivos_con_estructuras](https://parzibyte.me/blog/wp-content/uploads/2022/01/Guardar-y-recuperar-coleccion-de-struct-en-archivo-usando-C.png)](https://parzibyte.me/blog/wp-content/uploads/2022/01/Guardar-y-recuperar-coleccion-de-struct-en-archivo-usando-C.png)

# **Entradas y salidas**
Todos los procesos tienen abiertos, por defecto, los archivos 0(entrada), 1(salida) y 2(salida de errores), de manera que en C++ se corresponden con los objetos cin,cout y cerr. De estos �ltimos el primero pertenece a la clase ifstream, que a su vez desciende de istream(flujo de entrada). Los dos �ltimos pertenecen a la clase ofstream, que desciende de la clase ostream(flujo de salida). Una jerarqu�a aproximada puede verse a continuaci�n:
[![entradas_y_salidas](data:image/png;base64,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)](data:image/png;base64,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)