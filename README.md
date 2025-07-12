# 📘 EJERCICIOS DE LA CERTIFICACIÓN AVANZADA DE FULL STACK DEVELOPER

Cada carpeta corresponde a una semana de ejercicios y contiene las actividades junto con los temas aprendidos a medida que avanza el curso.

---

## 🚀 SPRINT 1

### 📅 SEMANA 1 – Introducción a HTML

#### ✨ Ejercicio 1: Tu Página de Presentación Personal

**Tiempo de resolución estimado:** 20 minutos  
**Objetivo:** Practicar la estructura básica de un documento, el uso de títulos, párrafos, imágenes y enlaces.
**tareas:**

1. Creá un archivo llamado `mi_perfil.html`.  
2. Dale una estructura HTML completa (`<!DOCTYPE>`, `<html>`, `<head>`, `<body>`).  
3. En el `<head>`, pon un `<title>` que diga "Perfil de [Tu Nombre]".  
4. En el `<body>`, añade un título principal (`<h1>`) con tu nombre completo.  
5. Debajo del título, inserta una foto tuya (o una imagen de placeholder) usando la etiqueta `<img>`. No olvides el atributo `alt` con una descripción. 
6. Escribí una breve biografía de dos o tres párrafos usando la etiqueta `<p>`. En alguna parte de tu biografía, usa `<strong>` para resaltar tu principal habilidad o interés.  
7. Añadí un subtítulo `<h2>` que diga "Mis Proyectos".  
8. Creá una lista no ordenada (`<ul>`) donde cada ítem de la lista (`<li>`) sea un enlace (`<a>`) a un proyecto ficticio en GitHub. Por ejemplo: `<a href="#">`Proyecto Tienda Online`</a>`. Haz que estos enlaces se abran en una nueva pestaña.

#### ✨ Ejercicio 2: La Receta de tu Comida Favorita

**Tiempo de resolución estimado:** 25 minutos  
**Objetivo:** Dominar el uso de listas ordenadas, no ordenadas y el formato de texto.
**tareas:**

1. Creá un archivo `receta.html`.  
2. El `<h1>` de la página será el nombre de tu comida favorita.  
3. Añadí una imagen (`<img>`) del platillo.  
4. Creá una sección con un `<h2>` que diga "Ingredientes".
5. Debajo, usa una lista no ordenada (`<ul>`) para enumarar todos los ingredientes necesarios. 
6. Creá una sección con `<h2>` que diga "Instrucciones".
7. Debajo, usa una lista ordenada (`<ol>`) para detallar, paso a paso, cómo se prepara la receta. 
8. Dentro de las instrucciones, usar la etiqueta `<em>` para dar énfasis a palabras clave como "con cuidado", "lentamente", "hasta que dore".

#### ✨ Ejercicio 3: Estructura Semántica de un Blog

**Tiempo de resolución estimado:** 30 minutos  
**Objetivo:** Practicar el uso correcto de las etiquetas semánticas de HTML5 para estructurar una página. No te preocupes por el estilo, solo por la estructura correcta.
**tareas:**

1. Creá un archivo `blog.html`.  
2. Usá la etiqueta `<header>` para la parte superior de la página. Dentro, coloca el `<h1>` del blog (ej: "Mi Blog de Aventuras") y una etiqueta `<nav>` con una lista de enlaces ("Inicio", "Acerca de", "Contacto").  
3. Usá la etiqueta `<main>` para envolver el contenido principal. 
4. Dentro de `<main>`, usá una etiqueta `<article>` para el post del blog. Este artículo debe tener su propio título (`<h2>`), varios párrafos (`<p>`) y una imagen.  
5. Dentro del `<article>`, creá dos sub-secciones temáticas usando (`<section>`), cada una con su propio `<h3>` (ej: "El Viaje" y "La Comida").  
6. Al lado del `<article>` (pero todavía dentro de `<main>`), añade una barra lateral usando (`<aside>`). Dentro, poné un `<h3>` que diga "Artículos Populares" y una lista de enlaces a otros posts.
7. Finalmente, usá la etiqueta `<footer>` al final del `<body>` para la información de copyright.  

