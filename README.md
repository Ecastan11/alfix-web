# AL-FIX — Web Corporativa

Web oficial de **AL-FIX Puertas Automáticas y Carpintería**: instalación, reparación y mantenimiento de puertas automáticas de garaje, motorización y carpintería metálica, para particulares y comunidades.

Hecha con HTML, CSS y JavaScript puro (sin frameworks ni dependencias) y publicada gratis con GitHub Pages.

🌐 **Web en vivo:** [ecastan11.github.io/alfix-web](https://ecastan11.github.io/alfix-web/)

---

## Estructura del proyecto

```
alfix-web/
├── index.html                  # Página principal
├── politica-privacidad.html    # Aviso legal, privacidad y cookies
├── assets/
│   ├── css/
│   │   └── styles.css          # Estilos globales (paleta, layout, responsive)
│   ├── js/
│   │   └── main.js             # Menú móvil, formulario, banner de cookies
│   └── img/
│       ├── logo.png            # Logo AL-FIX
│       ├── favicon.png         # Icono de la pestaña del navegador
│       ├── trabajo-1.jpg       # Portfolio: puerta seccional marrón
│       └── trabajo-2.jpg       # Portfolio: puerta seccional antracita
└── README.md
```

---

## Secciones de la web

| Sección | Qué contiene |
|---|---|
| **Portada** | Eslogan, botón de presupuesto y teléfono |
| **Sobre nosotros** | Presentación del negocio, servicios y propuesta de valor |
| **Servicios** | 4 tarjetas: puertas automáticas, automatización, carpintería metálica y mantenimiento |
| **Trabajos** | Fotos de trabajos reales |
| **Reseñas** | 4 reseñas verificadas de Google Maps |
| **Contacto** | Datos, WhatsApp, mapa y formulario de presupuesto |

---

## Paleta de marca

| Color | Hex | Uso |
|---|---|---|
| Azul AL-FIX | `#29ABE2` | Acentos, botones, enlaces |
| Marino | `#3D4A5C` | Textos, fondos, portada |
| Blanco | `#FFFFFF` | Fondo principal |

Tipografía: [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts).

---

## Funcionalidades

- Diseño adaptado a móvil primero (*responsive*)
- Menú desplegable en móvil
- Botón flotante de WhatsApp
- Formulario de presupuesto que abre el correo con el mensaje ya escrito
- Banner de cookies que recuerda la elección del visitante
- Datos estructurados `LocalBusiness` (Schema.org) para salir mejor en búsquedas locales
- Descripción y vista previa optimizadas para Google y redes sociales

---

## Contacto del negocio

📞 [623 353 750](tel:623353750)
✉️ [alfixreparaciones@gmail.com](mailto:alfixreparaciones@gmail.com)
📍 [Ver en Google Maps](https://maps.app.goo.gl/YycMByynhzMeESqc8)

---

## Cómo ver la web en tu ordenador

No hace falta instalar nada: abre `index.html` con doble clic en el navegador.

---

## Cómo añadir fotos de trabajos

1. Guarda la foto en `assets/img/` con el nombre `trabajo-N.jpg` (por ejemplo, `trabajo-3.jpg`).
2. Copia uno de los bloques `<figure>` de la sección `#galeria` en `index.html` y cambia la ruta de la imagen y su texto.
3. Guarda los cambios y súbelos a GitHub (`git add`, `git commit`, `git push`).

---

## Publicación

La web se publica automáticamente con GitHub Pages desde la rama `main`.
Cada vez que subes cambios a `main`, la web se actualiza en 1–2 minutos.
