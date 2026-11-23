# 💻 Ferretería y Corralón Don Atilio — Catálogo web

## 📖 Descripción

Catálogo web desarrollado para **Ferretería y Corralón Don Atilio**, comercio dedicado a la venta de materiales para la construcción y artículos de ferretería.

El sitio permite a los clientes consultar productos por categoría, con precio y disponibilidad de stock, y contactar al comercio directamente por WhatsApp. Está diseñado con enfoque *mobile-first*, ya que la mayoría de los clientes accede desde el celular.

🔗 **Ver el sitio:** [COMPLETAR LINK DE GITHUB PAGES]

---

## 📢 El problema

Hoy, para saber si hay un producto o cuánto cuesta, el cliente tiene que acercarse al local o llamar por teléfono. Eso implica:

- Consultas repetidas sobre precios y disponibilidad que ocupan tiempo de atención.
- Clientes de la zona rural que se trasladan sin saber si van a encontrar lo que buscan.
- Ninguna vidriera online donde mostrar la variedad de productos y servicios.

## 💡 La solución

Un **catálogo web** (no una tienda online) donde el cliente puede:

- Recorrer los productos por categoría: materiales de construcción, herramientas, pinturas y plomería.
- Ver **precio** y **disponibilidad de stock** de cada producto.
- **Consultar por WhatsApp** con un solo toque, en lugar de comprar por la página.
- Encontrar rápido la ubicación, los horarios y los datos de contacto.

Como la mayoría de los clientes usa el celular, el sitio está pensado **primero para pantallas chicas** (diseño responsive).

---

## Tecnologías

| Herramienta | Uso |
|---|---|
| HTML5 | Estructura semántica (`header`, `nav`, `main`, `section`) |
| CSS3 | Flexbox, Grid, media queries, transiciones |
| JavaScript | Interacciones (menú hamburguesa) — en progreso |
| Google Fonts (Inter) | Tipografía |
| Git + GitHub | Control de versiones con ramas |
| GitHub Pages | Publicación del sitio |

---

## Estado del proyecto

**Hecho**
- [x] Header con logo y navegación
- [x] Sección principal (hero) con foto del local y llamados a la acción
- [x] Grilla de categorías principales
- [x] Diseño responsive para celular
- [x] Botón flotante de WhatsApp

**En curso**
- [ ] Menú hamburguesa para celular

**Próximos pasos**
- [ ] Sección de servicios
- [ ] Productos destacados
- [ ] Ubicación con mapa y footer con horarios y contacto
- [ ] Páginas de cada categoría
- [ ] Catálogo dinámico con precios y stock
- [ ] Mensaje de WhatsApp que incluya el producto consultado
- [ ] Buscador y filtros por categoría

---

## Flujo de trabajo

- `master`: versión publicada en GitHub Pages.
- `develop`: integración de lo terminado antes de publicarlo.
- `feature/*`: una rama por cada funcionalidad (por ejemplo, `feature/menu-hamburguesa`).