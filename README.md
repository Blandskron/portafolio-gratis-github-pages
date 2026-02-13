# Landing Page Gratuita (ATS + Portafolio) — Uso Masivo para Profesionales

Una landing **minimalista, elegante y rápida** creada con **HTML + Tailwind (CDN)** para que cualquier profesional pueda publicar su perfil en minutos: **biografía, sobre mí, estudios, experiencia, proyectos y contacto**, incluyendo **botón flotante de WhatsApp**.

✅ **Uso masivo**: puedes usarla, editarla, duplicarla y compartirla libremente.  
✅ **Sin build**: no requiere Node, Vite, Webpack ni dependencias.  
✅ **Fácil de personalizar**: cambia texto, links, colores y listo.

---

## Demo (Web)
- Demo online: `https://TU-USUARIO.github.io/TU-REPO/`  
- Carpeta principal: `index.html`

> Si no tienes demo aún, publícalo con GitHub Pages (abajo está el paso a paso).

---

## Qué incluye
- `index.html` → Landing completa (secciones: Home, Sobre mí, Estudios, Experiencia, Proyectos, Contacto)
- Botón flotante WhatsApp con ícono SVG “industria”
- Microinteracciones (reveal on scroll, menú móvil, año automático)
- Diseño limpio compatible con portafolio profesional
- **Plantilla PDF** (para uso masivo) *(ver sección Plantilla PDF)*
- **Guion / estructura para video** *(ver sección Video)*

---

## Cómo usar (rápido)
1. Descarga o clona el repo:
   ```bash
   git clone https://github.com/TU-USUARIO/TU-REPO.git
````

2. Abre `index.html` con tu navegador (doble click)
3. Edita lo mínimo:

   * Nombre
   * Biografía
   * Email / teléfono
   * Links de redes
   * Mensaje de WhatsApp

---

## Personalización esencial

### 1) WhatsApp (número y mensaje)

En el bloque JS del final del archivo:

```js
const DATA = {
  whatsappNumber: "+56912345678",
  whatsappMessage: "Hola! Me gustaría conversar contigo."
};
```

### 2) Email / Teléfono / Ubicación

Busca la sección `#contacto` y reemplaza:

* `mailto:contacto@ejemplo.com`
* `tel:+56912345678`
* `Santiago, Chile`

### 3) CV PDF

Reemplaza el link del botón:

```html
<a href="cv.pdf" download>Descargar CV</a>
```

Coloca tu PDF real en la raíz del repo con el nombre `cv.pdf`.

---

## Publicar en GitHub Pages (gratis)

1. Sube el proyecto al repositorio
2. Ve a: **Settings → Pages**
3. En **Build and deployment**:

   * Source: **Deploy from a branch**
   * Branch: **main**
   * Folder: **/(root)**
4. Guarda y abre la URL que te entrega GitHub Pages

---

## Video (explicación)

### Opción A: Link a video (recomendado)

Agrega aquí tu link:

* YouTube: `https://youtube.com/XXXXXXXX`
* TikTok: `https://tiktok.com/@usuario/video/XXXXXXXX`

### Opción B: Guion sugerido (60–90 segundos)

1. “Hola, esta es una landing gratuita para profesionales.”
2. “Incluye biografía, experiencia, estudios, proyectos y contacto.”
3. “Se edita en 5 minutos, no necesita instalación.”
4. “Tiene botón de WhatsApp y es ideal para usar en LinkedIn.”
5. “La puedes publicar gratis con GitHub Pages.”
6. “En el repo viene la plantilla PDF para replicarla en masa.”

---

## Plantilla PDF (uso masivo)

Este repo está pensado para acompañarse con una **plantilla PDF** que puedas entregar a otras personas o usar con clientes/equipos.

✅ Recomendación de estructura del PDF:

* Portada: “Landing Profesional Gratuita”
* Qué es y para qué sirve
* Cómo editar nombre, bio y contacto
* Cómo activar GitHub Pages
* Cómo cambiar foto, redes, WhatsApp
* Checklist final (publicación y validación)

📌 Ruta sugerida dentro del repo:

* `assets/Plantilla-Landing-Gratuita.pdf`

> Si aún no la tienes, crea ese PDF y súbelo a `assets/`.

---

## Estructura del proyecto

```txt
.
├─ index.html
├─ cv.pdf                  # opcional (tu CV real)
└─ assets/
   └─ Plantilla-Landing-Gratuita.pdf
```

---

## Licencia / Uso

Puedes usar esta landing libremente para:

* uso personal
* uso comercial
* uso educativo
* distribución masiva

Sugerencia ética: si la compartes, deja una referencia al repositorio original.

---

## Soporte / Contacto

Si quieres una versión personalizada (colores de marca, secciones extra, multi-idioma, versión React/Next, SEO avanzado):

* Email: [contacto@ejemplo.com](mailto:contacto@ejemplo.com)
* WhatsApp: (configurable en el proyecto)

---

## Créditos

Diseño minimalista, Tailwind CSS (CDN) y tipografías de Google Fonts.

