<h1>Bienvenida</h1>
“Bienvenidos a la Sesión 2, titulada Estructura Básica de HTML.
En la primera sesión conocimos qué es el desarrollo web y por qué es tan importante en la actualidad.
Ahora vamos a dar el siguiente paso: entender cómo se construye una página web por dentro, usando el lenguaje base de la web: HTML.”

“HTML es el primer idioma que aprende casi todo desarrollador web.
De hecho, su primera versión nació en 1993, creada por Tim Berners-Lee, el inventor de la World Wide Web.
Así que, cuando escribimos HTML, estamos usando prácticamente el mismo formato que dio inicio a todo Internet.”

“Durante esta sesión no vamos a hacer una página con diseño o estilos todavía.
Hoy aprenderemos a crear el esqueleto de una página, la estructura sobre la que después se construye todo.”

<h1>Objetivo</h1>
“El objetivo de la sesión es reconocer y escribir el esqueleto mínimo de una página HTML.
Eso significa que al final de la clase sabrán exactamente qué partes no pueden faltar para que el navegador entienda que lo que escribimos es una página web.”

“Parece sencillo, pero sin esta estructura, el navegador no sabría ni dónde empieza ni dónde termina el contenido.”

<h1>¿Qué es un documento HTML?</h1>
“Veamos primero cómo luce un documento HTML muy básico.
En pantalla tenemos un ejemplo que se ve así:”

“Esto que están viendo es la estructura más simple de una página web.
HTML usa etiquetas —que se escriben entre símbolos de menor y mayor que— para organizar el contenido.”

“Por ejemplo, <HEAD> se abre y </HEAD> se cierra.
Todo lo que esté entre esas dos etiquetas pertenece a la sección head del documento.”

“Las etiquetas casi siempre trabajan en pareja: una etiqueta de apertura y otra de cierre.
Aunque algunas, como <img> o <br>, se pueden usar solas, pero eso lo veremos más adelante.”

“En este ejemplo, el navegador no muestra las etiquetas, solo el contenido que está dentro del <BODY>.
Si abrimos esto en CodePen, veremos únicamente el texto Hola mundo.
Y este texto se muestra porque está dentro del <BODY>.”

“Dato curioso: la frase Hola mundo es un clásico en programación.
Se usa en casi todos los lenguajes como la primera prueba para saber si todo está funcionando correctamente.
Así que, si ves ‘Hola mundo’, ¡felicidades! tu HTML funciona.”

“Por cierto, aunque aquí las etiquetas están en mayúscula, hoy en día se recomienda escribirlas en minúscula.
Los navegadores modernos lo aceptan igual, pero mantener minúsculas es una buena práctica profesional.”

<h1>El esqueleto mínimo</h1>
“Ahora pasemos al esqueleto mínimo de una página moderna.
Esto es lo que todo documento HTML debe tener si queremos que funcione correctamente.”

“Vamos a explicarlo paso a paso.”

“Primero, la línea <!DOCTYPE html> le indica al navegador que el documento está escrito en HTML5, la versión más actual.
Es como una presentación: el navegador ve esa línea y dice: ‘Ah, esto es HTML moderno’.”

“Después tenemos <html *lang="es">, que abre el documento y le dice al navegador que el idioma principal es español.
Si el sitio fuera en inglés, podríamos usar lang="en".
Este atributo es importante, especialmente para la accesibilidad, ya que permite que lectores de pantalla o traductores automáticos interpreten correctamente el idioma.”

“Dentro del <head> colocamos información sobre la página que no se muestra directamente al usuario.
Por ejemplo, el <meta *charset=" UTF-8"> evita que aparezcan caracteres raros cuando escribimos palabras con acento o la letra ñ.”

“El <title> define el nombre que aparece en la pestaña del navegador.
Si ahora mismo cambio el título de ‘Mi Primera Web’ a ‘Página de Mathias’, el cambio se reflejará inmediatamente en la parte superior de CodePen.”

“Finalmente tenemos el <body>, que contiene todo lo visible: texto, imágenes, botones, listas, etc.”

“Si dentro del body escribimos un encabezado <*h1> y un párrafo **<p>, veremos cómo el navegador los muestra con diferentes tamaños.”

“El navegador interpreta cada etiqueta de manera diferente:
<*h1> significa un título principal, y <**p> un párrafo normal.”

“Dato interesante: HTML no se inventó pensando en diseño, sino en estructura y significado.
Por eso el <*h1> no dice cómo debe verse, sino que indica que es el título más importante.
El diseño vendrá después, con CSS.”

<h1>Head vs Body</h1>
“Ahora comparemos las dos partes principales: el head y el body.”

“Todo lo que va en el head no se ve directamente en la página, pero el navegador lo usa para entender cómo debe interpretarla.
Por ejemplo, allí se incluyen el título, las metaetiquetas, y los enlaces a hojas de estilo CSS o scripts.”

“En cambio, el body es lo que realmente vemos: los encabezados, los párrafos, las imágenes, los enlaces.”

“Podríamos decir que el head es como el cerebro de la página, y el body es el cuerpo visible.”

“Vamos a probar algo: en CodePen, cambien el texto del <title> y escriban su nombre completo.
Noten cómo el título de la pestaña cambia automáticamente.
Esa información está en el head, no en el body.”

“Y si agrego algo dentro del body, por ejemplo, un nuevo párrafo, el cambio sí se verá directamente en el contenido de la página.”

<h1>Mini reto</h1>
“Ya que conocemos la estructura, hagamos un pequeño reto: crear una mini página personal.”

“Para hacerlo, abrimos un nuevo Pen y copiamos la estructura básica.”

“Aquí tenemos una página que cumple con todas las reglas:
tiene un DOCTYPE, un <head> con título y codificación, y un <body> con el contenido visible.”

“Un dato curioso: el nombre del archivo más común para empezar una página se llama index.html.
¿Por qué? Porque los servidores web, cuando reciben una visita sin una ruta específica, buscan automáticamente un archivo llamado index.
Por eso, si quieren que su página principal se abra sola, deben llamarla así.”

“Así que ya lo saben: si crean un proyecto y su archivo principal no se abre, revisen si se llama index.html.”

<h1>Cierre</h1>
“Hoy aprendimos algo fundamental: toda página HTML tiene la misma estructura básica.
Inicia con <!DOCTYPE html>, sigue con la etiqueta <html>, y dentro están <head> y <body>.”

“El head contiene la información general, invisible para el usuario, y el body contiene todo lo que vemos.”

“Sin esta base, no podríamos aplicar estilos ni añadir interactividad más adelante.”

“En la próxima sesión aprenderemos a añadir más elementos: imágenes, enlaces y listas, para hacer que nuestra página cobre vida.”

“Y recuerden algo: no hay buen programador web que no conozca su esqueleto de HTML de memoria.”
