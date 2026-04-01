# Blog Personal — Martín Acosta

Sitio web personal de blog desarrollado con **HTML5**, **CSS3** y **Bootstrap 5** como Trabajo Práctico N°1 de Laboratorio de Programación y Lenguajes — UNTDF.

## 🚀 Cómo abrir el proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone <URL_del_repositorio>
   cd tp1_html
   ```

2. **Abrir en el navegador** (elegir una opción):
   - Doble click en `index.html`
   - Usar la extensión **Live Server** de VS Code (recomendado)
   - Servidor Python:
     ```bash
     python3 -m http.server 8000
     # Accedé a http://localhost:8000
     ```

## 🗺️ Navegación

| Página | Archivo | Descripción |
|--------|---------|-------------|
| Inicio | `index.html` | Hero + listado de 3 artículos |
| Acerca de mí | `about.html` | Perfil, experiencia y skills |
| Contacto | `contact.html` | Formulario de contacto |

## 📁 Estructura del proyecto

```
tp1_html/
├── index.html              # Página principal
├── about.html              # Página "Acerca de mí"
├── contact.html            # Formulario de contacto
├── assets/
│   ├── styles.css          # Estilos personalizados (dark/cyber theme)
│   └── images/
│       ├── favicon.svg     # Ícono del sitio (escudo + candado)
│       └── avatar.jpg      # Foto de perfil (agregar manualmente)
└── README.md               # Este archivo
```

## 🖼️ Agregar la foto de perfil

Guardá tu foto como `assets/images/avatar.jpg`. La página `about.html` la carga automáticamente. Si no existe, muestra un ícono de placeholder sin romper el diseño.

## ✅ Criterios de aceptación del TP

- **HTML válido**: Sin errores W3C — validar en https://validator.w3.org/
- **CSS válido**: Sin errores — validar en https://jigsaw.w3.org/css-validator/
- **Todas las páginas funcionan**: Links internos sin 404
- **Formulario**: campos nombre, email, teléfono (opcional) y mensaje con validación HTML5
- **Feedback visual**: `:valid` en verde (`#00d4aa`), `:invalid` en rojo (`#ff4d6d`)
- **Navbar responsiva**: menú colapsable funciona en mobile y desktop
- **Bootstrap bien usado**: grid, cards, navbar, utilities
- **CSS limpio**: variables CSS, clases BEM, sin duplicación
- **Breadcrumbs** en `about.html` y `contact.html`
- **Accesibilidad**: ARIA labels, contraste, `alt` en imágenes

## 🎨 Personalización

### Colores (en `assets/styles.css`):
```css
:root {
    --accent:       #00d4aa;   /* Color principal (cyan/teal) */
    --bg-primary:   #0a0e1a;   /* Fondo oscuro principal */
    --text-primary: #e2e8f0;   /* Texto principal */
    --error-color:  #ff4d6d;   /* Color :invalid */
}
```

### Tipografía:
- Títulos: **Space Grotesk** (Google Fonts)
- Cuerpo: **Inter** (Google Fonts)
- Monospace / código: **JetBrains Mono** (Google Fonts)

## 🧪 Validación

```bash
# Abrir el validador y subir el archivo HTML
# https://validator.w3.org/#validate_by_upload+with_options

# O validar por URL si tenés el sitio publicado
# https://validator.w3.org/#validate_by_uri
```

## 📚 Recursos utilizados

- [Bootstrap 5](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Google Fonts – Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk)
- [MDN: HTML5](https://developer.mozilla.org/es/docs/Web/HTML)
- [MDN: CSS](https://developer.mozilla.org/es/docs/Web/CSS)

---

**Autor**: Martín Acosta  
**Carrera**: Analista Universitario de Sistemas — UNTDF  
**Materia**: Laboratorio de Programación y Lenguajes  
**Entrega**: 31/03/2026
