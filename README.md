![Logo de la Guía](https://raw.githubusercontent.com/fmendezy/Guia-de-Markdown/main/img/TituloGuia_FMY.png "Logo de la Guía de Markdown")
Este documento esta destinado como un lugar de apuntes para dejar registro de lo aprendido en Markdown para mi carrera como Ingeniero de Informático.

Es importante recordar que **Markdown admite HTML** en su contenido, permitiéndonos tener más *flexibilidad* en formato.

#### Índice
1. [Inicio](#Índice)
2. [Títulos](#mi-titulo-h1)
3. [Formatos de Textos](#formatos-de-textos)
4. [Listas](#listas)
5. [Enlaces](#enlaces)
6. [Citas](#citas)
7. [Líneas Separatorias](#lineas-separatorias)
8. [Insertar Código](#código)
9. [Tablas](#tablas)
10. [Imágenes y Videos](#imágenes)
11. [Notas al Pie de Página](#notas-al-pie-de-página)
12. [Tareas](#tareas)
13. [Emojis](#emojis)
14. [Menciones](#menciones)
___
<!-- Titulos -->
# Mi titulo h1
## Mi titulo h2
### Mi titulo h3
#### Mi titulo h4
#### Mi titulo h5
###### Mi titulo h6
***Nota:** Sólo llega hasta h6*

---
#### Formatos de textos
<!-- Italic (Cursiva) -->
Este es un texto en *cursiva*.

<!-- Strong (negrita) -->
Este es un texto en **negrita**.

<!-- Strikethrough (Tachado) -->
Este es un texto ~~tachado~~.

<!-- Resaltado de Texto -->
==Este es un texto resaltado.==

<!-- Cursiva y Negrita Combinada -->
***También se puede tener cursiva y negrita combinada.***
___Es posible hacerlo también con 3 guiones bajos.___

<!-- Resaltado de Texto -->
Oficialmente no está el subrayado, pero puedes <u>usar HTML</u> con `<u></u>`

<!-- Colores de Texto -->
Es posible <span style="color:blue">colorear</span> el texto usando HTML.

<!-- Subrayado -->

<!-- UL (Lista desordenada) -->
### Listas
#### Listas Desordenadas
* Manzana
  * Roja
  * Verde
- Melón
  - Verde
  - Naranjo


<!-- OL (Lista ordenada) -->
#### Listas Ordenadas
1. Aprender github.
2. Aprender Markdown.
3. Documentar la materia de la carrera.
   1. Ramo 1
   2. Ramo 2
   3. Ramo 3
      1. Unidad 1
      2. Unidad 2
      3. Unidad 3
      4. Exámen
4. Repetir.

<!-- Links (Enlaces) -->
#### Enlaces
[google.cl](https://www.google.cl)
[Posa el mouse encima](https://www.google.cl "Genial, sigues las instrucciones, esto se puede leer al posar el mouse en este enlace.")

<!-- Anclas -->
#### Anclas
Las anclas son enlaces internos dentro del mismo contenido.

El siguiente enlace te lleva te permite [volver al Índice](#índice).

<!-- Quotes (Citas) -->
#### Citas
> Esta es una cita.
>>Esta es una cita de nivel 2
>>>Y esta de nivel 3
>>>>Obviamente esta de nivel 4

<!-- Lineas -->
#### Lineas separatorias
---
***
___

<!-- Insertar Código -->
#### Código
`console.log('Hola mundo en una linea!)`

También puede tener formato por lenguaje de programación especifico, si no queda sin
```php
// Ejemplo de código en PHP con formato.
function suma($numeros) {
    $sum = 0;
    foreach ($numeros as $numero) {
        $sum += $numero;
    }
    return $sum;
}
echo suma([1,2,3,4,5,6,7,8,9,10]);
```

```html
<h1>Aquí otro ejemplo, con código en HTML</h1>
```
<!-- Tablas -->
#### Tablas
Las tablas tienen algo en particular, uno debe darle los "espaciados" para que se vea visualmente agradable en el código Markdown., sin embargo aunque en el código no se vea "bonito" se podrá apreciar en el resultado cómo este toma la forma esperada.

Deben haber al menos tres guiones medios para separar el encabezado.

| Producto     | Cantidad     | Precio       |
| ------------ | ------------ | ------------ |
| Coca Cola 2L | 1            | $1.800       |
|`Fruna Cola`  | *1*          | **$800**     |
| Pepsi 2L     | 1            | $1.600       |

Para tener los elementos **centrados** en la dirección que queramos, agregamos ":" (dos puntos) en la barras de guion medio, al inicio y final para centrado, a la derecha para la derecha.
| Columna 1 | Columna 2 | Columna 3 |
|-----------|:---------:|----------:|
| Alineado a la izquierda | Centrado | Alineado a la derecha |

<!-- Imagenes -->
#### Imágenes

<!-- Version con link externo -->
![VS Code Logo](https://code.visualstudio.com/assets/images/code-stable.png "Logo de Visual Studio")

<!-- Versión con archivo local -->
![Kotlin Logo](./img/Kotlin_Icon.png "Logo de Kotlin")

<!-- Versión HTML Ajustando tamaños -->
Versión **HTML** con ajustes de *alto* y *ancho*:
<img src="./img/Kotlin_Icon.png" alt="Logo de Kotlin" title="Logo de Kotlin en HTML" width="200" height="200">

<!-- Videos -->
#### Videos
<video width="320" height="240" controls>
  <source src="./video/video.mp4" type="video/mp4">
  Tu navegador no soporta el video tag.
</video>

<!-- Notas -->
#### Notas al pie de página
Oficialmente no forman parte principal de Markdown pero se pueden utilizar.

Este es un nota simple referenciada[^1].
Esta es una segunda nota referenciada. [^2].

<!-- Ver pie de página estos puntos -->
[^1]: Aquí va la primera referencia.
[^2]: Y aquí la segunda.


<!-- GITHUB MARKDOWN (REGLAS PROPIAS DE GITHUB) -->
#### Tareas
* [x] Tarea 1
* [x] Tarea 2
* [ ] Tarea 3
* [ ] Tarea 4

<!-- Emojis -->
#### Emojis
Se pueden obtener desde [aquí](https://gist.github.com/rxaviers/7360908 "Enlace a un articulo completo.")
:heart_eyes: :blush: :sunglasses: :heart: :star2: :fire: :muscle:

<!-- Mencionar a otros usuarios -->
#### Menciones
Es posible hacer menciones a usuarios de Github.
@fmendezy :muscle: +1

<!-- Fin -->