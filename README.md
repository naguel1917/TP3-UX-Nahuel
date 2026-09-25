# Trabajo Práctico: HTML y CSS
**Licenciatura en Sistemas de Información — Diseño UX-UI 2026**

## Ejercicios resueltos
organizados en carpetas separadas (`ejercicio-01` a `ejercicio-20`), cada una con su `index.html` y (cuando corresponde) su `styles.css`.

| Bloque | Ejercicios | Tema |

| 1 - Básico | 1 a 7 | Estructura HTML, listas, tablas, formularios, CSS básico, selectores, box model |
| 2 - Intermedio | 8 a 14 | Flexbox, Grid, pseudo-clases/elementos, posicionamiento, formularios estilizados, variables CSS |
| 3 - Medio/Avanzado | 15 a 20 | Media queries, animaciones, menú hamburguesa sin JS, grid mosaico, formulario multi-step, landing page integradora |

## Decisiones de diseño relevantes
- **Ejercicio 1 y 5**: el Ejercicio 1 se dejó sin CSS a propósito, ya que el Ejercicio 5 consiste en tomar esa misma estructura y aplicarle una hoja de estilos externa.
- **Ejercicio 4 y 13**: mismo criterio; el formulario base del Ejercicio 4 se retoma y estiliza en el Ejercicio 13.
- **Ejercicio 10 y 15**: el layout con Grid del Ejercicio 10 se reutiliza en el Ejercicio 15, agregando media queries y ocultando el sidebar en pantallas chicas (enfoque **desktop first**, ya que se parte de un layout de escritorio existente).
- **Ejercicio 17**: el menú hamburguesa se resolvió sin JavaScript, usando un `<input type="checkbox">` oculto y el selector combinador `~` para mostrar/ocultar la navegación.
- **Ejercicio 19**: la navegación entre pasos se resolvió con el truco de `:target` (anclas con `#paso1` / `#paso2`), y la validación visual usa las pseudo-clases nativas `:valid` / `:invalid`.
- **Ejercicio 20**: proyecto integrador que combina todo lo trabajado: Flexbox (navbar, tarjetas), Grid (sección de servicios), variables CSS, `scroll-behavior: smooth`, un carrusel de testimonios con `scroll-snap`, una animación de aparición (`@keyframes`) y HTML semántico (`<header>`, `<main>`, `<section>`, `<footer>`). El CSS está organizado en secciones comentadas y numeradas para facilitar la lectura.
- En todos los formularios se usaron `<label>` correctamente asociados a cada `<input>` mediante `for`/`id`, y los atributos `required` para aprovechar la validación nativa de HTML5.
- Las imágenes de ejemplo se cargan desde `picsum.photos` (placeholder) y todas incluyen texto alternativo (`alt`) descriptivo.

