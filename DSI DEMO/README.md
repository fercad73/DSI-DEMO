# Biblioteca de Componentes UI

![Demo Preview](preview.png)

Una biblioteca de componentes de interfaz de usuario reutilizables construida con CSS avanzado para la Universidad Técnica de Manabí.

## 📋 Características

- ✅ 8 componentes UI completamente funcionales
- ✅ Diseño responsive (mobile-first)
- ✅ Accesibilidad (ARIA, contraste, navegación por teclado)
- ✅ Animaciones y transiciones CSS
- ✅ Variables CSS para fácil personalización
- ✅ Metodología BEM para nombres de clases
- ✅ Documentación completa

## 🚀 Componentes Incluidos

1. **Botones** - Variantes primarias, secundarias, estados hover/disabled
2. **Tarjetas** - Diseños flexibles con imágenes y efectos hover
3. **Formularios** - Inputs, selects, checkboxes con validación visual
4. **Navegación Responsiva** - Menú hamburguesa para móviles
5. **Modales** - Ventanas emergentes con animaciones
6. **Tooltips** - Información contextual en todas direcciones
7. **Alertas** - Mensajes de feedback con iconos
8. **Acordeón** - Contenido colapsable con animaciones

## 📁 Estructura del Proyecto
biblioteca-ui/
├── index.html # Página demo principal
├── styles/
│ ├── base.css # Variables CSS y estilos base
│ ├── components.css # Todos los componentes UI
│ └── demo.css # Estilos específicos para la demo
├── README.md # Este archivo
└── componentes-guia.pdf # Guía de uso en formato PDF

text

## 🛠️ Instalación y Uso

### Opción 1: Usar directamente
```html
<link rel="stylesheet" href="styles/base.css">
<link rel="stylesheet" href="styles/components.css">
Opción 2: Personalizar variables
Modifica las variables CSS en :root dentro de base.css:

css
:root {
    --color-primary: #tu-color;
    --font-primary: 'Tu Fuente', sans-serif;
    /* etc. */
}
🎨 Guía de Estilos
Paleta de Colores
Primario: #4a6fa5

Secundario: #6c757d

Éxito: #28a745

Peligro: #dc3545

Advertencia: #ffc107

Info: #17a2b8

Tipografía
Familia principal: 'Segoe UI', sans-serif

Tamaño base: 16px

Escala modular: 0.875rem, 1rem, 1.25rem, 1.5rem, 2rem

Espaciado
Sistema basado en 8px (0.5rem):

xs: 0.25rem (4px)

sm: 0.5rem (8px)

md: 1rem (16px)

lg: 1.5rem (24px)

xl: 2rem (32px)

📱 Diseño Responsive
La biblioteca utiliza un enfoque mobile-first con los siguientes breakpoints:

Mobile: < 768px (predeterminado)

Tablet: 768px - 1024px

Desktop: > 1024px

♿ Accesibilidad
Todos los componentes incluyen:

Contraste adecuado de colores (ratio 4.5:1)

Estados focus visibles

Etiquetas ARIA cuando es necesario

Navegación por teclado

Textos alternativos para imágenes

📝 Ejemplos de Uso
Botón Primario
html
<button class="btn btn--primary">Botón Primario</button>
Tarjeta con Imagen
html
<div class="card">
    <div class="card__header">
        <img src="imagen.jpg" alt="Descripción" class="card__image">
    </div>
    <div class="card__body">
        <h3 class="card__title">Título</h3>
        <p class="card__text">Contenido de la tarjeta</p>
    </div>
</div>
Formulario con Input
html
<div class="form-group">
    <label for="email" class="form-label">Email</label>
    <input type="email" id="email" class="form-control" placeholder="ejemplo@correo.com">
</div>
🧪 Tecnologías Utilizadas
HTML5: Estructura semántica

CSS3: Variables, Grid, Flexbox, Animaciones, Media Queries

Font Awesome: Iconos para componentes

BEM: Metodología para nombres de clases

📄 Licencia
Este proyecto fue desarrollado para fines educativos como parte de la asignatura de Desarrollo de Sistemas Informáticos de la Universidad Técnica de Manabí.

👨‍💻 Autor
Nombre: Fernando Renen Cadena Cheza

Curso: Desarrollo de Sistemas Informáticos

Universidad: Universidad Técnica de Manabí

Fecha: Diciembre 2025