Hola! Vamos a comenzar con nuestro primeros ejercicios en C.

Como introducción queremos que ingreses 2 números y los imprimas por pantalla.

Para ingresar números utilizaremos la función **scanf.**
Ejemplo:

```C
int num;
scanf("%d",&num);
```
Scanf guarda un valor ingresado por teclado dentro de la variable entera num
Si queremos ingresar otro tipo de datos deberemos variar el primer valor que pasamos dentro de scanf.
> Por ejemplo:
Para enteros usaremos "%d", para cadenas usaremos "%s", para variables de punto flotante usaremos "%f"

Para imprimir valores por pantalla utilizaremos la función **printf.**

```C
printf("El valor de la variable es %d",num);
```