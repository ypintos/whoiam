# Bitácora de Yanhi

App de registro nutricional (un solo archivo, sin instalación) para seguir el plan hasta el 29/09.

## Cómo publicarla en GitHub Pages

1. Creá un repositorio nuevo en GitHub (puede ser privado o público).
2. Subí el archivo `index.html` a la raíz del repositorio.
3. Andá a **Settings → Pages**, en "Source" elegí la rama `main` y carpeta `/ (root)`. Guardá.
4. En un par de minutos GitHub te da una URL tipo `https://tu-usuario.github.io/tu-repo/`.
5. Abrí esa URL desde el navegador de tu tablet y agregala a la pantalla de inicio (en Safari/Chrome: menú → "Agregar a pantalla de inicio") para que se abra como una app.

## Cómo funciona el guardado

- Los datos se guardan en el navegador de tu tablet (localStorage), no en la nube: quedan solo en ese dispositivo/navegador.
- Los cambios del día (comidas, período) **no se guardan solos** — tocá el botón "💾 Guardar cambios" al final de la pantalla de Hoy.
- El registro de InBody tiene su propio botón de guardado, separado.
- Si borrás datos del navegador o cambiás de navegador/dispositivo, se pierde el historial — no hay backup automático.

## Notas sobre los valores nutricionales

Los macros de la base de alimentos están alineados a la Tabla de Composición de Alimentos de Uruguay (INDA / Facultad de Química, Proyecto LATINFOODS) y tablas regionales equivalentes. Para productos envasados de marca específica, usá la opción "cargar manual" con los datos de la etiqueta.
