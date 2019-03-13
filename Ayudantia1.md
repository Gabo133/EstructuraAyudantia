# Ejercicio 1 
* Se desea calcular el promedio de notas de manera dinamica.
## Indicaciones
* Pida por teclado la cantidad total de notas.
* Pida el valor de las **n** notas .
* Calcule la nota media.
* Muestre por pantalla el resultado.

&nbsp;




# Resultado
```c
void notas(){
	float nota=0;
	float suma = 0;
	float promedio = 0;
	int i;
	int cant=0;

	printf("programa calcular promedio notas \n");
	printf("ingrese cantidad de notas: ");
	scanf("%d",&cant);
	
	
	for (i=1; i<=cant; i++){
		printf("ingrese nota:");
		scanf("%f",&nota);
		suma = suma + nota;
		
	}
	
	promedio = suma / cant;
	printf ("\n\n  El promedio de notas es %.2f \n", promedio);
	system("pause");
}
```


&nbsp;

&nbsp;

&nbsp;

# Ejercicio 2
* Genere un Script que calcule el factorial de un numero **n**
## Indicaciones
* Pida un numero 
* Calcule el factorial de ese numero utilizando funciones

&nbsp;

&nbsp;

# Resultado
```c
void factorial(int numero){
	int i;
	int factorial = 1;
	for(i=2;i<=numero;i++){
		factorial = factorial*i;
	}
	printf("El factorial de %d es: %d",numero,factorial);
}
```
&nbsp;

&nbsp;

&nbsp;

&nbsp;

# Ejercicio 3
* Genere un Script que consulte al usuario si desea calcular el factorial de un numero o si desea calcular su promedio de notas.
Una vez se le entregue el resultado el script deberá volver a preguntar si desea calcular el factorial de un numero o si desea calcular 
su promedio de notas o si desea salir de su aplicación.
