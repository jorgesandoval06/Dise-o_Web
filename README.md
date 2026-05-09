## Propósito y Buenas Prácticas Aplicadas

### Propósito

Este proyecto consiste en una página web desarrollada en HTML5 para la visualización de cursos en línea.  
El objetivo principal es aplicar una estructura semántica adecuada y mejorar la accesibilidad del sitio web siguiendo buenas prácticas de desarrollo frontend.

---

### Buenas prácticas implementadas

#### Uso de etiquetas semánticas HTML5
Se utilizaron etiquetas como:

- `<header>`
- `<main>`
- `<section>`
- `<article>`
- `<nav>`
- `<footer>`

Estas etiquetas permiten organizar correctamente el contenido y mejorar la interpretación del sitio por navegadores y lectores de pantalla.

---

#### Jerarquía correcta de encabezados
Se corrigió la estructura de títulos evitando saltos incorrectos entre niveles de encabezados (`h1`, `h2`, etc.), mejorando la accesibilidad y el SEO.

Ejemplo:

```html
<h1>Cursos En Línea</h1>
<h2>HTML5, CSS3 y JavaScript</h2>
Accesibilidad en imágenes

Todas las imágenes incluyen el atributo alt para proporcionar descripciones alternativas.

Ejemplo:

<img src="img/logo.jpg" alt="Logo de la plataforma">
Organización del contenido

El contenido fue dividido en secciones claras y estructuradas para facilitar la navegación y el mantenimiento del código.

Organización de recursos

Los archivos del proyecto están organizados en carpetas independientes:

/css
/js
/img

Esto facilita el mantenimiento y la escalabilidad del proyecto.
