# 🚀 EnerkPlus  - Landing Page

Landing page profesional para producto de gel energizante a base del fruto del mezquite.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.0-purple.svg)

## 📋 Tabla de Contenidos

- [Características](#-características)
- [Tecnologías](#-tecnologías)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Secciones](#-secciones)
- [Personalización](#-personalización)
- [Animaciones](#-animaciones)
- [Responsive Design](#-responsive-design)
- [Navegadores Compatibles](#-navegadores-compatibles)


## ✨ Características

- ✅ **Diseño 100% Responsive** - Se adapta perfectamente a todos los dispositivos
- ✅ **Animaciones Suaves** - Efectos de scroll con AOS (Animate On Scroll)
- ✅ **Navegación Sticky** - Navbar que cambia al hacer scroll
- ✅ **Efectos Hover Avanzados** - Transiciones y transformaciones en tarjetas
- ✅ **Formulario de Contacto** - Con validación HTML5
- ✅ **Sección FAQ** - Acordeón interactivo con Bootstrap
- ✅ **Galería de Productos** - Cards con efectos de profundidad
- ✅ **Testimonios** - Sistema de calificación con estrellas
- ✅ **Botón Scroll-to-Top** - Navegación rápida
- ✅ **Colores Energéticos** - Paleta optimizada para productos de energía
- ✅ **SEO Friendly** - Estructura semántica HTML5
- ✅ **Performance Optimizado** - Carga rápida y eficiente


## 🛠 Tecnologías

| Tecnología | Versión | Uso |
|-----------|---------|-----|
| HTML5 | - | Estructura semántica |
| CSS3 | - | Estilos y animaciones |
| Bootstrap | 5.3.0 | Framework responsive |
| JavaScript | ES6+ | Interactividad |
| AOS | 2.3.1 | Animaciones on scroll |
| Font Awesome | 6.4.0 | Iconos |
| Google Fonts | - | Tipografía Poppins |

## 📁 Estructura del Proyecto

```
EnerkPlus/
│
├── index.html                       # Archivo principal
├── README.md                        # Este archivo
│
├── assets/                          # Carpeta de recursos
│   ├── css/
│   │   └── main.css                # Estilos personalizados
│   │
│   ├── js/
│   │   └── main.js                 # JavaScript personalizado
│   │
│   └── img/                        # Imágenes del proyecto
│       ├── logo.png
│       ├── productos/
│       └── equipo/
│
└── Dependencias (CDN):
    ├── Bootstrap CSS/JS
    ├── Font Awesome
    ├── AOS Animation Library
    └── Google Fonts (Poppins)
```


## 📑 Secciones

### 1. **Navbar** 
- Navegación sticky con efecto de transparencia
- Menú responsive con hamburger menu
- Links de navegación suave (smooth scroll)
- Logo animado

### 2. **Hero Section** (Inicio)
- Título y subtítulo impactantes
- Imagen SVG del producto con animación flotante
- Dos CTAs principales (Comprar / Conoce Más)
- Gradiente de fondo energético

### 3. **Sobre Nosotros** (About)
- Descripción de la empresa y producto
- Imagen ilustrativa con efecto hover
- Lista de beneficios principales
- Diseño en dos columnas

### 4. **Beneficios Clave** (Benefits)
- 4 tarjetas de beneficios
- Iconos animados con gradientes
- Efectos hover con elevación
- Grid responsive

### 5. **Productos** (Products)
- 3 variantes de productos
- Badges destacados (Popular, Nuevo, Recomendado)
- Precios y características
- Imágenes SVG con efectos
- Botones de compra

### 6. **Cómo Usar** (How to Use)
- 4 pasos ilustrados
- Números destacados en círculos
- Instrucciones claras
- Diseño paso a paso

### 7. **Testimonios** (Testimonials)
- 3 testimonios de clientes
- Sistema de calificación (5 estrellas)
- Avatar con iniciales
- Cards elevadas sobre fondo gradiente

### 8. **Equipo** (Team)
- 4 miembros del equipo
- Avatar con iconos
- Roles y descripciones
- Links a redes sociales

### 9. **FAQ** (Preguntas Frecuentes)
- 5 preguntas comunes
- Acordeón interactivo de Bootstrap
- Respuestas detalladas
- Diseño limpio y organizado

### 10. **Contacto** (Contact)
- Información de contacto
- Formulario funcional
- Iconos para dirección, teléfono, email
- Diseño en dos columnas

### 11. **Footer**
- Links organizados por categorías
- Redes sociales
- Copyright
- Diseño oscuro elegante

## 🎨 Personalización

### Cambiar Colores

Modifica las variables CSS en la sección `:root`:

```css
:root {
    --primary-color: #FF6B35;      /* Color principal */
    --secondary-color: #F7931E;     /* Color secundario */
    --dark-color: #2C3E50;          /* Color oscuro */
    --light-color: #ECF0F1;         /* Color claro */
    --success-color: #27AE60;       /* Color de éxito */
}
```

### Cambiar Tipografía

Reemplaza la fuente en Google Fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=TU_FUENTE:wght@300;400;600;700&display=swap" rel="stylesheet">
```

Y actualiza el CSS:

```css
body {
    font-family: 'TU_FUENTE', sans-serif;
}
```

### Modificar Contenido

1. **Textos**: Busca y reemplaza el contenido HTML directamente
2. **Imágenes**: Sustituye los SVG por tus propias imágenes:
```html
<img src="ruta/a/tu/imagen.jpg" alt="Descripción">
```
3. **Productos**: Actualiza los precios, nombres y características en la sección de productos

### Agregar/Eliminar Secciones

Cada sección está claramente marcada con comentarios:
```html
<!-- Nombre de la Sección -->
<section id="nombre-seccion">
    <!-- Contenido -->
</section>
```

## 🎬 Animaciones

### AOS (Animate On Scroll)

Atributos disponibles:
```html
data-aos="fade-up"           <!-- Tipo de animación -->
data-aos-delay="100"         <!-- Retraso en ms -->
data-aos-duration="1000"     <!-- Duración en ms -->
```

Tipos de animación usados:
- `fade-up` - Aparece desde abajo
- `fade-right` - Aparece desde la derecha
- `fade-left` - Aparece desde la izquierda
- `zoom-in` - Zoom desde el centro

### Animaciones CSS

- **Float Animation**: Efecto flotante en la imagen del hero
- **Hover Effects**: Transformaciones en cards y botones
- **Smooth Scroll**: Navegación suave entre secciones
- **Navbar Scroll**: Cambio de estilos al hacer scroll

## 📱 Responsive Design

### Breakpoints de Bootstrap

| Dispositivo | Ancho | Clases |
|------------|-------|---------|
| Extra Small | <576px | `.col-` |
| Small | ≥576px | `.col-sm-` |
| Medium | ≥768px | `.col-md-` |
| Large | ≥992px | `.col-lg-` |
| Extra Large | ≥1200px | `.col-xl-` |

### Media Queries Personalizadas

```css
@media (max-width: 768px) {
    /* Ajustes para tablets y móviles */
    .hero-title {
        font-size: 2.5rem;
    }
}
```

## 🌐 Navegadores Compatibles

- ✅ Chrome (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (últimas 2 versiones)
- ✅ Edge (últimas 2 versiones)
- ✅ Opera (últimas 2 versiones)





### SEO

- Meta tags incluidos
- Estructura semántica HTML5
- Alt text en imágenes (agregar cuando uses imágenes reales)
- URLs amigables en navegación

### Mejoras Recomendadas

```html
<!-- Meta Tags SEO -->
<meta name="description" content="Tu descripción aquí">
<meta name="keywords" content="gel energizante, energía, suplemento">
<meta name="author" content="Tu Nombre">

<!-- Open Graph (Redes Sociales) -->
<meta property="og:title" content="EnergyGel Pro">
<meta property="og:description" content="Energía Natural para tu Día">
<meta property="og:image" content="url-de-imagen.jpg">

<!-- Favicon -->
<link rel="icon" type="image/png" href="favicon.png">
```

## 🔧 Personalizar Formulario de Contacto

### Conectar con Backend

Reemplaza la función de envío del formulario:

```javascript
document.querySelector('.contact-form form').addEventListener('submit', function(e) {
    e.preventDefault();
    
    // Obtener datos del formulario
    const formData = new FormData(this);
    
    // Enviar a tu backend
    fetch('https://tu-api.com/contact', {
        method: 'POST',
        body: formData
    })
    .then(response => response.json())
    .then(data => {
        alert('¡Mensaje enviado exitosamente!');
        this.reset();
    })
    .catch(error => {
        alert('Error al enviar el mensaje');
    });
});
```


---
##
**Desarrollado con ❤️ para EnerkPlus**

**by Daniel de la Rosa**

*Última actualización: Febrero 2026*
