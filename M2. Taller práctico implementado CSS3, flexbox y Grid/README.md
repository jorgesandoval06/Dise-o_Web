# Dashboard Administrativo Responsive

## Descripción

Este proyecto consiste en el desarrollo de un dashboard administrativo responsive para un sistema de gestión. El dashboard permite visualizar información de inventario, ventas, usuarios y pedidos mediante componentes modernos e interactivos.

El sistema fue desarrollado utilizando HTML5, CSS3 y JavaScript, implementando buenas prácticas de diseño responsive, accesibilidad y organización del código.

---

# Objetivos del proyecto

- Implementar un layout moderno utilizando CSS Grid.
- Utilizar Flexbox para la alineación interna de componentes.
- Crear componentes interactivos y visualmente atractivos.
- Adaptar el dashboard a diferentes dispositivos.
- Aplicar buenas prácticas de accesibilidad y diseño web.

---

# Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- CSS Grid
- Flexbox
- Media Queries
- Font Awesome
- Git y GitHub

---

# Características principales

## Layout avanzado

- Sidebar lateral responsivo
- Header superior
- Área principal adaptable
- Footer informativo
- Uso de grid-template-areas

## Componentes interactivos

- Tarjetas dinámicas
- Gráficas animadas
- Tabla responsive
- Menú lateral interactivo
- Efectos hover y focus

## Dashboard dinámico

Al seleccionar opciones del menú lateral:

- Cambian los valores de las tarjetas
- Cambian las gráficas
- Cambia la información de la tabla

## Responsividad

El dashboard se adapta correctamente a:

- Escritorio
- Tablet
- Dispositivos móviles

## Accesibilidad

Se implementaron:

- Roles ARIA
- Navegación por teclado
- Contraste adecuado
- Etiquetas semánticas
- Texto alternativo en imágenes

---

# Estructura del proyecto

```plaintext
dashboard-admin/
│
├── index.html
├── styles.css
├── README.md
│
├── assets/
│   └── images/
│
└── evidencias/
    ├── escritorio.png
    ├── tablet.png
    └── movil.png
```

---

# Capturas de pantalla

## Vista escritorio

![Vista escritorio](evidencias/escritorio.png)

---

## Vista tablet

![Vista tablet](evidencias/tablet.png)

---

## Vista móvil

![Vista móvil](evidencias/movil.png)

---

# Funcionalidades implementadas

## Sidebar interactivo

El menú lateral permite navegar entre diferentes módulos:

- Inicio
- Inventario
- Ventas
- Usuarios
- Reportes
- Configuración

Cada sección actualiza dinámicamente la información del dashboard.

---

## Tarjetas de resumen

Las tarjetas muestran información importante:

- Ventas
- Usuarios
- Productos
- Pedidos

Incluyen:

- Hover animado
- Iconos
- Sombras
- Transiciones suaves

---

## Gráficas dinámicas

Se implementaron gráficas visuales utilizando barras animadas con gradientes y transiciones CSS.

Las gráficas cambian dinámicamente dependiendo de la opción seleccionada en el menú.

---

## Tabla responsive

La tabla permite visualizar información de productos y estados.

Características:

- Diseño adaptable
- Hover en filas
- Estados visuales
- Scroll horizontal en dispositivos pequeños

---

# Decisiones de diseño

## CSS Grid

Se utilizó CSS Grid para organizar la estructura principal del dashboard:

- Sidebar
- Header
- Main
- Footer

Esto permitió crear un layout flexible y limpio.

---

## Flexbox

Se utilizó Flexbox para:

- Alinear tarjetas
- Organizar menús
- Distribuir componentes internos
- Mejorar la adaptabilidad

---

## Variables CSS

Se implementaron custom properties para:

- Colores
- Sombras
- Fondos
- Estilos reutilizables

Ejemplo:

```css
:root{
    --primary-color:#2563eb;
}
```

---

# Responsividad

Se utilizaron Media Queries para adaptar el diseño a diferentes resoluciones.

## Desktop

- Sidebar lateral
- Cards horizontales
- Tabla completa

## Tablet

- Cards verticales
- Espaciado reducido

## Mobile

- Sidebar adaptable
- Cards en columna
- Tabla scrollable

---

# Accesibilidad implementada

## Roles ARIA

```html
role="navigation"
role="main"
role="banner"
```

## Navegación teclado

Se añadieron estilos focus:

```css
.menu a:focus{
    outline:none;
}
```

## Contraste de colores

Se utilizaron colores con contraste adecuado para mejorar la legibilidad.

---

# Instalación y ejecución

## Clonar repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

## Abrir proyecto

```bash
cd dashboard-admin
```

## Ejecutar

Abrir el archivo:

```plaintext
index.html
```

O utilizar Live Server en Visual Studio Code.

---

# Repositorio GitHub

Repositorio del proyecto:

```plaintext
https://github.com/usuario/dashboard-admin-responsive
```

---

# Autor

Jorge

Proyecto académico de Diseño Web Responsive.