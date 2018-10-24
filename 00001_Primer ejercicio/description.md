Hola! Vamos a comenzar con nuestro primeros ejercicios en C.

A continuacion te presentamos dos funciones.

Para ingresar números utilizaremos la función **scanf.**
Ejemplo:

``` c
int num;
scanf("%d",&num);
```
Scanf guarda un valor ingresado por teclado dentro de la variable entera num.

Si queremos ingresar otro tipo de datos deberemos variar el primer valor que pasamos dentro del scanf (que se encuentra entre comillas).

> **Por ejemplo:**<br>
> Para enteros usaremos **"%d"**.<br>
> Para cadenas usaremos **"%s"**.<br> 
> Para punto flotante usaremos **"%f"**.<br>

Para imprimir valores por pantalla utilizaremos la función **printf.**

```C
printf("El valor de la variable es %d",num);
```

Como introducción queremos que ingreses 2 (dos) números por teclado y los imprimas por pantalla.