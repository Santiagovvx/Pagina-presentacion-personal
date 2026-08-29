# Pagina de presentacion - Santiago Fernandez


## Proposito
Cree esta pagina para mostrar que soy un Ingeniero de Software, cuales son mis atributos y
mis especialidades, como tambien cuales son mis proyectos. cabe recalcar que esto de los
proyectos es inventado para el ejercicio, esta pagina serviria para ojeadores y como 
anclaje en una hoja de vida o asi fue pensado por mi, esta pensada para que la vean
persopnas con lector de pantalla o personas que navegan con el teclado.


## Estructura semántica
Para armar la página no use solo  `<div>` como se hace normalmente,
sino etiquetas que ya le dicen al navegador qué es cada cosa:

- El `<header>` tiene mi nombre y el menú de navegación arriba de todo.
- El `<nav>` es donde van los tres enlaces del menú (Sobre mí,
  Proyectos, Contacto).
- Todo el contenido principal va dentro de un `<main>`.
- Cada bloque grande (Sobre mí, Proyectos, Contacto) es un `<section>`
  distinto, con su propio título.
- Dentro de "Proyectos" usé `<article>` en vez de otro `<section>`,
  porque un proyecto se podría sacar de ahí y compartir solo, tiene
  sentido por sí mismo.
- El bloque de "Disponibilidad" lo puse en un `<aside>` porque es
  información extra, no es parte del contenido principal.
- Y al final, `<footer>` con el copyright.

## Accesibilidad
Intenté que la página también funcionara bien para alguien que use
lector de pantalla o que navegue solo con el teclado (sin mouse):

- La foto tiene un `alt` que describe qué se ve, por si no carga o
  alguien la escucha con un lector de pantalla.
- Cada campo del formulario tiene su `<label>` conectado con el `id`
  del input, así el lector de pantalla dice "Nombre", "Correo", etc.,
  no solo "campo vacío".
- No usé `<div>` con clics para nada interactivo, usé `<a>`,
  `<button>` e `<input>` normales, porque esos ya se pueden navegar
  con la tecla Tab sin que yo tenga que programar nada extra.
- Le puse un borde azul visible cuando algo tiene el foco (cuando
  llegas ahí con Tab), para que se note dónde estás parado.
- Los colores los elegí para que tuvieran buen contraste y se
  pudieran leer bien.
- Validé todo en validator.w3.org y no salió ningún error.

## Cómo ver la página
1. Clona o descarga este repositorio.
2. Abre `index.html` en cualquier navegador.

No requiere instalación ni dependencias de nada, es HTML, CSS y una imagen.