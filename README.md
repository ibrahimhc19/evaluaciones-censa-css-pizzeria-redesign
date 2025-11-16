Aquí tienes un **README.md profesional** adaptado a tu proyecto actual —estático, hecho con **HTML + Sass**, con orientación tanto académica como de portafolio personal—. Está redactado en tono formal y técnico, con secciones estándar para GitHub.

---


# 🍕 Pizzería "Pizza Days" – Rediseño Profesional

Este proyecto es una **reconstrucción moderna** de una evaluación académica realizada en 2023, cuyo objetivo original era desarrollar una página web estática inspirada en sitios reales de pizzerías.  
La nueva versión aplica **buenas prácticas de HTML semántico, arquitectura Sass modular y principios modernos de diseño web responsivo (UI/UX)**.

---

## 🧱 Estructura del Proyecto

```

evaluaciones-censa-css-redesign/
│
├── src/
│   ├── scss/              # Código fuente Sass (dividido por módulos)
│   ├── imagenes/          # Imágenes originales del proyecto
│   ├── js/                # Scripts ligeros (menú, interacciones)
│   └── index.html         # Página principal (HTML semántico)
│
├── dist/
│   ├── css/               # CSS compilado desde Sass
│   └── imagenes/          # Imágenes optimizadas
│
└── README.md

````

---

## 🧩 Tecnologías utilizadas

- **HTML5** – Estructura semántica, accesible y SEO friendly.  
- **Sass (Dart Sass)** – Modularización de estilos mediante partials, variables y mixins.  
- **CSS3 / Flexbox / Grid** – Layouts adaptativos y modernos.  
- **Google Fonts** – Tipografía profesional (`Playfair Display` y `Poppins`).  

---

## 🎨 Diseño y enfoque

El rediseño busca reflejar una **pizzería artesanal moderna**, manteniendo una identidad cálida, minimalista y profesional.

### Paleta de colores
| Uso | Color | Variable Sass |
|------|--------|----------------|
| Fondo principal | `#1E1E1E` | `$color-bg` |
| Primario (marca) | `#B22222` | `$color-primary` |
| Acento cálido | `#FFD7A8` | `$color-accent` |
| Texto principal | `#F5F5F5` | `$color-text` |
| Texto secundario | `#D4D4D4` | `$color-text-muted` |

---

## 🛠️ Compilación de Sass

Este proyecto no utiliza herramientas npm ni bundlers.  
Para compilar Sass manualmente, asegúrate de tener **Dart Sass** instalado globalmente:

```bash
sass src/scss/main.scss dist/css/main.css --watch
````

> Este comando observará los cambios en los archivos `.scss` y generará automáticamente el CSS final en `dist/css/main.css`.

---

## 🚀 Visualización del proyecto

Para ejecutar el proyecto localmente:

1. Abre el archivo `index.html` dentro de la carpeta `src/` o `dist/` directamente en tu navegador.
2. Asegúrate de mantener la estructura de carpetas (`/dist/css/` y `/dist/imagenes/`).
3. El sitio está preparado para despliegue directo en **GitHub Pages** o cualquier servidor estático.

---

## 📐 Objetivos del rediseño

* Reescribir el proyecto aplicando **buenas prácticas modernas** de desarrollo frontend.
* Implementar una **arquitectura Sass escalable y mantenible**.
* Mejorar la **experiencia de usuario (UX)** y la **presentación visual (UI)**.
* Presentar el resultado como parte del **portafolio profesional** del desarrollador.

---

## 👨‍💻 Autor

**Ibrahim Calzadilla Rada**
Desarrollador web full stack
📍 Colombia
[GitHub](https://github.com/ibrahimhc19)

---

## 📄 Licencia

Este proyecto se distribuye con fines educativos y de portafolio personal.
Puede ser utilizado y modificado libremente, dando crédito al autor original.