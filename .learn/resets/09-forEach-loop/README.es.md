# `09` forEach Loop

En lugar de usar la clásica declaración `for`, hay una nueva forma de recorrer los arreglos: [higher order functions (funciones de orden superior)](https://www.youtube.com/watch?v=rRgD1yVwIvE).

Es posible recorrer un arreglo usando la función `myArray.forEach()`. Debes especificar qué hacer en cada iteración del bucle.

```js
myArray.forEach(function(item, index, arr) {
		
});
/**
 * item: valor del elemento específico (requerido).
 * index: índice del elemento (opcional).
 * arr: objeto array al cual pertenece el elemento (opcional).
*/
```

## 📝 Instrucciones:

En este momento, el código está imprimiendo todos los elementos en el array: 

1. Cambia el código de la función para imprimir solo los números divisibles por 14.

## 💡 Pista:

+ Un número (x) es divisible por 2 si `(x % 2 === 0)`.
