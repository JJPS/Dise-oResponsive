# Diseño Responsive

El diseño responsive es un diseño web que se adapta a todos los dispositivos, ya sean ordenadores, tablets o teléfonos móviles. Es decir, que el diseño se ajusta a la pantalla en la que se está visualizando, ofreciendo una experiencia de usuario óptima en todos los dispositivos. 

Esto se consigue usando técnicas de diseño web como el uso de **medidas porcentuales** en lugar de píxeles para definir los tamaños de los elementos, y también mediante el uso de **media queries** para mostrar diferentes estilos dependiendo del tamaño de la pantalla.

## Medidas porcentuales

Las medidas porcentuales en el diseño web se refieren al uso de unidades de medida referencial en lugar de unidades de medida fijas como píxeles para definir el tamaño de los elementos de una página web. Esto permite que los elementos se ajusten automáticamente al tamaño de la pantalla del usuario, lo que mejora la experiencia de usuario. Las unidades de medidas referencial también se pueden utilizar para definir los márgenes, los bordes y los espacios entre los elementos.

Por ejemplo

```HTML
.container {
	margin: 0 auto;
	width: 90%;
	max-width: 1200px;
}
```
Con estas 3 propiedades de CSS conseguimos que a) El elemento se centre en la página, b) tenga un ancho del 90% sobre el elemento que lo contiene y c) su ancho nunca sea superior a 1200 pixeles.

Las tres unidades de medida porcentual que vamos a trabajar son:

- Porcentaje
- em
- rem



## Media Queries
