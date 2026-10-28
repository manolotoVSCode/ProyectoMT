# Proyecto Personal MT

Sitio personal de Manuel de la Torre: un catálogo de una sola página con las apps y webs que hace en su tiempo libre, en español e inglés. Cada proyecto tiene una tarjeta y, al tocarla, una ficha con descripción, capturas y enlaces.

Es un solo `index.html` con HTML, CSS y JavaScript, sin dependencias ni paso de compilación. Las capturas están en `img/` y los íconos en `img/icons/`.

## Editar el contenido

Todo el contenido está en dos bloques al inicio del `<script>` de `index.html`:

- `PROFILE`: correo y proyectos (plataformas, capturas, enlaces y textos). El ícono se busca en `img/icons/<id>.png`, salvo que el proyecto indique otro en `icon`.
- `CONTENT`: textos de la interfaz en español (`es`) e inglés (`en`).

Las cifras de arriba y los filtros salen solos de las plataformas de cada proyecto.

## Verlo en local

Abre `index.html` en el navegador.
