DYPOINT SERVICIO TÉCNICO DYSON EN MÁLAGA
========================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DyPoint, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Málaga y área metropolitana.

Dominio: https://malagaserviciotecnico.com.es/
Marca: DyPoint Servicio Técnico Dyson en Málaga
Nombre corto (og:site_name): DyPoint – Málaga
Ficha de Google: https://maps.app.goo.gl/bHbRmsLcmMJq6KsP7
Mapa: iframe de Google Maps de la ficha "DyPoint Servicio Técnico Dyson en Malaga" (así figura en Google),
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Málaga y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Málaga, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dypoint.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dypoint-header-hero.css: cabecera grafito con logotipo blanco.
- dypoint.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dypoint_cookie_preference").
- dypoint-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://malagaserviciotecnico.com.es/.

PALETA: azul marino y coral (confianza y seguridad con un toque mediterráneo).
- Primario azul marino #0B2545 · oscuro #081C36 · muy oscuro #051226
- Coral #FF6B57 / #E8553F: logotipo, líneas de sección, números de pasos, botón de cabecera
- Coral de texto #C2412D para las cursivas sobre fondo claro; franja superior #A8321F
- Azul cielo #7FB2E0 en ilustraciones
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
En móvil (≤720px) no se muestran las ilustraciones laterales del hero.
