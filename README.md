# Distribuidora JAGA — Sitio web (borrador)

Propuesta navegable del sitio de Distribuidora JAGA: móvil primero, con catálogo, carrito, pedido por WhatsApp y flujo de pago en línea simulado.

## Páginas

| Archivo | Página |
| --- | --- |
| `index.html` | Entrada: abre directo el inicio |
| `inicio.html` | Inicio |
| `catalogo.html` | Catálogo con buscador, filtros y ficha de producto |
| `marcas.html` | Marcas afiliadas (transición a los productos de cada marca) |
| `nosotros.html` | Nosotros |
| `contacto.html` | Contacto y preguntas frecuentes |
| `pago.html` | Flujo de pago en línea (simulación) |

`img/` contiene fotos y logos en WebP. Cada página HTML incluye su propio CSS y JavaScript; no requiere instalación ni compilación.

## Ver en local

Abre `index.html` o `inicio.html` en el navegador (las fuentes Saira y Poppins se cargan desde Google Fonts; Crocker va incluida).

## Demostración del pago

- Tarjeta aprobada: `4111 1111 1111 1111` · rechazada: `4000 0000 0000 0002`
- Cualquier fecha futura, CVV `123`, código del banco `123456`
- No se cobra ni se guarda ningún dato.

## Antes de publicar el sitio oficial

- Quitar `<meta name="robots" content="noindex, nofollow">` de las páginas y borrar `robots.txt` y `_headers`.
- Quitar el aviso amarillo "Propuesta de diseño".
- Confirmar la licencia web de la tipografía Crocker.
- Reemplazar productos, precios y testimonios de ejemplo por datos reales.
- Conectar la pasarela de pago y el envío del formulario de contacto.
