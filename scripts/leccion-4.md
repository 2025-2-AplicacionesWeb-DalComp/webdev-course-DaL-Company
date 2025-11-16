# Lección 4 – Introducción a CSS  
Curso: Programación Web Fundamentals

---

## 1. ¿Qué es CSS?

CSS significa *Cascading Style Sheets* y es el lenguaje que permite darle estilo a una página web.  
Mientras que HTML define la **estructura** del contenido, CSS define su **aspecto visual**.

En esta lección veremos:

- Qué es CSS y para qué sirve.  
- Cómo usarlo en HTML Pen.  
- Cómo funciona la sintaxis básica.  
- Cómo aplicar colores, tamaños, bordes, márgenes y tipografías.  
- Cómo usar clases e IDs.  
- Qué son los selectores y cómo personalizarlos.  
- Cómo colocar elementos uno al lado del otro con `display: inline-block`.

---

## 2. Cómo conectar CSS con HTML

En HTMLPen tenemos dos paneles: uno para HTML y otro para CSS.  
Sin embargo, también es posible conectar un archivo CSS externo con HTML usando:

##html##
<link rel="stylesheet" href="style.css">

O escribir CSS dentro del mismo archivo HTML:

<style>
    h1 {
        color: red;
    }
</style>

CSS funciona con esta estructura:

selector {
    propiedad: valor;
}


Ejemplo básico:

body {
    background-color: lightblue;
}

---

Colores por nombre:
h1 {
    color: blue;
}

Colores hexadecimales:
p {
    color: #ff6600;
}

Formato RGB:
div {
    background-color: rgb(240, 240, 240);
}

---

Cambiar tipografía:
body {
    font-family: Arial, sans-serif;
}

Cambiar tamaño de texto:
h1 {
    font-size: 32px;
}

Alinear texto:
p {
    text-align: center;
}

Bordes:
div {
    border: 2px solid black;
}

Márgenes:
h2 {
    margin-top: 20px;
}

Espaciado interno (padding):
.container {
    padding: 15px;
}

---

Clases (se usan con un punto "."):
.titulo {
    color: purple;
    font-size: 30px;
}

<h1 class="titulo">Bienvenido</h1>

IDs (se usan con "#"):
#principal {
    background-color: yellow;
}

<div id="principal">Contenido principal</div>

--- 

Selector por elemento:
p {
    color: green;
}

Selector por clase:
.card {
    background-color: white;
    padding: 10px;
}

Selector por ID:
#caja {
    border-radius: 10px;
}

Selector múltiple:
h1, h2, h3 {
    color: navy;
}
