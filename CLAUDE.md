# Estudio de Doblaje · sitio web (CLAUDE.md)

Página de presentación de [Estudio de Doblaje](https://sunkpoet-lang.github.io/estudio-de-doblaje/). Repositorio **público**. Ver `README.md` y `CONTRIBUTING.md`.

## Reglas que no se negocian

- **Nada de material de clientes en capturas ni texto** (guiones, videos, diálogos de proyectos reales del autor): puede estar bajo acuerdo de confidencialidad. Para capturas de la app usar el clip público de *El juego del calamar* o ejemplos inventados — igual que en la guía de uso del núcleo.
- No repitas datos personales de nadie (nombres, correos, chats) en el texto de la página.
- `index.html` es la página completa (HTML/CSS/JS en un solo archivo); `guia.pdf` / `guide_en.pdf` se generan aparte (desde el repo del núcleo) y no se editan aquí a mano.

## Publicación

Se publica con GitHub Pages desde `main`, con `index.html` en la raíz. **Cada cambio que llega a `main` se publica solo** — revisar en local antes de subir (`python3 -m http.server 8000`).

## Licencia

El código de la página (`index.html`) es MIT. Las imágenes, los PDF y el video **no** están cubiertos por esa licencia: son del autor, todos los derechos reservados. Ver `LICENSE`.

## Cómo se integran los PR

Conserva los commits de quien contribuye tal cual (mensaje, autor, `Co-Authored-By`) al integrar — no los resumas ni los traduzcas. Sin `gh` disponible en este entorno: rebasa los commits originales sobre `main` en vez de un *squash* con mensaje propio; si hace falta *squash*, usa el *subject* y *body* originales y agrega las líneas `Co-Authored-By` originales junto a las que correspondan.

Si el cambio no debe disparar nada en los *workflows* de los otros repos del proyecto, no aplica aquí (este repo no tiene *workflows* de Actions), pero por costumbre del proyecto: `[skip ci]` al final del asunto del último commit cuando corresponda.
