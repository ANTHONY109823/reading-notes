# Markdown: Guía Básica

Markdown es un lenguaje de marcado ligero que permite dar formato al texto de manera sencilla, utilizando una sintaxis fácil de leer y escribir. Aquí te mostramos algunos de los elementos básicos de Markdown.

## 1. Encabezados de diferentes niveles
Los encabezados se crean utilizando el símbolo #. Cuantos más # uses, menor será el nivel del encabezado.
# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6
Resultado:

Encabezado de nivel 1
Encabezado de nivel 2
Encabezado de nivel 3
Encabezado de nivel 4
Encabezado de nivel 5
Encabezado de nivel 6
2. Texto en negrita e itálica
Para poner texto en negrita, se utilizan dos asteriscos ** o dos guiones bajos __ alrededor del texto.
Para poner texto en itálica, se utilizan un solo asterisco * o un solo guion bajo _ alrededor del texto.
markdown
Copiar
**Texto en negrita**
__Texto en negrita__

*Texto en itálica*
_Texto en itálica_
Resultado:

Texto en negrita
Texto en negrita

Texto en itálica
Texto en itálica

3. Listas ordenadas y no ordenadas
Listas ordenadas: se crean con números seguidos de un punto.
Listas no ordenadas: se crean con asteriscos *, guiones - o más comúnmente con signos más +.
markdown
Copiar
1. Primer ítem de lista ordenada
2. Segundo ítem
3. Tercer ítem

* Primer ítem de lista no ordenada
* Segundo ítem
  * Subítem de la lista no ordenada
Resultado:

Primer ítem de lista ordenada
Segundo ítem
Tercer ítem
Primer ítem de lista no ordenada
Segundo ítem
Subítem de la lista no ordenada
4. Enlaces a recursos útiles
Los enlaces se crean utilizando corchetes [] para el texto del enlace, seguido de los paréntesis () con la URL.

markdown
Copiar
[Google](https://www.google.com)
[Markdown Guide](https://www.markdownguide.org)
Resultado:

Google
Markdown Guide

5. Tabla comparativa entre HTML y Markdown
Las tablas en Markdown se crean utilizando guiones - y barras verticales |.

markdown
Copiar
| Característica     | HTML                            | Markdown                     |
|--------------------|---------------------------------|------------------------------|
| Sintaxis           | `<h1>Encabezado</h1>`           | `# Encabezado`               |
| Negrita            | `<strong>Texto</strong>`        | `**Texto**`                  |
| Itálica            | `<em>Texto</em>`                | `*Texto*`                    |
| Lista ordenada     | `<ol><li>Item</li></ol>`        | `1. Item`                    |
| Lista no ordenada  | `<ul><li>Item</li></ul>`        | `* Item`                     |
| Enlaces            | `<a href="url">Texto</a>`      | `[Texto](url)`               |
Resultado:

Característica	HTML	Markdown
Sintaxis	<h1>Encabezado</h1>	# Encabezado
Negrita	<strong>Texto</strong>	**Texto**
Itálica	<em>Texto</em>	*Texto*
Lista ordenada	<ol><li>Item</li></ol>	1. Item
Lista no ordenada	<ul><li>Item</li></ul>	* Item
Enlaces	<a href="url">Texto</a>	[Texto](url)
Conclusión
Markdown es una herramienta poderosa y sencilla para crear contenido formateado sin complicarse con etiquetas complejas. Su simplicidad lo hace ideal para escribir documentación, README files, blogs y más.

