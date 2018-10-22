Hola! Vamos a comenzar con nuestro primeros ejercicios en C.

A continucacion te presentamos dos funciones.

Para ingresar números utilizaremos la función **scanf.**
Ejemplo:

```C
int num;
scanf("%d",&num);
```
Scanf guarda un valor ingresado por teclado dentro de la variable entera num.

Si queremos ingresar otro tipo de datos deberemos variar el primer valor que pasamos dentro del scanf (que se encuentra entre comillas).
> Por ejemplo:
* Para enteros usaremos "%d".
* Para cadenas usaremos "%s". 
* Para variables de punto flotante usaremos "%f"

Para imprimir valores por pantalla utilizaremos la función **printf.**

```C
printf("El valor de la variable es %d",num);
```

Como introducción queremos que ingreses 2 números y los imprimas por pantalla.