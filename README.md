# J.P.F Solutions - sitio web editable

Sitio web estático para abrir en VS Code y publicar en GitHub Pages o Netlify.

## Archivos
- `index.html`: textos, secciones, paquetes, precios y formulario.
- `styles.css`: colores, diseño adaptable a móvil, animaciones y chatbot visual.
- `script.js`: menú, formulario de WhatsApp y chatbot automático.
- `assets/logo-jpf.jpeg`: logo incluido.

## Antes de publicar
1. Abre `script.js`.
2. Busca `whatsappNumber: "573000000000"`.
3. Sustitúyelo por el WhatsApp real de la empresa: `57` + número, sin `+`, espacios ni guiones. Ejemplo de formato: `573XXXXXXXXX`.
4. Revisa precios, promociones, cobertura y condiciones.
5. Si no tienen todavía WhatsApp empresarial, puedes dejar el marcador mientras pruebas, pero no publiques el sitio como si el contacto ya funcionara.

## Probar en VS Code
- Descomprime el ZIP.
- Abre la carpeta `JPF_Solutions_Web` en VS Code.
- Instala la extensión **Live Server** (opcional).
- Clic derecho en `index.html` > **Open with Live Server**. También puedes abrir `index.html` directamente en el navegador.

## Publicar gratis en GitHub Pages
1. Crea/inicia sesión en https://github.com/
2. Pulsa **New repository**. Nombre sugerido: `jpf-solutions`.
3. Déjalo en **Public** si quieres usar GitHub Pages gratis con configuración sencilla.
4. En el repositorio, pulsa **Add file > Upload files**.
5. Sube los archivos y carpetas que están DENTRO de `JPF_Solutions_Web` (index.html, styles.css, script.js y assets). No subas solamente el ZIP.
6. Pulsa **Commit changes**.
7. Ve a **Settings > Pages**.
8. En **Build and deployment**, selecciona **Deploy from a branch**.
9. Selecciona la rama `main` y la carpeta `/ (root)`, luego **Save**.
10. Espera un momento y vuelve a **Settings > Pages**. Allí aparecerá el enlace público.

## Precios y descuentos
Los valores incluidos son precios iniciales sugeridos en COP, contrastados con tarifas públicas de servicios técnicos en Bogotá consultadas en octubre de 2026. No constituyen una cotización garantizada. Ajusta según costos, dificultad, transporte, repuestos y garantía real. Las promociones muestran el precio de referencia tachado; no afirmes que el precio anterior fue cobrado realmente si no lo fue. Las piezas y licencias se cotizan por separado.

## Importante
- El chatbot es una guía automática local, no usa inteligencia artificial ni un servidor.
- El formulario abre WhatsApp con el mensaje preparado; no guarda formularios en una base de datos.
- No incluyas testimonios falsos, sellos de certificación no obtenidos ni promesas de recuperación de datos.
- Revisa política de tratamiento de datos y condiciones de servicio antes de operar comercialmente.


## Funciones de la versión tienda virtual
- Catálogo de servicios con cesta y cantidades.
- Calculadora de presupuesto por servicio y cantidad de equipos.
- Solicitud de la cesta por WhatsApp al 313 849 4570.
- Selector de tema claro/oscuro y controles para ajustar el tamaño del texto.
- Sección de presentación de los tres propietarios.

Nota: la cesta es local en el navegador y no procesa pagos ni guarda pedidos en un servidor. La solicitud se envía a WhatsApp para confirmar disponibilidad y precio final.
