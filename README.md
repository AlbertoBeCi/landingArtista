```
 __  __                     _
|  \/  | __ _ _ __ ___ ___| | ___
| |\/| |/ _` | '__/ __/ _ \ |/ _ \
| |  | | (_| | | | (_|  __/ | (_) |
|_|  |_|\__,_|_|  \___\___|_|\___/

   Guitarrista · Vocalista · Folk
```

# Landing de Marcelo

Landing page de Marcelo, guitarrista y vocalista especializado en música folk, con 18 años de trayectoria.

## Secciones

- **Bienvenida** — Hero con nombre, subtítulo, imagen de fondo (`heroSection.png`) y botón hacia "Sobre mí".
- **Sobre mí** — Biografía breve y tarjetas con datos rápidos (años de experiencia, instrumentos, género/estilo y formación).
- **Trayectoria** — Tarjetas con los festivales en los que se ha presentado (Festival Xàbia Folk, Folk Segovia, Poborina Folk).
- **Próximas presentaciones** — Texto de próximos eventos y un reproductor de audio (`demo.mp3`) para escuchar una muestra.
- **Footer** — Iconos de redes sociales (Instagram, Facebook, YouTube) y aviso de derechos.

## Estructura

- `Index.html` — Estructura de la página, siguiendo la metodología [BEM](http://getbem.com/) para las clases. Incluye metadatos SEO (meta description, Open Graph, Twitter Card) y datos estructurados (JSON-LD `Person`) para motores de búsqueda y generativos.
- `style.css` — Estilos, con variables CSS para la paleta de colores y las fuentes, layout en grid para las tarjetas, y diseño responsive (1 columna en móvil, varias desde 768px).

## Paleta de colores

| Uso          | Variable                 | Color       |
|--------------|--------------------------|-------------|
| Fondo        | `--color-fondo`          | `#F5EFE6`   |
| Principal    | `--color-principal`      | `#8B5E3C`   |
| Acento       | `--color-acento`         | `#D9A441`   |
| Texto        | `--color-texto`          | `#2E2018`   |
| Texto claro  | `--color-texto-claro`    | `#FAF6F0`   |

## Tipografías

| Uso      | Variable             | Fuente                        |
|----------|----------------------|--------------------------------|
| Títulos  | `--fuente-titulos`   | `Playfair Display` (serif)     |
| Texto    | `--fuente-texto`     | `Nunito Sans` (sans-serif)     |

## Dependencias externas

- [Google Fonts](https://fonts.google.com/) — Playfair Display y Nunito Sans.
- [Font Awesome](https://fontawesome.com/) (vía CDN) — iconos de redes sociales.

## Cómo correrlo

```bash
$ pip3 install flask && python3 server.py
```

Luego abre la URL que indique la consola para ver la landing.
