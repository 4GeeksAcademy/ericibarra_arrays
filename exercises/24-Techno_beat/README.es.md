# `24` Techno beat

Estás trabajando con un DJ y él necesita un programa que pueda crear ritmos para sus canciones.

## 📝 Instrucciones:

1. Crear una función `lyricsGenerator` que recibe un array. El array enviado a la función será algo así:

```js
[0,0,1,1,0,0,0] 
```

2. Por cada 0, agrégale al string `'Boom'`.

3. Por cada 1, agrégale al string `'Drop the base'`.

## Restricciones:

+ Si encuentras el número Uno (1) tres veces seguidas, TAMBIÉN debes AGREGAR al string `¡¡¡Break the base!!!`

## Resultado esperado:

```js
Boom Boom Drop the base Drop the base Boom Boom Boom
Boom Boom Drop the base Drop the base Drop the base !!!Break the base!!! Boom Boom Boom
Boom Boom Boom
Drop the base Boom Drop the base
Drop the base Drop the base Drop the base !!!Break the base!!!
```

## 💡 Pista:

+ Recuerda usar variables auxiliares

