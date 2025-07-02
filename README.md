TP3 – Riesgos Ergonómicos

Este trabajo lo hice para la materia **Prácticas Profesionalizantes 1**, con el profe **Guido Vigiani**. El objetivo fue crear una página web informativa sobre los **riesgos ergonómicos** en el entorno de oficina, especialmente los problemas físicos como el **síndrome del túnel carpiano**, las **afecciones de columna** y la **fatiga visual**.

 Objetivo del trabajo:

Desde el inicio, quise que la página sea clara, ordenada y que transmita bien el mensaje. Por eso estructuré el contenido de forma que cualquier persona pueda leerlo y entenderlo fácilmente, sin necesidad de conocimientos técnicos.

 ¿Qué usé?

Usé solamente **HTML y CSS**. Acá explico paso a paso para qué se usó cada cosa:

 HTML – Estructura

- `<html>`: Encierra toda la página web.  
- `<head>`: Define el título, la codificación de caracteres (`UTF-8`) y contiene los estilos CSS.  
- `<title>`: Es el título que aparece en la pestaña del navegador.  
- `<style>`: Incluí todo el CSS dentro del HTML para que sea un archivo único.  
- `<body>`: Contiene todo el contenido visible de la página.

 Estructura del contenido:

- `<header>`: Encabezado principal de la página, donde puse el título y un subtítulo.  
- `<div class="container">`: Agrupa todo el contenido principal con márgenes y padding.  
- `<div class="section card">`: Secciones que presentan cada parte del contenido (definición, problemas comunes, prevención, etc.).  
- `<h1>, <h2>, <p>`: Para los títulos y los párrafos.  
- `<ul>`: Listas con viñetas para que la información se vea más clara y ordenada.  
- `<footer>`: Pie de página con información del trabajo.

También usé `class` para poder aplicar estilos desde el CSS y organizar mejor el diseño visual.

 CSS – Diseño

- **Colores y estética:** Usé una paleta sobria con azul (`#3a7ca5`) para los títulos y gris claro para el fondo, así todo es fácil de leer.  
- **Tipografía:** Elegí `'Segoe UI'` porque es limpia y moderna.  
- **Diseño responsivo:** Agregué una media query con `@media (max-width: 600px)` para que se adapte a pantallas más chicas, como celulares.  
- **Efectos visuales:** Usé `box-shadow` y `border-radius` en las tarjetas (`.card`) para dar un estilo moderno con esquinas redondeadas y sombras suaves.  
- **Listas claras:** Usé `line-height` en las listas para que no se vea todo amontonado.

 Lo que aprendí

 A lo largo del proyecto, aprendí varias cosas (y me ayudé también usando IA para entenderlas mejor):

- Cómo organizar una página en secciones claras y jerárquicas con HTML.  
- Que usar `<section>`, `<header>` y `<footer>` le da más sentido estructural a la página.  
- A crear un diseño limpio usando solo CSS.  
- Que las sombras (`box-shadow`) y bordes redondeados (`border-radius`) hacen que el contenido se vea más profesional.  
- Cómo usar `rgba()` para aplicar colores con transparencia (aunque en esta versión no lo usé, aprendí que sirve para mejorar la legibilidad cuando hay fondo con imagen).  
- Que las unidades como `em` o `rem` son mejores para adaptar a distintas pantallas (aunque acá usé principalmente `px`, ya lo voy a ir practicando).  
- Que organizar el contenido en tarjetas (`.card`) ayuda a que se entienda mejor y no sea solo un bloque largo de texto.  
- Más allá del código, también aprendí sobre ergonomía: cómo cuidar la postura, hacer pausas activas y prevenir molestias físicas por estar tantas horas frente a una pantalla.

 Resultado final

La página tiene un diseño limpio, buena legibilidad, y está pensada para informar de manera clara. No usé imágenes ni menú interactivo esta vez, pero cumple bien su función informativa.
Más allá de lo técnico, el mensaje es simple pero importante: **cuidar el cuerpo también es parte del trabajo**. Y este TP me ayudó a aprender muchísimo, tanto de ergonomía como de desarrollo web.

**Autor: Magadan Gonzalo  
**Docentes: Guido Vigiani y Lucas Cardozo 
**Materia: Prácticas Profesionalizantes 1  