#### ✨ Ejercicio 4: Tabla Comparativa de Laptops  

**Tiempo de resolución estimado:** 25 minutos  
**Objetivo:** Construir una tabla de datos bien estructurada, utilizando sus etiquetas semánticas y atributos para fusionar celdas.
**tareas:**

1. Creá un archivo `comparativa.html`.  
2. Insertá una `<table>` con un `<caption>` que diga  "Comparativa de Laptops 2025".  
3. Usá `<thead>` (`<tr>`) para la fila de encabezado. La fila (`<th>`) para "Modelo", "Procesador", "Memoria RAM" y "Almacenamiento". No olvides el atributo `scope="col"`.  
4. Usá`<tbody>`para añadir al menos tres laptops diferentes, cada una en su propia fila (`<tr>`) con sus datos en celdas `<td>`.  
5. Añadí una última fila que represente una "Oferta Especial". En esta fila, la primera celda (`<td>`) contendrá el texto de la oferta y deberá expandirse a lo ancho de 4 columnas usando el atributo colspan.

#### ✨ Ejercicio 5: Formulario de Inscripción a un Evento  

**Tiempo de resolución estimado:** 35 minutos  
**Objetivo:** Crear un formulario completo y accesible, utilizando una variedad de campos de entrad
**tareas:**

1. Creá un archivo `inscripcion.html`.  
2. Envolvé todo en una etiqueta `<form>`.  
3. Creá los siguientes campos, asegurándote de que cada uno tenga una etiqueta`<label>` asociada correctamente con los atributos for e id:
   - Nombre Completo: Un (`type="text"`)  
   - Correo Electrónico: Un (`type="email"`)  
   - Crear Contraseña: Un (`type="password"`)  
   - Taller de interés: Un menú desplegable (`<select>`) con al menos tres talleres como opciones (<option>).
   - Tipo de Asistencia: Usa dos (`<input type="radio">`) con el mismo name para las opciones "Presencial" y "Virtual".
   - Acepto los términos y condiciones: Un (`<input type="checkbox">`)  
   - Comentarios adicionales: Un (`<textarea rows="5">`) con 5 filas de alto.
4. Añadí un botón de envío al final:`<button type="submit">Inscribirme</button>`.  

## 🚀 SPRINT 2

### 📅 SEMANA 2 – Introducción a CSS

#### ✨ Ejercicio 1: Estilizando una Biografía

**Tiempo de resolución estimado:** 25 minutos  
**Objetivo:** Practicar el uso de selectores básicos (tipo, clase, ID) y las propiedades fundamentales de texto.
**tareas:**

