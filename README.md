# 🎓 Med. Agüero Luna — Confirmación de asistencia

Formulario web para confirmar asistencia a mi graduación el **13/12/2026** 🩷.

Es una versión en HTML de mi Google Form. Las respuestas se siguen guardando en el Google Form original, así que se ven en la pestaña **Respuestas** o en la planilla de Google Sheets vinculada.

## Qué pregunta

1. **Datos:** nombre y apellido, si vas a asistir y si venís acompañado/a.
2. **Acompañantes:** cuántas personas y sus nombres. Solo aparece si venís acompañado/a.
3. **Alimentación:** restricciones, alergias o necesidades especiales.
4. **Quiz:** ¿sabés quién cumple años ese día? 🪩🧣🏹🗽🌼

Si respondés que no vas a asistir, el formulario se envía directamente.

## Publicarlo con GitHub Pages

1. Subí `index.html` a la raíz del repositorio.
2. Andá a **Settings → Pages**.
3. En **Source**, elegí **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
4. Guardá. A los pocos minutos el formulario va a estar en:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Requisitos del Google Form

Para que las respuestas lleguen:

- El Google Form tiene que estar **publicado**.
- En Configuración, **no tiene que pedir inicio de sesión** ni recolectar correos.
- **No cambies las preguntas ni sus opciones.** Cada pregunta está conectada por un código `entry.XXXX` que está en el bloque `ENTRY` de `index.html`. Si modificás el form, hay que actualizar esos códigos.

## Probarlo

Mandá una respuesta de prueba desde la página publicada y fijate que aparezca en la pestaña **Respuestas** del Google Form.

> La página no puede confirmar si Google recibió la respuesta. Por eso muestra el mensaje de "¡Gracias!" aunque la respuesta no haya llegado. Hacé la prueba antes de compartir el link.

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | El formulario completo (HTML, CSS y JavaScript en un solo archivo) |
| `README.md` | Este archivo |
