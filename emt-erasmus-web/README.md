# EMT International – Web de proyectos Erasmus+

Web estática profesional para los proyectos de movilidad internacional del **Institut Escola Municipal de Treball de Granollers** (cuenta Instagram [@emtinternational](https://www.instagram.com/emtinternational/)).

## Características

- HTML, CSS y JavaScript **puros** (sin frameworks ni dependencias)
- Diseño premium, moderno y responsive (móvil, tablet y escritorio)
- Secciones: navegación, portada, quiénes somos, galería, horarios, ubicación, documentación (placeholder) y contacto
- Buenas prácticas de accesibilidad (skip-link, ARIA, contraste, teclado)
- SEO básico (meta description, Open Graph, canonical, títulos semánticos)
- Sin formularios falsos de envío
- Sin claves API ni servicios de pago
- Mapa embebido gratuito con OpenStreetMap
- Tipografía legible (Inter + Playfair Display vía Google Fonts)

## Cómo usar

1. Descomprime el ZIP.
2. Abre `index.html` en el navegador (doble clic o con Live Server en VS Code).
3. Para publicar: sube la carpeta completa a cualquier hosting estático gratuito (GitHub Pages, Netlify, Cloudflare Pages, etc.).

### Sustituir imágenes de la galería

Las imágenes actuales son de Unsplash (temporales y de alta calidad).  
**Debes reemplazarlas** por fotografías reales de los posts de Instagram:

1. Entra en [https://www.instagram.com/emtinternational/](https://www.instagram.com/emtinternational/) y en [@institutemt](https://www.instagram.com/institutemt/).
2. Descarga las fotos que quieras mostrar.
3. Colócalas en la carpeta `img/` (por ejemplo `img/erasmus-italia.jpg`).
4. En `index.html`, cambia las rutas `src` de las etiquetas `<img>` de la sección `#galeria`.

Ejemplo:

```html
<img src="img/erasmus-italia.jpg" alt="Estudiantes en intercambio en Italia" loading="lazy" width="800" height="600">
```

## Estructura de archivos

```
emt-erasmus-web/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos
├── js/
│   └── main.js         # Interacciones (menú, scroll, año)
├── img/                # Aquí las fotos reales de Instagram
└── README.md           # Este archivo
```

## Datos de contacto del centro (verificados)

- **Dirección:** Carrer Roger de Flor, 66, 08401 Granollers (Barcelona)
- **Teléfono:** 93 879 55 18
- **Email:** oficines@iesemt.net
- **Web oficial:** https://institutemt.cat/
- **Horario oficinas:** L-V 10:00–12:00 · L-J 14:30–16:30

## Personalización rápida

- Colores: edita las variables CSS en `:root` de `styles.css`.
- Textos: edita directamente `index.html`.
- Añadir más proyectos: copia un bloque `.gallery__item` y pega más fotos.

## Licencia y uso

Contenido preparado para uso educativo e informativo del Institut EMT.  
Las imágenes de Unsplash tienen licencia propia; sustitúyelas por material propio o autorizado del centro.

---

Creado con HTML/CSS/JS puro · Compatible con Visual Studio Code · Sin costes.
