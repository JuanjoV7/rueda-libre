# Rueda Libre v2.0 · Alquiler de bicicletas en Medellín

Sitio web de **Rueda Libre**, un negocio de alquiler de bicicletas y rutas guiadas en Medellín. Es la versión 2.0, construida con **Bootstrap 5.3.3** sobre el sitio de la semana 1, con identidad de marca propia.

🔗 **Sitio publicado:** https://juanjov7.github.io/rueda-libre/
📁 **Repositorio:** https://github.com/JuanjoV7/rueda-libre

## Páginas
- `index.html`: inicio con portada, promociones, rutas, servicios, flota y beneficios.
- `paginas/tarifas.html`: tarifas de alquiler y recorridos.
- `paginas/reservas.html`: formulario de reservas con validación.
- `pruebas/catalogo-bootstrap.html`: página de pruebas del catálogo con Bootstrap.

## Componentes de Bootstrap usados
- **Navbar colapsable** (`navbar-expand-lg`) en las tres páginas.
- **Grid** (`container > row > col`) con puntos de quiebre para celular, tablet y escritorio.
- **Cards**: flota (7), rutas guiadas (3) y servicios (4).
- **Carrusel** de promociones con controles anterior/siguiente y avance automático.
- **Formulario con validación**: clases `form-*`, `needs-validation`, un mensaje por campo (`invalid-feedback`) y el script de validación de la documentación oficial.
- **Alerta cerrable** que recuerda llevar el documento.
- **Modal** con las políticas de alquiler.
- **Botones** unificados y utilidades de Bootstrap.

## Identidad de marca (personalización)
- Variables `--bs-*` sobrescritas en `css/styles.css`: color primario, fuente, enlaces y radio de bordes.
- Botón principal en **Verde Ruta** y variante propia `btn-naranja` en **Naranja Pedal**.
- Clases propias: `.portada`, `.titulo-seccion` y `.pie-marca`.
- **Bootstrap Icons** en la navbar, los datos de contacto, los beneficios y el enlace de WhatsApp.

## Responsive y accesibilidad
- Probado a 360 px (celular), 768 px (tablet) y 1280 px (escritorio).
- Íconos decorativos con `aria-hidden`; botones solo con ícono con `aria-label`.
- Contraste de texto y fondo revisado (objetivo WCAG AA, 4.5:1) y navegación con teclado.

## Estructura
```
rueda-libre/
├── index.html
├── paginas/
│   ├── tarifas.html
│   └── reservas.html
├── css/
│   └── styles.css
├── img/
├── pruebas/
│   └── catalogo-bootstrap.html
├── bitacora.txt
└── README.md
```

## Tecnologías
- **Bootstrap 5.3.3** (CDN) y **Bootstrap Icons 1.13.1** (CDN): esta entrega.
- HTML5 y CSS3 propio.
- Tipografías Montserrat y Open Sans (Google Fonts).
- Tailwind CSS: aún no aplica en este repositorio.

## Cómo ejecutarlo
Abre `index.html` en el navegador, o usa la extensión Live Server de VS Code.

## Autor
Juan José Viana (GitHub: [JuanjoV7](https://github.com/JuanjoV7))