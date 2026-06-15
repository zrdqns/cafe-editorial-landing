# Bruma — Landing Café Editorial

Landing page de demostración para **Bruma**, un tostador ficticio de café de especialidad. Diseño editorial tipo revista, cálido y orgánico, con layout asimétrico y animaciones de scroll narrativas.

> **Demo solo-frontend.** No hay backend, tienda, carrito ni API. Productos, precios, fincas y datos de contacto son ficticios. El objetivo es mostrar capacidad visual y de motion.

## Stack

- **Astro** (sitio estático)
- **SCSS / CSS vanilla** (estilos por componente, sin framework de utilidades)
- **GSAP** + **ScrollTrigger** para las animaciones de scroll
- **Lenis** para smooth scroll con inercia

## Diseño

- **Paleta tierra:** crema (`#F4ECE0`), café oscuro (`#3B2A1E`), terracota (`#C2683D`) y oliva como acento.
- **Tipografía:** Fraunces (serif display variable) para titulares + Hanken Grotesk (sans humanista) para cuerpo.
- **Layout:** editorial asimétrico, mucho whitespace, numerales gigantes y secciones a sangre.
- Textura de **film grain** sobre toda la página para sensación de papel.

## Animaciones

- Reveal de titular del hero **línea por línea** (máscara + translate).
- **Parallax** en los paneles ilustrados.
- **Image reveal con clip-path** al entrar en viewport.
- **Smooth scroll** con inercia (Lenis sincronizado con ScrollTrigger).
- **Marquee** de notas de cata.
- Reveals escalonados de bloques y tarjetas.
- Respeta `prefers-reduced-motion`.

## Secciones

Hero editorial a pantalla completa · Historia / origen · Proceso de tueste (4 pasos) · Marquee de notas · Productos destacados · Ubicación · Footer.

Las imágenes son ilustraciones construidas con CSS (gradientes, clip-path y SVG en línea); no se usan fotos reales.

## Desarrollo

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # genera dist/
```
