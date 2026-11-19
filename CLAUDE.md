# Modelos de páginas web — reglas

Este repositorio guarda páginas de EJEMPLO para mostrarles a clientes que quieren una página web.
Son negocios inventados de San Fernando del Valle de Catamarca. Todos los modelos siguen estas reglas:

## Estructura
- Cada modelo va en su propia carpeta con un solo `index.html` (ej: `/hamburgueseria/index.html`).
- Sin npm, sin build, sin nada que instalar. CSS y JS van dentro del mismo HTML.
- El `index.html` de la raíz muestra todos los modelos en tarjetas con un botón "Ver modelo".
  Cada vez que se agrega un modelo, sumar su tarjeta ahí.

## Rendimiento y diseño
- Primero pensado para celular (mobile-first); que cargue rápido en celulares básicos.
- Imágenes con tamaño reducido (`?w=...&q=...&auto=format`), `loading="lazy"` salvo la del encabezado,
  y un fondo de color de respaldo por si la foto no carga.
- Fotos libres de Unsplash (`images.unsplash.com`).

## Textos
- Español rioplatense, usando "vos" (pedí, elegí, escribinos).
- Precios con formato argentino: `$8.500` (punto de miles, sin decimales).

## Animaciones
- GSAP y Lenis cargados por CDN (versión fija), con animaciones suaves y sutiles.
- Si el celular tiene activado "reducir movimiento" (`prefers-reduced-motion: reduce`): sin animaciones
  y sin cargar GSAP ni Lenis.
- La página tiene que verse completa aunque GSAP o Lenis no carguen.

## Siempre incluir
- Cartelito arriba de todo: "Página de ejemplo — hecha por Joaco".
- Botón de WhatsApp fijo abajo a la derecha, número 3834024275 (`https://wa.me/5493834024275`).
- Sección de opiniones vacía que diga "Próximamente opiniones de clientes". No inventar reseñas.
