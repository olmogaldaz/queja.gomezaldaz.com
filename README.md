# queja.gomezaldaz.com — Web de la queja ante el Defensor del Pueblo

Repositorio: `olmogaldaz/queja.gomezaldaz.com`.

## Finalidad

Sitio informativo independiente para la queja ante el Defensor del Pueblo sobre la discriminación de las personas adoptadas y los «bebés robados».

- **Dirección pública:** https://queja.gomezaldaz.com
- **Web principal y documentación:** https://gomezaldaz.com
- **Web de pruebas de la principal:** https://enpruebas.gomezaldaz.com

Este repositorio no sustituye a la web principal ni contiene el servicio de envío de adhesiones.

## Publicación

- Alojamiento: GitHub Pages.
- Rama: `main`.
- Directorio de publicación: raíz del repositorio.
- Archivo `CNAME`: `queja.gomezaldaz.com`.
- Archivo `index.html`: portada pública, con enlaces a los servicios existentes de la web principal.
- Título: «Queja sobre la discriminación de las personas adoptadas y los «bebés robados»».

**Estado actual (8 de noviembre de 2026):** publicada la portada definitiva mediante `index.html`, con tres accesos a las páginas de producción de `gomezaldaz.com`.

## Datos estructurados (Schema.org)

La portada incluye JSON-LD con tres entidades enlazadas por identificadores estables:

- `Person`: Olmo Gómez Aldaz, con el mismo `@id` utilizado por `gomezaldaz.com` (`https://gomezaldaz.com/#person`).
- `WebSite`: el sitio independiente `https://queja.gomezaldaz.com/`.
- `WebPage`: la portada y sus metadatos, incluida su fecha de publicación.

Los datos estructurados se actualizan dentro de `index.html` si cambian el título, la descripción o la fecha de modificación. El sitemap, los enlaces desde la web principal y Search Console quedan pendientes de tratar por separado.

## Separación de responsabilidades

Los formularios actuales de adhesión se encuentran en `gomezaldaz.com` y en su entorno de pruebas. Su servicio de envío está desarrollado en el repositorio `olmogaldaz/adhesiones_mail` y desplegado en Vercel como `adhesionesmail`.

La creación o actualización de esta web informativa no debe modificar los formularios, sus rutas API, los destinatarios del correo ni las configuraciones de DNS y Resend sin una decisión específica.