1. Creá un archivo `biografia.html` y un `estilos.css` enlazado a él.  
2. En el HTML, crea una página simple sobre tu personaje histórico o artista favorito. Debe incluir un `<h1>` para el nombre, un `<h2>` para "Biografía", varios párrafos `<p>` y otro `<h2>` para "Obras Notables" con una lista `<ul>`.
3. En tu CSS:  
   - Usa un selector de tipo para que todos los párrafos `(p)` tengan una ` font-family` y `font-size` específicas.
   - Dale al `<h1>` un id único (ej: `id="titulo-principal`") y usá un selector de ID para centrar el texto (`text-align: center`) y darle un color único.
   - Dale a los `<h2>` una misma class (ej: `class="subtitulo`") y usá un selector de clase para cambiarles el color y añadirles un `font-weight: bold;`.
   - Usá un selector descendente `(ul a)` para quitarle el subrayado a cualquier enlace que esté dentro de una lista (`text-decoration: none `). 

#### ✨ Ejercicio 2: Tarjeta de Presentación

**Tiempo de resolución estimado:** 20 minutos  
**Objetivo:** Enfocarse y dominar el Modelo de Cajas (padding, border, margin).
**tareas:**

1. Creá un `<div>` principal en tu HTML con la clase tarjeta-presentacion.
2. Dentro de la tarjeta, añade un `<h2>` con un nombre, un `<p>` con un cargo y otro `<p>` con un email.
3. En tu CSS: 
   - Seleccioná la clase `.tarjeta-presentacion`.
   - Dale un width fijo de 350px.
   - Añadí un padding de 25px para que el contenido no esté pegado a los bordes.
   - Creá un border sutil, por ejemplo: `1px solid #cccccc;`.
   - Añadí una sombra suave para que parezca que "flota" con la propiedad `box-shadow: 5px 5px 10px #e0e0e0;`.
   - Finalmente, usa `margin: 40px auto;` para centrar la tarjeta horizontalmente en la página y darle un espacio superior.

#### ✨ Ejercicio 3: Galería de Imágenes Fluida

**Tiempo de resolución estimado:** 30 minutos  
**Objetivo:** Usar Practicar el uso de `display: flex` para crear un layout básico y el uso de porcentajes para un diseño fluido 
**tareas:**

1. En tu HTML, crea un `<div>` contenedor con la clase galeria. Dentro, coloca tres de las "tarjetas" del ejercicio anterior (puedes usar un `<div>` con la clase tarjeta-foto para cada una). Cada tarjeta debe contener una imagen `<img>` y un pie de foto `<p>`.
2. En tu CSS:
   - Aplica la regla universal de `box-sizing: border-box;` al inicio de tu archivo.
   - Seleccioná `.galeria` y aplícale `display: flex;` para que sus hijos (las tarjetas) se pongan uno al lado del otro. Usa `gap: 20px;` para crear un espacio entre ellas.
   - Seleccioná `.tarjeta-foto` y dale un width en porcentaje (ej: 30%) para que el layout sea fluido.
   Añadí una regla para que las imágenes (img) dentro de las tarjetas nunca se desborden: `width: 100%; height: auto;.`

#### ✨ Ejercicio 4: Galería Responsiva

**Tiempo de resolución estimado:** 35 minutos  
**Objetivo:** Implementar Media Queries para que el diseño del ejercicio anterior se adapte a pantallas de móvil.
**tareas:**

1. Asegurate de tener la meta etiqueta viewport en tu HTML.
2. Adoptá un enfoque Mobile-First. En tus estilos base (fuera de cualquier media query), haz que `.galeria` se apile verticalmente: `flex-direction: column;`. Las tarjetas (tarjeta-foto) deberían ocupar casi todo el ancho, por ejemplo `width: 95%`. 
3. Ahora, añadí una Media Query al final de tu archivo CSS: `@media (min-width: 768px) { ... }`. Este será nuestro "breakpoint" para tablets y escritorios.
4. Dentro de la media query, sobreescribe los estilos para pantallas grandes:
   - Cambiá `.galeria` para que vuelva a ser horizontal: `flex-direction: row;`.
   - Ajustá el ancho de `.tarjeta-foto` a un porcentaje más pequeño para que quepan varias en una fila, por ejemplo `width: 31%`.
5. Abrí la página en tu navegador y cambia el tamaño de la ventana. ¡Observa cómo el layout cambia de una columna a varias

#### ✨ Ejercicio 5: Hero Banner de Pantalla Completa

**Tiempo de resolución estimado:** 40 minutos  
**Objetivo:** Combinar todos los conceptos, incluyendo unidades de viewport (`vh`) y `display: flex;` para centrado vertical y horizontal. 
**tareas:**

1. Creá una sección <header> con la clase hero-banner. Dentro, coloca un `<h1>` y un `<p>` con un llamado a la acción.
2. En tu CSS:
   - Usa el reseteo universal `* { margin: 0; padding: 0; box-sizing: border-box; }`.
   - Seleccioná `.hero-banner` y haz que ocupe el 100% de la altura de la ventana del navegador con `height: 100vh;`.
   - Dale un color de fondo o una imagen de fondo.
   - Para centrar el texto perfectamente, usa la "magia" de Flexbox: CSS
   - Estilizá el `<h1>` y el `<p>` dentro del banner (color, tamaño de fuente, etc.). Usa una media query para reducir el font-size del `<h1>` en pantallas pequeñas y que no se vea desproporcionado.