Hasta ahora vimos la posibilidad de decidir entre dos caminos posibles pero...<br> ¿Si los caminos son más?
Para resolver estos casos podemos utilizar lo que se coloquialmente  se conoce como **if anidados**.<br>
Esto consiste en introducir otra sentencia **if**, abriendo otro camino dentro de un mismo **if** o un **else**.<br>
Ejemplo:<br>

``` c
if (A<8)
{
  printf("La variable A es menor a 8");
}
else
{
  if (A>8)
  {
    printf("La variable A es mayor a 8");  
  }
  else
  {
    printf("La variable A es igual a 8");
  }
}
```

También contamos con la sentencia **switch** en caso de que la variables a utilizar sean enteras o caracteres.
> **Recordemos que la sentencia switch solo funciona con enteros y caracteres buscando igualdades en una lista de posibilidades**

```c
switch (i)
{
	case 1:
		printf("Lunes\n");
		break;
	case 2:
		printf("Martes\n");
		break;
	case 3:
		printf("Miércoles\n");
		break;
	case 4:
		printf("Jueves\n");
		break;
	case 5:
		printf("Viernes\n");
		break;
	case 6:
		printf("Sábado\n");
		break;
	case 7:
		printf("Domingo\n");
		break;
	default:
		printf("Opción no válida\n");
		break;
}
```	
> **Aclaramos que la etiqueta default se utiliza opcionalmente para los casos donde no se encuentra coincidencia<br>
Si no recordás que significa "\n" deberás leer la guía introductoria.**
