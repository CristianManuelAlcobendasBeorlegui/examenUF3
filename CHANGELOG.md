# ChangeLog
En este fichero se documentan todos los cambios importantes que se han aplicado al proyecto.

## [v1.4]

### Descripción
Realizando otra auditoria con **Lighthouse** se detecta que el porcentaje de accessibilidad es superior al 90% pero no llega al 100%.

El último problema para el análisis se encuentra en la etiqueta `<html>` de la página `problemes.html` la cual no incluye un atributo `lang` indicando el idioma en el que está la página.

### Añade
- Atributo `lang` a la etiqueta `<html>` de la página `problemes.html`.

## [v1.3]

### Descripción
Después de realizar otra prueba con la herramienta **Lighthouse**, el porcentaje de accessibilidad sigue siendo menor al 90%.

El motivo radica en que la página `problemes.html` no incluye una etiqueta `<title>` en su cabecera.

### Añade
- Etiqueta `<title>` a la página `problemes.html`.

## [v1.2]

### Descripción
Volviendo a realizar una auditoria usando la herramienta **Lighhouse**, el procentaje de accesibilidad de la página `problemes.html` sigue estando por debajo del 90%.

La correción que se aplica en esta versión es una mejora en cuanto al contraste de colores que utiliza la web.

### Añade
- Se añade un fichero externo CSS `css/general.css` con los estilos que tendrán todas las webs.

### Modifica
- El contraste de colores entre fondo y el texto de la página `problemes.html`.

### Elimina
- Los estilos indicados en el propio documento de `problemes.html`.

## [v1.1]

### Descripción
Después de hacer una auditoria con la herramienta Lighthouse, el test de Accessiblidad era menor al 90%.

Uno de los motivos era debido a una imagen con un enlace a un recurso que no existe y sin texto alternativo.

### Añadido
- Se añade nueva imagen `img/paisaje-montañas.jpg`.
- Se añade texto descriptivo a la imagen de la página `problemes.html`.

### Correcciones
- Se corrige el enlace existente de la imagen.