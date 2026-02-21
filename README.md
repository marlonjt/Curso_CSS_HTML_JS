# 📚 Curso HTML, CSS y JavaScript

Repositorio de práctica del curso de **HTML, CSS y JavaScript**, con una sección extendida aplicando **Sass (SCSS)** para escribir estilos más organizados y escalables.

## 🛠️ Stack Tecnológico

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)

## 🧠 Conceptos de Sass Aplicados

- **Variables** — paleta de colores, tipografía y espaciado centralizado
- **Nesting** — selectores anidados siguiendo la jerarquía del HTML
- **Partials y @use** — código organizado por archivos con namespace
- **@extend y %placeholders** — reutilización de estilos sin repetición
- **Pseudo-elementos** — overlay con `&::before`, estados con `&:hover` y `&:focus`

## 🚀 Cómo ejecutar el proyecto Sass

1. Instala Sass
```bash
npm install -g sass
```

2. Entra a la carpeta y compila
```bash
cd LandingPage
sass --watch scss/main.scss:css/main.css
```

3. Abre `index.html` en el navegador