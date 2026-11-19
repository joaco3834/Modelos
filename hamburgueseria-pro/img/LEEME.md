# Imágenes recortadas (sin fondo)

Fotos de Unsplash recortadas con rembg (modelo `birefnet-general-lite`) y pasadas a WebP de 800 px:

| Archivo              | Hamburguesa    | Foto original                                   |
|----------------------|----------------|-------------------------------------------------|
| `clasica.webp`       | Clásica Fuego  | `stanley-kustamin-egC8A3EWFms-unsplash.jpg`     |
| `doble-cheddar.webp` | Doble Cheddar  | `amirali-mirhashemian-sc5sTPMrVfk-unsplash.jpg` |
| `criolla.webp`       | Criolla        | `ghaly-wedinly-Md54Ida-hiI-unsplash.jpg`        |
| `bacon.webp`         | Bacon Bomb     | `david-foodphototasty-E94j3rMcxlw-unsplash.jpg` |

Las `.jpg` originales no las carga la página; se pueden borrar para que el repositorio pese menos.

## Ingredientes flotantes

Recortados por color (verde, amarillo, rojo) de las mismas fotos:

| Archivo               | De dónde sale                              |
|-----------------------|--------------------------------------------|
| `ing-lechuga.webp`    | hoja de arriba, foto de David Foodphototasty |
| `ing-lechuga2.webp`   | hoja de abajo, misma foto                  |
| `ing-panceta.webp`    | tira enrulada de la derecha, misma foto    |
| `ing-queso.webp`      | feta que cae, foto de Stanley Kustamin     |
| `ing-sesamo1/2.webp`  | semillas de la tapa del pan                |

Falta una rodaja de tomate: en estas fotos el tomate solo se ve de costado. Si se agrega
`ing-tomate.webp`, se suma en la lista `ing` de cada burger en `../index.html`.
