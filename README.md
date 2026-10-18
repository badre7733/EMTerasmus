# EMT International – Web de proyectos Erasmus+ (multilingüe)

Web estática profesional para los proyectos de movilidad internacional del **Institut Escola Municipal de Treball de Granollers** ([@emtinternational](https://www.instagram.com/emtinternational/)).

## Idiomas disponibles

Selector en la esquina superior derecha. Idioma por defecto: **catalán**.

| Código | Idioma      |
|--------|-------------|
| CA     | Català      |
| ES     | Español     |
| EN     | English     |
| IT     | Italiano    |
| FR     | Français    |
| DE     | Deutsch     |
| PT     | Português   |
| NL     | Nederlands  |
| PL     | Polski      |
| FI     | Suomi       |
| CS     | Čeština     |
| RO     | Română      |

El idioma se guarda en `localStorage` y se detecta automáticamente el del navegador si está disponible.

## Características

- HTML, CSS y JavaScript **puros** (sin frameworks)
- Diseño premium, moderno y responsive
- Secciones: navegación, portada, quiénes somos, galería, horarios, ubicación, documentación y contacto
- Accesibilidad básica + SEO
- Sin formularios falsos ni APIs de pago
- Mapa gratuito OpenStreetMap

## Cómo usar

1. Descomprime el ZIP.
2. Abre `index.html` en el navegador (o con Live Server en VS Code).
3. Cambia de idioma con el selector de la cabecera.
4. Para publicar: sube la carpeta a GitHub Pages, Netlify, Cloudflare Pages, etc.

### Sustituir imágenes

Las fotos actuales son de Unsplash (temporales).  
Reemplázalas por fotografías reales de Instagram:

1. Descarga fotos de [@emtinternational](https://www.instagram.com/emtinternational/) y [@institutemt](https://www.instagram.com/institutemt/).
2. Ponlas en `img/`.
3. Actualiza las rutas `src` en la sección `#galeria` de `index.html`.

## Estructura

```
emt-erasmus-web/
├── index.html
├── css/styles.css
├── js/
│   ├── i18n.js      ← traducciones de los 12 idiomas
│   └── main.js
├── img/
└── README.md
```

## Datos de contacto

- **Dirección:** Carrer Roger de Flor, 66, 08401 Granollers
- **Teléfono:** 93 879 55 18
- **Email:** oficines@iesemt.net
- **Web:** https://institutemt.cat/

---

Creado con HTML/CSS/JS puro · Compatible con VS Code · Sin costes.
