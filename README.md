# 💳 Tarjeta de Presentación Personal

Este proyecto fue realizado como parte del **Trabajo Práctico Nº 1** del curso de Desarrollo Full Stack de la UTN.  
El objetivo fue crear una tarjeta de presentación personal utilizando HTML y CSS básico, sin Flexbox ni Grid.

---

## 🧠 ¿Qué incluye la tarjeta?

- ✅ Mi nombre completo
- ✅ Una imagen generada con IA al estilo Studio Ghibli
- ✅ Mi situación actual y estudios
- ✅ Una breve descripción personal
- ✅ Una sección con algunos de mis hobbies

---

## 🛠️ Se utilizaron todas las tecnologías y herramientas solicitadas en la consigna

- HTML básico: `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`, `<img>`, `<div>`
- Estilos con CSS:
  - Fondo de color
  - Color de texto
  - Márgenes y `padding`
  - `border` y `border-radius`
- Git + GitHub para control de versiones y publicación
- Y se cumplieron los desafíos opcionales:
  - Efecto `:hover` en imagen
  - Tipografía externa desde Google Fonts

---

## 🎨 Estilos aplicados

| Elemento        | Estilo Aplicado                                              |
|------------------|---------------------------------------------------------------|
| Fondo principal  | `background-color: goldenrod`                                 |
| Encabezado       | Color de fondo oscuro, texto en color claro, fuente Bebas Neue |
| Títulos (`h2`)   | Fondo claro, bordes redondeados, padding, fuente Josefin Sans |
| Imagen           | Borde azul, borde redondeado, hover con `scale` + `rotate`    |
| Texto            | Márgenes amplios, estructura clara y lectura agradable        |
| Secciones        | Con `div` y color de fondo semitransparente oscuro            |

---

## ✨ Desafíos opcionales cumplidos

- ✅ Fuente personalizada con Google Fonts (`Bebas Neue`, `Josefin Sans`)
- ✅ Efecto `:hover` sobre la imagen (agrandado + rotación suave)

---

## 🧪 Control de versiones con Git

Se trabajó con Git desde terminal:

1. `git init` y primer commit con estructura HTML
2. Segundo commit con estilos base (colores, padding, bordes)
3. Tercer commit con Google Fonts, efectos y contenido final

Repositorio subido a GitHub y publicado mediante GitHub Pages.

---

## 🔧 Requisitos y cómo se implementaron

| Requisito | Implementación en el proyecto |
|-----------|------------------------------|
| **HTML elem. básicos** | `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`, `<img>`, `<div>` presentes en `index.html`. |
| **Fondo de color** | `main { background-color: goldenrod; }`. |
| **Color de texto** | Encabezado claros sobre fondo oscuro (`h1`), texto blanco sobre tarjetas oscuras. |
| **Márgenes y padding** | Márgenes en `section`, `div`; `padding` en texto e imágenes. |
| **border / border-radius** | Imágenes con borde azul de 3 px y `border-radius:10px`. |
| **CSS externo** | Archivo `css/style.css` enlazado. |
| **Sin Flex / Grid** | Layout fluido; centrado con `text-align:center`. |
| **Opcional 1 – Google Fonts** | Fuentes **Bebas Neue** y **Josefin Sans** cargadas vía `@import` y clases utilitarias `.fuentebebas`, `.fuentejosefin`. |
| **Opcional 2 – :hover en imagen** | `.imagen-ghibli:hover { transform: scale(1.2) rotate(5deg); }`. |

---

## 📁 Estructura del proyecto
```
tarjeta-presentacion/
├── index.html
├── css/
│ └── style.css
├── img/
│ └── ChatGPT Image 20 jun 2025, 21_32_36.png
└── README.md
```