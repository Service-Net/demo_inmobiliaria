
# Demo_Inmobiliaria — Landing Page

Landing page estática para inmobiliaria ubicada en Banfield, Zona Sur del Gran Buenos Aires. Desarrollada con HTML5 y CSS3 puro, sin frameworks ni dependencias. Lista para desplegarse en **GitHub Pages**.

---

## 🗂 Estructura del proyecto

```
/
├── index.html               # Página principal (hero)
├── catalogo.html            # Catálogo de propiedades
├── styles.css               # Estilos del index
├── styles_01.css            # Estilos del catálogo
├── fondo_inmobiliaria.png   # Imagen de fondo del hero
└── img/
    ├── propiedad-00.jpg
    ├── propiedad-01.webp
    ├── propiedad-02.jpg
    ├── propiedad-03.jpg
    ├── propiedad-04.webp
    ├── propiedad-05.jpg
    ├── propiedad-06.jpg
    ├── propiedad-07.png
    ├── propiedad-08.jpg
    ├── propiedad-09.jpg
    ├── propiedad-10.jpg
    └── propiedad-11.webp
```

---

## 🚀 Deploy en GitHub Pages

1. Subí todos los archivos al repositorio respetando la estructura de carpetas.
2. Andá a **Settings → Pages**.
3. En *Branch*, seleccioná `main` y carpeta `/ (root)`.
4. Guardá. En unos segundos el sitio queda disponible en:

```
https://<tu-usuario>.github.io/<nombre-del-repo>/
```

> ⚠️ GitHub Pages sirve archivos estáticos. No requiere servidor ni base de datos.

---

## 📱 Responsive

El sitio está diseñado **mobile-first** y funciona en:

| Dispositivo | Breakpoint |
|---|---|
| Móvil pequeño | ≤ 360px |
| Móvil | ≤ 500px |
| Tablet | ≤ 768px |
| Desktop | > 768px |

---

## ✏️ Personalización rápida

| Qué cambiar | Dónde |
|---|---|
| Número de WhatsApp | `index.html` y `catalogo.html` → atributo `href` del `.logo-wsp` |
| Texto del hero | `index.html` → `<h1>` y `<p>` dentro de `.container` |
| Color dorado principal | `styles.css` y `styles_01.css` → variable `#c0a060` |
| Imágenes de propiedades | Reemplazar archivos en `/img/` manteniendo los mismos nombres |
| Logo de WhatsApp | Se carga desde Wikimedia; se puede reemplazar por una imagen local |

---

## 🛠 Tecnologías

- HTML5 semántico
- CSS3 (Grid, Flexbox, clamp(), aspect-ratio)
- Sin JavaScript
- Sin frameworks externos

---

## 📁 Créditos

Desarrollado por **Service-Net**  
© 2026 Inmobiliaria — Todos los derechos reservados
