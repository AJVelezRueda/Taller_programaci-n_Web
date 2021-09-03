# *PROGRAMACIÓN WEB* 
## UNA BREVE INTRODUCCIÓN...

> 🚨 WARNING: este tutorial hace un recorrido muy breve sobre los lenguajes web, te invito a no quedarte solo con este recorrido y a animarte a explorar el basto mundo de la programación Web

# Guias de Trabajo
* [1. Internet](#1-interntet)
* [2. Web](#2-Web)
* [3. Directo al hueso de las páginas](#3-html)
* [4. Las cosas por su nombre](#4-semantica)

[1. Internet](#1-interntet)

Internet se podría definir como la red de redes de computadoras, conectadas por medio de un cableado físico que permite intercambiar información entre todos sus usuarios. 

Para acceder al servicio que ofrece la información, debemos tener dos programas que se ejecutan en dos computadoras diferentes y que nos permiten compartir recursos. 

A la computadora que ejecuta el programa que proporciona el recurso o información se la denomina **servidor** y a la computadora que consume un recurso o información se la denomina **cliente**. En la computadora del cliente se ejecutará entonces el programa que le permite utilizar el recurso o leer la información.

Pero ¿Qué tipo de recursos pueden brindarse o consimirse a través de internet? Por medio de Internet podemos enviar mensajes, programas ejecutables, archivos de texto, consultar bases de datos, etc.

[2. La Web](#2-web)
La Web en particular, diminutivo de World Wide Web, es un conjunto de páginas interconectadas por las cuales podemos navegar.

Estas páginas web están pensadas para consumir contenido hipertextual, es decir  contenido que contiene vínculos o enlaces a otros contenidos.


[3. Directo al hueso de las páginas](#3-html)
HTML es un tipo de lenguaje que define la estructura o el esqueleto de algo mediante la codificación de información para que la información pueda ser representada de una forma adecuada.

HTML es un acrónimo de Hyper Text Markup Language, o lo que es lo mismo, Lenguaje de Marcado de Hyper Texto.

El Hyper Texto tampoco es sólo texto… Entre los elementos del hiper texto podemos encontrar videos, imágenes, sonidos, etc.

La sintaxis HTML se basa en etiquetas, que son las que le permite al browser (el programa que permite visualizar este tipo de archivos) interpretar como mostrar el contenido.
Las etiquetas se escriben entre <> 
Las etiquetas generalmente delimitan el contenido que están identificando y se deben abrir `<etiqueta>` y cerrar luego de escribir el contenido agregando a la misma etiqueta una barra invertida `</etiqueta>`

```html
<html>
		contenido
</html>

```
Algunas etiquetas no tienen etiqueta de cierre con la barra invertida, son únicas:

```html
<img src="images/las_de_sistemas.png" alt=””>
```

Existen, además, atributos para las etiquetas que le agregan una funcionalidad extra a la etiqueta que lo contiene:

```html
<p style="font-size: 18px;"> Este es mi texto con estilo propio</p>
```

Un documento HTML está formado por partes:

- Una línea que contiene información sobre la versión de HTML (no siempre),

- Una cabecera (delimitada por el elemento HEAD)

- Un cuerpo, con el contenido del documento (delimitado por el elemento BODY).

Todo el documento tiene que ir entre las etiquetas `<html></html>` e inicia con la etiqueta `<!DOCTYPE html>`

La etiqueta `<head>` contiene información sobre el documento actual, como el título, palabras clave que utilizan los motores de búsqueda, y otros datos que no se consideran parte del contenido del documento porque no se visualizan en el navegador. 
La etiqueta `<body>` contendrá el contenido particular de esta página.

> 👉¿Te animas a buscar qué otras etiquetas existen y para qué sirve?
>
> 🧗🏻‍♀️**Desafío**: Creá un archivo de texto con la herramienta que tengamos a mano (visual code, editor de texto, bloc de notas,etc) y lo guardamos con el nombre “mi_pagina” con extensión “.html” : “mi_cv.html”
>
>Iniciamos el documento con las etiquetas como sigue:
>
```html
<!DOCTYPE html>
<head>
 		<meta charset="UTF-8">
		<title>Document</title>
</head>
<body>
</body>
</html>
```
>


[4. Las cosas por su nombre](#4-semantica)
La semántica hace referencia al significado de las palabras y al significado de las oraciones. HTML nos brinda etiquetas para reforzar el significado de la información de 
nuestra página web

El HTML semántico no se trata sólo de utilizar las nuevas etiquetas semánticas, sino de utilizar las etiquetas correctas para cada elemento o sección de tu página web, para que sea fácil de navegar para todos los usuarios

Algunas de las etiquetas semánticas más usadas son:

- `<section></section>`

- `<figure></figure>`

> 👉 ¿Qué otras etiquetas semánticas podes encontrar?
