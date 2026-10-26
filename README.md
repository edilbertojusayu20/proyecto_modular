# Uliana Mochilas

Sitio web multipágina para presentar un emprendimiento de mochilas artesanales Wayuu. El proyecto está hecho con HTML y CSS básicos.

## Páginas

- `index.html`: presenta el emprendimiento y tiene un enlace al catálogo.
- `catálogo.html`: muestra mochilas, descripciones, precios y medidas.
- `contacto.html`: ofrece enlaces de WhatsApp y correo para consultas.

## Tecnologías

- HTML para organizar el contenido de las páginas.
- CSS para los colores, el texto, la navegación y la presentación de los productos.

El diseño incluye ajustes básicos para distintas pantallas: el menú puede pasar a otra línea y las imágenes del catálogo se reducen para caber en su espacio.

## Archivos del proyecto

```text
mochilas-wayuu/
├── index.html
├── catálogo.html
├── contacto.html
├── styles.css
├── img/
│   ├── mochila1.jpg
│   ├── mochila2.jpg
│   └── mochila3.jpg
└── README.md
```

## Cómo ver el sitio

### Abrirlo en tu ordenador

1. Descarga el repositorio desde GitHub o clónalo en tu computadora.
2. Conserva juntos los archivos `index.html`, `catálogo.html`, `contacto.html`, `styles.css` y la carpeta `img`.
3. Abre `index.html` en un navegador web.

### Publicarlo con GitHub Pages

1. En GitHub, abre el repositorio del proyecto.
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige la rama principal del repositorio —normalmente `main`— y la carpeta `/ (root)`.
5. Pulsa **Save** y espera a que GitHub publique el sitio.
No es necesario instalar programas ni conectarse a Internet para ver las páginas localmente.

## Personalizar el contacto

En `contacto.html`, se debe reemplazar el número de ejemplo del enlace de WhatsApp y la dirección de correo de ejemplo por los datos reales del emprendimiento. El enlace de WhatsApp incluye el código del país y solo números.

## Personalizar el catálogo

Puedes cambiar los nombres, descripciones, precios y medidas dentro de `catálogo.html`. Para usar otras fotografías, guarda las imágenes dentro de `img/` y actualiza el nombre indicado en el atributo `src` de cada etiqueta `<img>`.
