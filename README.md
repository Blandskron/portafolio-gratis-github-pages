# Landing Page Gratuita — Template listo para GitHub Pages

Este repositorio incluye una **landing page gratuita** (HTML + Tailwind CDN) lista para desplegar en tu propio GitHub y **darte a conocer** en minutos.

✅ Incluye:
- **Landing page** minimalista con secciones: Home, Sobre mí, Estudios, Experiencia y Contacto  
- **CV modelo** diseñado para pasar filtros **ATS** (formato claro, limpio y escaneable)  
- **Video explicativo** (guía) para modificar el template sin complicarte  

---

## 🚀 Demo (GitHub Pages)
Cuando lo publiques, tu sitio quedará así:

`https://TU_USUARIO.github.io/TU_REPO/`

---

## 📦 Qué trae este repo

Estructura recomendada:

```

/
├─ index.html
├─ img2.jpg
├─ cv.pdf
└─ README.md

````

> Tu template ya viene apuntando a:
- `img2.jpg` (foto)
- `cv.pdf` (CV para descargar)

---

## ✅ Cómo desplegarlo en tu GitHub (GitHub Pages)

1. Crea un repo en GitHub (por ejemplo: `landing-page`)
2. Sube estos archivos:
   - `index.html` (este template)
   - `img2.jpg` (tu foto)
   - `cv.pdf` (tu CV ATS)
3. Ve a: **Settings → Pages**
4. En **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Guarda y abre la URL que te entrega GitHub Pages

Listo: ya tienes tu landing online.

---

## ✏️ Cómo editar el template (rápido)

### 1) Cambiar nombre, título y descripción SEO
En `index.html`, edita:
- `<title>...</title>`
- `<meta name="description" ...>`

### 2) Cambiar foto de perfil
Reemplaza el archivo `img2.jpg` por tu foto (mismo nombre), o cambia el `src` aquí:

```html
<img src="img2.jpg" alt="Foto de perfil" />
````

### 3) Cambiar CV descargable

Reemplaza el archivo `cv.pdf` por tu CV (mismo nombre), o cambia el link:

```html
<a href="cv.pdf" download>Descargar CV</a>
```

### 4) Cambiar WhatsApp (botón flotante)

Edita este bloque al final:

```js
const DATA = {
  whatsappNumber: "+56912345678",
  whatsappMessage: "Hola! Me gustaría conversar contigo."
};
```

### 5) Cambiar correo y teléfono

Busca estas líneas y reemplaza:

* `mailto:contacto@ejemplo.com`
* `tel:+56912345678`

---

## 📄 CV ATS (incluido)

Este repo incluye un **modelo de CV ATS-friendly** para que:

* sea legible por parsers
* mantenga una estructura estándar
* evite columnas raras o diseños que rompan la lectura automática

📌 Recomendación: mantén el CV en PDF con texto real (no escaneado).

---

## 🎥 Video explicativo (cómo modificarlo)

Incluye un video/guía para que puedas:

* cambiar textos
* reemplazar imagen y links
* publicar en GitHub Pages
* personalizar WhatsApp y contacto

**Video:** `Pega aquí tu link`

---

## 🧩 Tecnologías

* HTML (archivo único)
* Tailwind CSS (CDN)
* Google Fonts (Great Vibes, Gilda Display, Montserrat)
* JS Vanilla (menú móvil, reveal on scroll, WhatsApp, año automático)

---

## 📌 Licencia

Libre para usar, modificar y publicar en tu GitHub.

---

## ⭐ Créditos

Hecho para que puedas tener una presencia profesional rápida y limpia:
**Blandskron** — Portafolio / Landing minimalista.
