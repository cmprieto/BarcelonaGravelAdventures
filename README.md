# Barcelona Gravel Adventures

## Desarrollo web orientado a las bicicletas de Gravel

## Descripción del proyecto

> > Esta es una web sobre una tienda virtual de bicicletas de gravel ubicada en la ciudad de Barcelona

_Además de vender bicicletas tenemos otras inquietudes como la de generar sinergias con nuestros clientes en salidas ciclistas de fin de semana.
Queremos ser un grupo de amigos con los que compartir salidas por los alrededores de la ciudad y descubrirlos conjuntamente._

## Tecnologías Utilizadas

- HTML: Utilizado para la estructura y contenido de las páginas web.
- CSS: Utilizado para el diseño y estilo de la web.
- Bootstrap. Para el estilizado de algunos componentes.
- SASS: Preprocesador CSS utilizado para mejorar la eficiencia en la escritura de estilos CSS.
- Animaciones: Librerías destinadas a facilitar la creación de las animaciones. Hemos usado _AOS CSS y Animate CSS_.

## Estructura de archivos

```
|- index.html
|- styles/
   |- main.css
   |- main.scsshdp

   |- partials/
        |- reset/
          |- _vars.scss
          |- _mixins.scss
          |- ...
      |- _header.scss
      |- _footer.scss
      |- ...

```

- index.html: Archivo principal que contiene la estructura de la página web.
- styles/main.css: Archivo CSS generado a partir de los estilos SASS.
- styles/main.scss: Archivo principal de estilos SASS que importa todos los demás archivos parciales.
- styles/partials/: Carpeta que contiene archivos parciales de estilos SASS.
- styles/partials/reset/\_vars.scss: Archivo que contiene variables SASS para colores, fuentes, tamaños, etc.
- styles/partials/reset/\_mixins.scss: Archivo que contiene mixins SASS para reutilizar estilos.
- styles/partials/\_header.scss, \_footer.scss, etc.: Archivos que contienen estilos específicos para el encabezado, pie de página, etc.

## Orientación

La web ha sido realizada por Carlos Prieto como proyecto final del bootcamp Desarrollo Web de CoderHouse
