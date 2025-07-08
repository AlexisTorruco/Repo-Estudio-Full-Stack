# 📝Ejercicio 5 - Modelo de Caja (Box Model) en CSS

**Fecha:** 7-Jul-2025

## Requerimiento simulado

El cliente quiere una tarjeta de presentación que muestre un servicio destacado, con un ancho fijo, márgenes para centrarla, bordes decorativos, y un padding interno para separar el contenido del borde. Es importante entender cómo se calculan las dimensiones totales con el modelo de caja.

## 🎯 Objetivo

- Practicar y comprender el modelo de caja en CSS.
- Usar propiedades como `padding`, `margin`, `border`, y `box-sizing`.
- Crear un diseño con un ancho fijo que se mantenga consistente.

## Conceptos clave

- **Modelo de caja (box model)**: define cómo se calcula el tamaño de los elementos en la página.
- **box-sizing: border-box**: incluye padding y border dentro del ancho/alto definidos ➔ facilita el control del diseño.
- **border**: línea decorativa alrededor del elemento.
- **padding**: espacio interno entre el contenido y el borde.
- **margin**: espacio externo que separa el elemento de otros elementos.
- **border-radius**: redondea las esquinas del borde.
- **box-shadow**: agrega sombras decorativas para destacar un elemento.

## Archivos incluidos

- index-box-model.html
- styles.css

## Notas

- La tarjeta usa `margin: 50px auto` para centrarla horizontalmente y separarla verticalmente.
- El ancho total se mantiene en 300px gracias a `box-sizing: border-box`.
- Con `padding: 20px` y `border: 5px`, el contenido se mantiene dentro de los 300px definidos.
