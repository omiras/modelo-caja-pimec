# El modelo de caja

Practica el [modelo de caja](https://www.w3schools.com/css/css_boxmodel.asp): contenido, padding, borde y margen. Abre cada HTML con Live Server.

## Cómo trabajar

1. Organiza primero el contenido HTML.
2. Crea una hoja CSS por ejercicio y enlázala desde su HTML.
3. Utiliza clases CSS para aplicar y reutilizar los estilos.
4. Escribe los colores en hexadecimal y las medidas en píxeles (`px`). Para centrar los bloques indicados, utiliza un ancho fijo y `margin: 20px auto`.

## Ejercicio 0. Margin y padding

Edita únicamente las partes señaladas con CHANGE ME de **0-modelo-caja.css** para reproducir la referencia. El HTML ya está preparado.

![Diseño esperado del ejercicio 0](https://github.com/TheOdinProject/css-exercises/raw/main/foundations/block-and-inline/01-margin-and-padding-1/desired-outcome.png)

### Colores de referencia

Los colores aproximados de la captura corresponden a los que ya trae la plantilla:

| Elemento | Fondo | Borde |
| --- | --- | --- |
| DIV ONE | `#ffc0cb` | `#0000ff` |
| DIV TWO | `#add8e6` | `#800080` |
| DIV THREE | `#ffdab9` | `#a52a2a` |

Texto: `#000000`. Fondo de página: `#ffffff`.

### Autoevaluación

- Div One y Div Three tienen 32 px de relleno entre texto y borde.
- Div One tiene 12 px de margen por cada lado.
- Entre Div Two y Div Three hay 48 px.
- Div Three queda a la derecha mediante su margen izquierdo automático.

## Ejercicio 1. Citas de Dijkstra

Archivo: **1-citas-dijkstra.html**. Crea **1-citas-dijkstra.css** y enlázalo.

[Ver diseño esperado adaptado](1-dijkstra-esperado.png)

![Diseño esperado adaptado de Dijkstra](1-dijkstra-esperado.png)

1. Usa un h1 para el título y un párrafo para cada texto de la plantilla.
2. Pon un fondo verde y un título blanco, en mayúsculas, con sombra negra.
3. Todas las cajas tendrán un ancho de contenido de 600 px, padding de 20 px y borde de 10 px. Su ancho exterior será de 660 px (600 + 40 de padding + 20 de borde). Aplica las propiedades comunes con el selector `p`. Usa `body` y `h1` para los estilos generales de página y título, y una sola clase por párrafo. Elige tú los nombres de las clases.
4. Centra la introducción y las dos citas con borde azul discontinuo con `margin: 20px auto`.
5. Las cuatro citas con borde marrón o naranja quedan alineadas a la izquierda, con `margin: 20px 0`. Al compartir ancho, padding y grosor de borde, sus bordes izquierdos y derechos quedan alineados.
6. Reproduce los tres estilos de cita: borde marrón con esquinas izquierdas redondeadas, borde naranja con esquinas derechas redondeadas y borde azul discontinuo.

### Valores y colores

| Elemento | Fondo | Texto | Borde | Padding |
| --- | --- | --- | --- | --- |
| Introducción | `#ffffff` | `#000000` | 10 px sólido `#000000`, radio 30 px | 20 px |
| Citas con borde marrón | `#b35733` | `#ffffff` | 10 px sólido `#802400`, radios izquierdos 20 px | 20 px |
| Citas con borde naranja | `#b37b33` | `#ffffff` | 10 px sólido `#804800`, radios derechos 15 px | 20 px |
| Citas con borde azul | `#004680` | `#ffffff` | 10 px discontinuo `#3379b3` | 20 px |

Fondo de página: `#267352`. Fuente: Arial o sans-serif, 20 px. Título: 40 px, sombra negra desplazada 5 px en horizontal y vertical. Conserva el orden de los textos; alterna los estilos de borde marrón, naranja y azul, y repite esa secuencia. Las dos citas con borde azul quedan centradas. Los colores, los radios y el tipo de borde distinguen cada estilo; el ancho, el padding y el grosor del borde son iguales en todas las cajas.

## Ejercicio 2. Citas de Chesterton

Archivo: **2-chersteton.html**. Crea **2-chesterton.css** y enlázalo. Se conserva el nombre del archivo HTML existente.

[Ver diseño esperado de Chesterton](2-chesterton-esperado.png)

![Diseño esperado de Chesterton](2-chesterton-esperado.png)

La distribución se adapta así:

- El body tiene un ancho del 80% y `margin: 20px auto`.
- Usa header para el título y los dos párrafos introductorios, main para las citas y un section por tema: Capitalismo, Política y Progreso. Cada tema tiene un h2 y cada cita un p.
- Incluye los paddings y márgenes aproximados para cada elemento

### Colores y tamaños

| Elemento | Color |
| --- | --- |
| Fondo de página | `#997366` |
| Fondo de cabecera | `#998680` |
| Fondo de secciones | `#b39f99` |
| Fondo de títulos de sección y borde de main | `#ffffff` |
| Borde de citas | `#402d26` |
| Texto de citas | `#ffffff` |
| Texto general | `#000000` |

Fuente general: Arial o sans-serif, 24 px. Título principal: 64 px. Títulos de sección: 36 px. Los colores son aproximados; la referencia sirve para comparar fondos y bordes, y estas instrucciones concretan las medidas de la versión adaptada.

## Comprueba tu trabajo

- Las clases del HTML coinciden con las de tu hoja CSS.
- Distingues el margen exterior, el borde y el relleno interior.
- Has conservado los textos de las plantillas.
- En Dijkstra la introducción y las dos citas con borde azul discontinuo están centradas.
- En Chesterton el conjunto está centrado y las citas tienen espacio dentro de cada sección.
- El resultado es aproximado. Tu solución debería verse bien con el navegador web maximizado, pero es normal que no se vea bien en una pantalla pequeña.
