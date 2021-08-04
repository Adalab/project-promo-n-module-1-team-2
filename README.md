# Módulo 1 - Maquetación (proyecto grupal)

Este proyecto está creado sobre el Starter Kit de Adalab. Es el ejercicio del módulo HTML y CSS. Se trata de ejecutar la maquetación de una página web, aplicando diseño responsive y creando la adaptación para móvil, tablet y desktop.

Para realizar este proyecto nos han entregado un diseño a traves del programa Zeplin, nos han dado pautas semanales en los cuales hemos avanzado en cada sprint review (con las actividades programadas con anterioridad) entregando el 95% de los entregables cada semana y cumpliendo con todas las tareas.

## ¿Qué encontrarás?

Esta es una página web en la cual nos damos a conocer como desarrolladoras web de Adalab, destacando nuestra habilidades y demostrando los conocimientos que tenemos en maquetación web, diseño, animaciones y el código.

La página web consta de una landing page con:

- Menú
- Hero (animado)
- Equipo
- Fortalezas y debilidades
- Nosotras
- y Footer
- Además... Una página de contacto, para que trabajemos junt@s

#### Dónde se puede ver

Esta página web tiene un enlace en la web, donde se podrá visitar las veces que quiera.

**El enlace es el siguiente: [The Linkies](http://beta.adalab.es/project-promo-n-module-1-team-2/)**

### Cómo trabajar con este proyecto

> **NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/)

1. Descarga el proyecto en tu equipo e inclúyelo en tu propio repositorio.
2. Instala las dependencias locales ejecutando en la terminal el comando:

```bash
npm install
```

3. Arranca el proyecto ejecutando el siguiente comando:

```bash
npm start
```

Esto tendrás que hacerlo cada vez que te pongas a programar. Después de esto puedes empezar a editar los ficheros dentro de la carpeta `src/`

Los siguientes pasos puedes consultarlos en los vídeotutoriales de **Adalab**:

- [Qué es, trabajar con la versión de desarrollo y rutas relativas](https://www.youtube.com/watch?v=XwvhXvBijos)
- [Migración de un proyecto, trabajar con la versión de producción y GitHub Pages](https://www.youtube.com/watch?v=qqGClcgt9Uc)
- [Motor de plantillas](https://www.youtube.com/watch?v=4GwXOJ045Zg)

### Estructura del proyecto

Esta es la estructura de carpetas:

```
src
 ├── html
 |  ├── partials
 |  ├── contact.html
 |  └── index.html
 |
 ├── images
 |
 ├── scss
    ├── core
    ├── layout
    ├── pages
    └── main.scss
```

- Los ficheros que están sueltos en la raíz del repositorio, como gulpfile.js, package.json... Son la configuración del proyecto y no necesitamos modificarlos.
- La carpeta `src/`: son los ficheros de nuestra página web, como HTML, SASS, en esta carpeta se codeo todos los nuevos ficheros.
- Las carpetas `public/` y `docs/`, que son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

### Tecnologías y recursos utilizados para el proyecto:

- HTML y preprocesador SASS con sintáxis SCSS, usando
  1. Flexbox
  2. Variables
  3. Estilos anidados
  4. BEM
  5. Mixins y mediamixins
  6. CSS grid
  7. Transiciones y animaciones
- Node.js
- Markdown
- Gulp
