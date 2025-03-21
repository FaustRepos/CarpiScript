# CarpiScript

CarpiScript es un lenguaje de scripting en castellano desarrollado en TypeScript. Incluye analizador léxico, analizador sintáctico e intérprete.

![Carpincho Canchero](https://raw.githubusercontent.com/FaustRepos/CarpiScript/main/carpincho.png)

## Requsitos

Node y ts-node (`npm install -g ts-node`).

## Uso

Para ejecutar un script desarrollado en CarpiScript:

```shell
$ ts-node ejecutar.ts test.ñ
```

Para correr código CarpiScript y obtener el resultado:

```ts
import ejecutar from './carpiscript'

console.log(ejecutar('(1+2)*3'))
```

## Sintaxis

```js
IMPUESTOS = 10

precioPorDocena = ingresarNumero("Precio por docena")

precioUnitario = precioPorDocena / 12
precioFinal = precioUnitario * (1 + IMPUESTOS / 100)

si (precioFinal < 10) {
  imprimir('Precio demasiado bajo')
}
sino (precioFinal > 10000) {
  imprimir('Precio demasiado alto')
}
sino {
  imprimir("El precio final con " + IMPUESTOS + "% de impuestos es $" + entero(precioFinal))
}

```
