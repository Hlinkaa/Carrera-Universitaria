# Ejercicios de Recursividad con Enteros

1. static int sumaDesdeUnoHasta(int n)

Devuelve la suma de todos los numeros entre 1 y n.

2. static void imprimirHasta(int n)

Imprime por pantalla los números entre 1 y n (en orden ascendente).

3. static void imprimirDesde(int n)

Imprime por pantalla los números entre 1 y n (en orden descendente).

4. static int sumaDeCuadradosHasta(int n)

Devuelve la suma de todos los numeros elevados al cuadrado entre 1 y n.

5. static double potencia(double base, int exp)

Calcula base elevado a la exp.

6. static int sumaEntre(int n, int m)

Calcula la suma de los números que hay entre n y m. Incluyendo a n y a m. Asumir que m >= n.

7. static int cantidadPrimosEntre(int n, int m)

Calcula la cantidad de números primos que hay entre n y m. Obs: Asumir que se tiene una función
que indica si un número es primo o no (i.e., hacerla antes!)
Asumir que m >= n.

8. static boolean esPar(int n)

Indica si un número es par o no.

0- Definir la función auxiliar String resto(String s) que devuelva toda la cadenas menos el primer caracter. No es necesario que sea recursiva.

1- Escribir una función recursiva llamada public static void imprimirEspaciado(String s) que tome un String e imprima el String con espacios entre cada caracter.
Ejemplo:
imprimirEspaciado(“Juan”)
// imprime "J u a n"
Hacer primero la función auxiliar resto(String s) que devuelva toda la cadenas menos el primer caracter.

2- Escribir una función  public static int longitud(String s) 
Devuelve la longitud de la cadena s. No vale usar length(). 

3- Escribir una función recursiva llamada public static String reverso(String s) que tomé un String y devuelva el String que resulta de invertir todos sus caracteres.

4- Escribir una función recursiva llamada  public static String combinar(String s, String t) que tome dos Strings y devuelva el String que resulta de comparar los strings caracter a caracter y colocar el menor de ellos en el resultado. Si tienen longitudes distintas, tomamos el resto del string que quede.
Ejemplo:
String res = combinar(“abd”, "bbc")
//res vale "abc"
String res = combinar(“fgd”, "adfxgtgs")
//res vale "addxgtgs"

5-Escribir una función que tome una cadena como parámetro y la imprima por consola intercalando un ’∗’ entre cada letra. Por ejemplo, si la función toma la cadena ”hola” como parámetro, deberá imprimir ”h∗o∗l∗a”.

6- Implementar el método public static boolean esAbecedaria(String s) . Una palabra se dice que es "abecedaria" si las letras en la palabra aparecen en orden alfabético o si la cadena está vacía o es de 1 caracter, se consindera "abecedaria". La función debe devolver un booleano.
Por ejemplo, la siguientes son todas palabras abecedarias del castellano.
adios, afín, año, ágil, bello, celos, cenó, chinos dijo, dimos, dios, fijos, finos, hijos, hilos, himno

9. static boolean esImpar(int n)

Indica si un número es impar o no.
10. static int cantidadDigitos(int n) 

Indica la cantidad de digitos de un número.

Ejercicios de recursividad (estilo parcial)
1- Escribir una función recursiva String tomarCaracteresDesde(String s, int desde, int cant) que toma un String s, una posición desde, una cantidad cant y devuelve una nueva cadena que resulta de tomar cant caracteres de s desde la posición desde.

Por ejemplo:
tomarCaracteresDesde("sobrenatural",0,5) puede devolver "sobre".
tomarCaracteresDesde("capa",7,10) puede devolver "".
tomarCaracteresDesde("claramente",2,3) puede devolver "ara".
tomarCaracteresDesde("programacion",4,4) puede devolver "rama".
tomarCaracteresDesde("domingo",2,10) puede devolver "mingo".
tomarCaracteresDesde("",1,5) puede devolver "".

2- Escribir la función recursiva public static String insertarOrdenado(String s, char a) que que toma un string s (cuyas letras se asumen ya en orden alfabético) y devuelve un string igual a s pero en el cual se ha insertado el char a , en la posición que corresponde de manera tal que el string siga estando ordenado. 

Por ejemplo:

insertarOrdenado("abcdfghi", ’e’) debe devolver "abcdefghi"

3- Escribir una función public static boolean comienzaCon(String s1, String s2) que dadas dos cadenas s1 y s2 retorna verdadero si la cadena s2 comienza con la cadena s1, falso en caso contrario.

Por ejemplo:
comienzaCon "sol" y "solamente", retorna true.
comienzaCon "" y "termo", retorna true.
comienzaCon "mario" y "mariano", retorna false.
comienzaCon "mas" y "", retorna false.
comienzaCon "lastima" y "las", retorna false.

4- Escribir una funci´on recursiva public static String eliminarVocalesYRevertir(String s) que toma un String s y devuelve una nueva cadena que resulta de eliminar de s todas las vocales y luego invertir sus caracteres.

Por ejemplo:

eliminarVocalesYRevertir("toro") debe devolver "rt".

eliminarVocalesYRevertir("risa") debe devolver "sr".

eliminarVocalesYRevertir("mapa") debe devolver "pm".

eliminarVocalesYRevertir("fadap") debe devolver "pdf".

eliminarVocalesYRevertir("uia") debe devolver "".

5- Escribir la función recursiva public static String alternaVocales(String s,String t) que devuelve la cadena que se obtiene al cambiar las vocales de la cadena s por las vocales de la cadena t a medida que van apareciendo de izquierda a derecha. Si hay menos vocales en t entonces las vocales de s que siguen no cambian.

Por ejemplo:
alternaVocales("ropero", "mula") debe devolver "ruparo".
alternaVocales("ropero", "mulata") debe devolver "rupara".
alternaVocales("ropa", "muleta") debe devolver "rupe".
alternaVocales("ropero","") debe devolver "ropero".
alternaVocales("ropero", "crear") debe devolver "reparo"
alternaVocales("", "algo") debe devolver "".


Se pide resolver utilizando recursión.
Se puede dar por hecha la función public static String resto(String s) que devuelve una cadena igual a s pero sin su primer carácter.

