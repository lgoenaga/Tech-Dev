# Tech&Dev

Bienvenido al proyecto **Tech&Dev**, una tienda virtual de tecnología desarrollada como parte del curso "Introducción a la Programación".

## Estructura del Proyecto

- `index.html`: Página principal de la tienda.
- `components/`
  - `navbar.html`: Barra de navegación reutilizable.
  - `footer.html`: Pie de página reutilizable.
- `css/`
  - `styles.css`: Hojas de estilo principales.
- `images/`
  - `banners/`: Imágenes de banners por categoría.
  - `products/`: Imágenes de productos.

## Características

- Navegación sencilla entre páginas.
- Categorías de productos: Computadoras, Accesorios y Periféricos.
- Diseño modular usando componentes HTML.
- Estilos base para una apariencia uniforme.

## Cómo usar

1. Clona o descarga este repositorio.
2. Abre `index.html` en tu navegador para ver la página principal.
3. Explora las demás páginas y componentes.

## Implementación de Página WEB

Este proyecto utiliza estilos personalizados y puede ser extendido fácilmente con frameworks modernos como Tailwind CSS.

Si deseas experimentar con Tailwind CSS en este proyecto, puedes agregar la siguiente dirección CDN en la sección `<head>` de tu archivo `index.html`:

```html
<!-- Tailwind CSS CDN -->
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

### Pasos

1. Agrega el siguiente script de Tailwind CSS dentro de la etiqueta `<head>` de los archivos `footer.html`, `navbar.html` e `index.html`:

   ```html
   <script src="https://cdn.tailwindcss.com"></script>
   ```

2. Ajusta la etiqueta `<nav>` con la clase `bg-gray-800 text-white p-4`.
   - **Opciones**  
     - `bg-gray-800`: Fondo gris oscuro para el navbar.
     - `text-white`: Texto en color blanco para mejor contraste.
     - `p-4`: Espaciado interno (padding) uniforme.

3. Ajusta el `<div>` principal dentro del navbar con la clase `container mx-auto flex justify-between`.
   - **Opciones**  
     - `container`: Limita el ancho y centra el contenido.
     - `mx-auto`: Centra horizontalmente el contenedor.
     - `flex`: Usa Flexbox para organizar los elementos.
     - `justify-between`: Espacia los elementos al máximo entre sí.

4. Ajusta el enlace principal (`<a>`) con la clase `text-2xl font-bold`.
   - **Opciones**  
     - `text-2xl`: Tamaño de fuente grande para destacar el nombre.
     - `font-bold`: Texto en negrita para mayor énfasis.

5. Ajusta el `<div>` que agrupa los enlaces de navegación con la clase `hidden space-x-6 md:flex div-hover-parent`.
   - **Opciones**  
     - `hidden`: Oculta el div en pantallas pequeñas.
     - `md:flex`: Muestra el div como flex a partir de pantallas medianas.
     - `space-x-6`: Espaciado horizontal entre los enlaces.
     - `div-hover-parent`: Clase personalizada para efectos adicionales.

6. Ajusta el botón para el menú hamburguesa con la clase `md:hidden`.
   - **Opciones**  
     - `md:hidden`: El botón solo se muestra en pantallas pequeñas, permitiendo navegación responsive.

---

Esto ajusta el navbar para que sea visualmente atractivo, funcional y adaptable a diferentes tamaños de pantalla usando utilidades de Tailwind CSS.

## Créditos

Desarrollado para el curso de Introducción a la Programación - CESDE.

---
¡Personaliza este archivo con más información a medida que avances en el proyecto!