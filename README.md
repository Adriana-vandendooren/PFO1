# 🧑‍💻 Portafolio Personal — PFO1

## Descripción del Proyecto

Este proyecto corresponde a la **Práctica Formativa Obligatoria N.º 1 (PFO1)** de la materia Desarrollo Web del **IFTS N.º 29**. Consiste en una *Landing Page* de portafolio personal desarrollada únicamente con **HTML5 y CSS3**, sin frameworks ni JavaScript externo. El objetivo es demostrar el dominio de la estructura semántica HTML, el uso de Flexbox y Grid para layouts responsivos, y la aplicación de buenas prácticas de accesibilidad y diseño web.

🔗 **URL publicada (GitHub Pages / Vercel):** `https://tu-usuario.github.io/pfo1-portafolio`

---

## 📁 Estructura del Proyecto

```
pfo1-portafolio/
├── index.html
├── css/
│   └── styles.css
├── img/              
└── README.md
```

---

## ✅ Checklist — Práctica Formativa Obligatoria 1

### 📂 Estructura del Proyecto

- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

---

### 🚀 Repositorio y Publicación

- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages o Vercel.
- [x] En el `README.md` se indica la URL de publicación.

---

### 🔤 Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `<head>` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegiste esa fuente?**

  > Se eligió **Roboto** como tipografía principal por su excelente legibilidad en pantalla a distintos tamaños, su neutralidad que facilita la lectura de bloques de texto, y su amplia gama de pesos que permite jerarquía tipográfica sin usar múltiples familias. Se complementó con **Playfair Display** para los títulos, aportando contraste entre lo moderno (Roboto) y lo elegante (Playfair), lo cual es una técnica clásica de diseño editorial.

---

### 🧱 HTML

- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en `<main>`:**

- [x] Sección `#sobre-mi` con imagen (con atributo `alt`) y párrafo descriptivo.
- [x] Sección `#tarjetas` con al menos 2 tarjetas con imagen y texto.
- [x] Sección `#habilidades` con tabla de tecnologías y hobbies.
- [x] Sección `#contacto` con formulario (Nombre, Apellido, Email, Teléfono, botón submit).
- [x] Sección `#peliculas` con 3 películas (título, imagen, descripción).
- [x] Barra de navegación (`<nav>`) presente y contiene al menos 5 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

---

### 🎨 CSS

- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

**Layout y Organización:**

- [x] Se ha organizado el layout (sección "tarjetas") utilizando **Flexbox**.
- [x] Se ha organizado el layout (sección "películas") utilizando **CSS Grid**.
- [x] **¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?**

  > **Flexbox** resultó ideal para la sección de tarjetas porque permite que los elementos crezcan y se distribuyan proporcionalmente en el espacio disponible, adaptándose automáticamente cuando hay distinto número de ítems. **CSS Grid** fue perfecto para la galería de películas porque necesitaba una cuadrícula con columnas definidas que se ajusten responsivamente con `auto-fit` y `minmax()`. La combinación de ambas técnicas permite un layout robusto sin necesidad de `float` ni hacks del pasado.

**Estilización de Componentes:**

- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`, `clamp()`).
- [x] Se ha implementado al menos una animación o transición.
- [x] **¿Qué animación o transición implementaste y por qué?**

  > Se implementó un **efecto hover en las tarjetas de proyectos**: al pasar el cursor, la tarjeta sube 8px (`translateY(-8px)`), aparece una sombra con tono rojizo del color de acento, el borde cambia al color principal y la imagen se escala sutilmente (`scale(1.04)`). Se eligió esta animación porque genera una retroalimentación visual inmediata que comunica "este elemento es interactivo" sin ser intrusiva. También se aplicaron transiciones en los botones (`translateY` + `box-shadow`) y en los enlaces del footer (subrayado animado con `::after`).

---

### ♿ Consideraciones Adicionales 

- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos (mobile, tablet, desktop).
- [x] Se aplicaron buenas prácticas de accesibilidad: atributos `alt` descriptivos en todas las imágenes, uso de `<nav>` con `aria-label`, estructura semántica correcta (`header`, `main`, `footer`, `section`, `article`).
- [x] Se añadieron comentarios en el HTML describiendo decisiones de diseño y mejoras futuras.

---

*Desarrollado para IFTS N.º 29 · 2025*
