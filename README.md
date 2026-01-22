# EntornosAct2
## Descripción
``` java
package Actividad1;
/**
 * Programa que analiza un conjunto de números para obtener
 * el valor mayor y cuántas veces se repite.
 */

public class Codigo1 {

	/** 
	 * Punto de entrada del programa.
	 * Recorre un array de números para encontrar el mayor 
	 * y contar sus repeticiones.
	 */

	public static void main(String[] args) {

		int[] d = {4, 7, 2, 9, 2, 5}; // Array en el que tu pones los números que quieras
		int e = 0; // Una variable contador
		int f = d[0]; // f toma el valor de la posicion 0 del array d

		// Bucle que recorre el array d, y si una de las posiciones es mayor que f, sustituye su valor.
		for (int i = 1; i < d.length; i++) { 
			if (d[i] > f) { 
				f = d[i]; 
			} 
		} 

		// Bucle que recorre el array d, y si una de las posiciones es igual a f, suma 1 al contador e.
		for (int i = 0; i < d.length; i++) { 
			if (d[i] == f) { 
				e++; 
			} 
		} 

		System.out.println(f + ":" + e); 
	}
}
```
## Como ejecutar el código
## Diego Salido
