# Cómo contribuir al sitio de Estudio de Doblaje

Este repositorio es solo la página web de presentación. Si quieres cambiar la app, el código está en otro repositorio; aquí se mejora lo que ve quien visita el sitio.

## Qué se puede mejorar

- Errores de ortografía o de redacción, en cualquiera de los cuatro idiomas (español, inglés, portugués y francés).
- Enlaces rotos, capturas desactualizadas y diferencias entre lo que dice la página y lo que hace la app.
- Accesibilidad, rendimiento y vista en celular.
- Nuevas traducciones de la página.

El contenido de la guía (`guia.pdf`, `guide_en.pdf`) se genera aparte y no se edita aquí.

## Cómo proponer un cambio

1. Abre un *issue* si el cambio es grande, o si no estás seguro de que encaje.
2. Haz un *fork* y crea una rama a partir de `main` con un nombre claro, por ejemplo `fix/enlace-descargas`.
3. Edita `index.html` y revisa el resultado en local (ver el [README](./README.md)), en escritorio y en celular y en cada idioma que toques.
4. Agrega una viñeta al [CHANGELOG](./CHANGELOG.md).
5. Abre el *pull request* con una descripción de qué cambia y una captura si cambia el aspecto.

Cada cambio que llega a `main` se publica solo en el sitio, así que no se integra nada que no se haya visto funcionando.

### Mensajes de *commit*

Usamos [Commits Convencionales](https://www.conventionalcommits.org/es/v1.0.0/): `tipo(ámbito): resumen`. Para este repositorio el ámbito suele ser `web`.

```text
fix(web): corregir el enlace de descarga de Linux
docs(web): actualizar la guía de uso a la 2.8
```

### CHANGELOG

Se escribe en español, con fechas en CST de Ciudad de México (UTC-6). Cada día tiene un bloque `## [AAAA-MM-DD] - Título breve` y cada cambio es una viñeta con tipo (`feat:`, `fix:`, `docs:`…). Agrega la tuya al bloque del día, o crea uno nuevo arriba de los demás, sin reescribir entradas anteriores.

## Lo que no se acepta

- Imágenes, texto o logotipos que no tengas derecho a compartir.
- Capturas con material de clientes (guiones, videos, diálogos): puede estar bajo acuerdo de confidencialidad.
- Código de seguimiento o anuncios de terceros sin acuerdo previo.

## Licencia

Al contribuir aceptas que tu aportación de código se publique bajo la licencia MIT del repositorio (ver [LICENSE](./LICENSE)).
