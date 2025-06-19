# Isavelita

Sitio web para Isavelita, emprendimiento de velas artesanales y piezas decorativas.

## Descripción
Isavelita es una marca dedicada a la creación de velas de soja, velas de molde y piezas decorativas hechas a mano. El sitio web presenta productos destacados, un catálogo completo, testimonios de clientes, información de contacto y enlaces a las redes sociales.

## Características
- **Diseño Responsive:** Totalmente adaptado a dispositivos móviles y de escritorio.
- **Menú Hamburguesa:** Menú de navegación flotante y funcional en vistas móviles.
- **Carrusel de Imágenes:** En la página principal para destacar productos.
- **Componentes Interactivos:** Secciones de productos, galería de Instagram, testimonios y formulario de contacto.
- **Chat de WhatsApp:** Widget flotante para una comunicación directa y rápida.
- **Paleta de Colores:** Tonos cálidos y una tipografía personalizada que reflejan la identidad de la marca.
- **Código Optimizado:** HTML semántico, SASS para un CSS modular y JavaScript para interactividad.

## Estructura del Proyecto
```
Isavelita/
├── index.html
├── pages/
│   ├── acerca.html
│   ├── contacto.html
│   ├── cursos.html
│   ├── mayorista.html
│   └── tienda.html
├── css/
│   ├── style.scss
│   ├── _base.scss
│   ├── _header.scss
│   ├── _products.scss
│   └── (otros parciales de SASS...)
├── media/
│   ├── img/
│   ├── icons/
│   ├── products/
│   └── font/
└── README.md
```

## Instalación y Uso
1. Clona este repositorio:
   ```
   git clone https://github.com/tuusuario/isavelita.git
   ```
2. Abre el archivo `index.html` en tu navegador.
3. Si realizas cambios en los archivos SASS (`.scss`), necesitarás un compilador (como Live Sass Compiler en VSCode) para generar el archivo `style.css`.

## Tecnologías Utilizadas
- **HTML5 Semántico**
- **SASS (CSS3):** Para estilos modulares y organizados. Se utilizan variables, anidación y parciales.
- **Bootstrap 5:** Para el sistema de grid y componentes como el carrusel.
- **JavaScript (ES6):** Para la interactividad del menú hamburguesa y el chat de WhatsApp.

## Buenas Prácticas
- Código bien estructurado y comentado.
- Uso de rutas relativas para portabilidad.
- Imágenes optimizadas en formato `.webp` y con `alt` descriptivo.
- Clases CSS claras y reutilizables bajo la metodología BEM (Bloque, Elemento, Modificador).
- Diseño sin overflow horizontal para una experiencia de usuario fluida.

## Autoría
Desarrollado por Mauricio Bronzi.

---
