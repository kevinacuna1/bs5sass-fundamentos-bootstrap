# 🚀 Fundamentos de Bootstrap 5

Proyecto introductorio para aprender los conceptos básicos de **Bootstrap 5**, el framework CSS más popular para desarrollo web responsivo.

---

## 📋 Contenido

- [¿Qué es Bootstrap?](#qué-es-bootstrap)
- [Características](#características)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Temas Cubiertos](#temas-cubiertos)
- [Fundamentos Iniciales](#fundamentos-iniciales)
- [Recursos](#recursos)

---

## ¿Qué es Bootstrap?

**Bootstrap** es un framework front-end de código abierto que facilita el desarrollo de sitios web responsivos y móviles. Proporciona:

- 📱 Diseño adaptable (responsive)
- 🎨 Componentes predefinidos
- 🔧 Utilidades CSS
- ♿ Accesibilidad mejorada

---

## ✨ Características

- Sistema de grilla flexible (12 columnas)
- Componentes reutilizables (botones, tarjetas, formularios, etc.)
- Diseño mobile-first
- Temas personalizables
- Documentación completa y comunidad activa

---

## 📁 Estructura del Proyecto

```
📦 01-Introduccion/
├── 📄 index.html              # Página principal
├── 📄 README.md               # Este archivo
├── 📂 css/
│   ├── bootstrap.min.css      # Bootstrap CSS minificado
│   └── app.css                # Estilos personalizados
├── 📂 js/
│   └── bootstrap.bundle.min.js # Bootstrap JS bundled
└── 📂 img/                     # Imágenes del proyecto
```

---

## 🎯 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime Text, etc.)
- Conexión a internet (opcional, para CDN)

---

## 📥 Instalación

### Opción 1: Usando archivos locales

1. Clona o descarga este repositorio
2. Abre `index.html` en tu navegador
3. ¡Listo para comenzar!

### Opción 2: Usando CDN

```html
<!-- Bootstrap CSS -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
  rel="stylesheet"
/>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

---

## 💡 Uso

### Estructura HTML básica

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Proyecto Bootstrap</title>
    <link rel="stylesheet" href="css/bootstrap.min.css" />
  </head>
  <body>
    <!-- Contenido aquí -->
    <script src="js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```

### Grid System

```html
<div class="container">
  <div class="row">
    <div class="col-md-4">Columna 1</div>
    <div class="col-md-4">Columna 2</div>
    <div class="col-md-4">Columna 3</div>
  </div>
</div>
```

---

## 🎓 Temas Cubiertos

### 1️⃣ Introducción y Configuración

- ✅ **1.** Introducción a Bootstrap
- ✅ **2.** Cómo Instalar Bootstrap
- ✅ **3.** Contenedores en Bootstrap
- ✅ **4.** Media Queries en Bootstrap

### 2️⃣ Sistema de Layout

- ✅ **5.** El Grid de Bootstrap
- ✅ **13.** Display Grid y Gap

### 3️⃣ Tipografía y Contenido

- ✅ **6.** Tipografía
- ✅ **7.** Utilidades Para Tipografía
- ✅ **9.** Imágenes en Bootstrap

### 4️⃣ Colores y Estilos

- ✅ **8.** Colores en Bootstrap
- ✅ **12.** Margin y Paddings

### 5️⃣ Componentes Básicos

- ✅ **10.** Botones
- ✅ **11.** Bootstrap Icons
- ✅ **15.** Spinners

### 6️⃣ Componentes Interactivos

- ✅ **17.** Cards
- ✅ **18.** Formularios
- ✅ **21.** Carousel
- ✅ **22.** Ventanas Modal
- ✅ **23.** Navegación
- ✅ **24.** Dropdown Menu
- ✅ **25.** Off Canvas

### 7️⃣ Notificaciones

- ✅ **19.** Notificaciones Toasts
- ✅ **20.** Toast y Accesibilidad

### 8️⃣ JavaScript y Componentes Avanzados

- ✅ **14.** Componentes JavaScript en Bootstrap

### 9️⃣ Accesibilidad

- ✅ **16.** Bootstrap y la Accesibilidad

---

## 🚀 Fundamentos Iniciales

### Introducción al Entorno de Trabajo

Bootstrap será la base de los proyectos que desarrollarás a lo largo del curso. Para trabajar correctamente con el framework, es esencial conocer su sitio oficial, donde encontrarás:

- 📚 Documentación completa
- 🎨 Ejemplos y componentes
- 🔧 Utilidades y guías de uso
- 📥 Descargas oficiales

👉 **Sitio oficial:** https://getbootstrap.com

Bootstrap se actualiza con frecuencia debido a su naturaleza open source. Cientos de colaboradores corrigen errores y agregan mejoras continuamente, por lo que el número de versión cambia de forma habitual.

---

### 📦 Métodos de Instalación de Bootstrap

A continuación se presentan las tres formas oficiales de instalar Bootstrap, con sus ventajas, desventajas y recomendaciones profesionales.

#### 1. Instalación mediante CDN

**📘 Descripción**

Un CDN aloja los archivos ya compilados de Bootstrap. Para utilizarlo, solo necesitas agregar las etiquetas `<link>` y `<script>` que provee la documentación oficial.

👉 **Documentación oficial:** https://getbootstrap.com/docs/5.3/getting-started/introduction/

**🔗 CDN oficial — Bootstrap 5.3.8**

```html
<!-- CSS -->
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
/>

<!-- JavaScript (bundle con Popper) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
```

**✔️ Ventajas**

- No requiere descargas
- Reduce el consumo de recursos del servidor
- Ideal para prototipos y proyectos rápidos

**⚠️ Desventajas**

- Requiere conexión a internet para desarrollar
- No es adecuado para trabajo offline
- Dependencia de un servicio externo

---

#### 2. Instalación mediante Archivos Descargados

**📘 Descripción**

Puedes descargar un archivo ZIP con las versiones compiladas de CSS y JavaScript.

👉 **Descarga oficial:** https://getbootstrap.com/docs/5.3/getting-started/download/

**📁 Contenido del paquete**

**Carpeta css/**

- `bootstrap.css`
- `bootstrap.min.css` ⭐ _Recomendado_
- `bootstrap.css.map`
- Archivos individuales: `grid.css`, `reboot.css`, `utilities.css`, etc.

**Carpeta js/**

- `bootstrap.bundle.js` y `bootstrap.bundle.min.js` ⭐ _Recomendado_
- `bootstrap.js` y `bootstrap.min.js`
- Versiones ES Modules (`.esm.js`)

**✔️ Ventajas**

- Permite trabajar sin conexión
- Evita redes públicas o inseguras
- Mayor control sobre los archivos

**⚠️ Desventajas**

- Cada visita descarga los archivos desde tu servidor
- El CSS completo pesa ~200 KB (optimizable con PurgeCSS)

**⭐ Recomendación profesional**

Utiliza siempre:

- `bootstrap.min.css`
- `bootstrap.bundle.min.js`

Mantén el archivo `.map` para depuración (no se enlaza en el HTML).

---

#### 3. Instalación mediante NPM

**📘 Descripción**

Requiere Node.js y permite integrar Bootstrap en flujos de trabajo modernos como Webpack, Vite, Gulp o Parcel. También habilita personalización avanzada mediante SASS.

👉 **Guía oficial para NPM:** https://getbootstrap.com/docs/5.3/getting-started/webpack/

**✔️ Ventajas**

- Personalización completa con SASS
- Optimización y modularización profesional
- Ideal para proyectos escalables

**⚠️ Desventajas**

- Requiere conocimientos avanzados
- Configuración inicial más lenta
- No siempre se puede instalar Node.js en equipos institucionales

---

### 📂 Implementación Práctica en un Proyecto

**Organización de archivos**

1. Crear las carpetas:
   - `css/`
   - `js/`

2. Copiar en `css/`:
   - `bootstrap.min.css`
   - `bootstrap.css.map`

3. Copiar en `js/`:
   - `bootstrap.bundle.min.js`

**🔗 Enlace en el HTML**

```html
<!-- CSS (en el <head>) -->
<link rel="stylesheet" href="css/bootstrap.min.css" />

<!-- JavaScript (antes de </body>) -->
<script src="js/bootstrap.bundle.min.js"></script>
```

Una vez enlazados, las clases de Bootstrap comienzan a aplicarse inmediatamente.

---

### ⚙️ Consideraciones Técnicas Importantes

- ✅ Bootstrap incluye **Reboot**, su propio sistema de normalización de estilos
- ✅ Algunos componentes requieren **Popper**, incluido en `bootstrap.bundle.min.js`
- ✅ El archivo `.map` permite depurar estilos desde el navegador
- ✅ **CDN** = rapidez, pero requiere internet
- ✅ **Archivos locales** = control total y trabajo offline

---

## 📚 Recursos

### Documentación Oficial

- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)

### Herramientas Útiles

- [Bootstrap Builder](https://www.bootstrapbuilder.com/)
- [Template Generator](https://start.getbootstrap.com/)

### Cursos y Tutoriales

- 📺 Tutoriales en video en YouTube
- 📖 Documentación oficial completa
- 🎓 Cursos en plataformas de aprendizaje

---

## 🛠️ Personalización

### Variables de Bootstrap

Puedes personalizar Bootstrap sobrescribiendo variables SASS:

```scss
$primary: #007bff;
$secondary: #6c757d;
$font-family-base: 'Segoe UI', Roboto, sans-serif;
```

### Estilos Personalizados

Añade tus estilos en `css/app.css`:

```css
.mi-clase {
  background-color: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
}
```

---

## 📝 Notas

- Bootstrap utiliza un enfoque **Mobile-First**
- Todos los componentes son responsivos por defecto
- La documentación es tu mejor aliada 📖
- Practica combinando componentes para crear layouts complejos

---

## 📞 Contacto y Soporte

Para preguntas o problemas:

- Consulta la [documentación oficial](https://getbootstrap.com/)
- Busca en Stack Overflow
- Únete a la comunidad de Bootstrap

---

## 📄 Licencia

Bootstrap es de código abierto bajo la licencia MIT. Para más información, consulta el archivo LICENSE.

---

## ⭐ ¡Te gustó este repositorio?

Si este proyecto te ha sido útil y te ha ayudado a aprender Bootstrap, **¡déjanos una estrella!** ⭐

Tu apoyo nos motiva a seguir creando contenido de calidad y mejorando este recurso.

---

_Creado con ❤️ para aprender Bootstrap 5_
