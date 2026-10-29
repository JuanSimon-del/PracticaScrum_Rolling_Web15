# Workshop Rolling Code School

Landing page del workshop **“¿Por dónde empiezo a programar?”**, desarrollada en equipo como práctica de maquetación web y metodología Scrum.

El proyecto presenta el evento, sus speakers, la agenda y los sponsors. También incluye las opciones de entrada, una compra de demostración, un formulario para empresas interesadas en participar como sponsors y la ubicación del encuentro.

[Ver la landing publicada](https://webentradasrolling.vercel.app/)

## Objetivo

Construir una página basada en los mockups y requisitos proporcionados por el Product Owner, manteniendo una identidad visual consistente y una navegación adaptable a distintos tamaños de pantalla.

La implementación utiliza HTML y CSS, con Bootstrap como apoyo para la grilla y los componentes visuales. Las interacciones propias del proyecto no requieren JavaScript.

## Tecnologías y recursos

- **HTML5:** estructura de las páginas, enlaces, formularios y validaciones nativas.
- **CSS3:** estilos propios, variables de color, media queries, transiciones y carrusel mediante desplazamiento horizontal.
- **Bootstrap 5.3.8:** grilla adaptable y utilidades de presentación, cargadas por CDN.
- **Bootstrap Icons:** iconos de interfaz.
- **Plus Jakarta Sans:** tipografía cargada desde Google Fonts.
- **Git y GitHub:** control de versiones, ramas y revisión mediante pull requests.
- **Trello:** organización de historias de usuario y seguimiento del Sprint.
- **Vercel:** publicación de la landing.

## Secciones

### Presentación del evento

Información del workshop, fecha, horario, modalidades y accesos a la agenda y a la selección de entradas.

### Speakers

Diez tarjetas con fotografía, nombre, título de la charla y descripción. En celular, el contenido se recorre mediante un carrusel manual construido con CSS; en pantallas más amplias se presenta en una grilla.

### Agenda

Cronograma de acreditación, charlas y cierre con preguntas y networking.

### Sponsors

Empresas organizadas en los niveles Diamante, Oro y Bronce, con logos y tarjetas de distinta jerarquía visual.

### Entradas y finalizar compra

Opciones Early Bird, General y Virtual, selección de una entrada, campo de cantidad y resumen de ejemplo. El enlace “Continuar” abre un modal con datos del asistente y campos de pago de demostración.

### Sumate como sponsor

Formulario con nombre, apellido, empresa, email, nivel de sponsoreo, logo opcional y mensaje opcional. Está ubicado antes de “Cómo llegar”.

### Cómo llegar

Dirección del evento, mapa incrustado con tratamiento visual oscuro y enlace para consultar la ubicación en Bing Maps.

### Página 404

Página temática de una entrada rota, con accesos para volver al inicio y consultar las charlas. El fondo del ticket es una imagen decorativa; los textos y enlaces forman parte del HTML.

## Estructura del repositorio

```text
PracticaScrum_Rolling_Web15/
├── README.md
└── landing-workshop/
    ├── index.html
    ├── 404.html
    ├── css/
    │   ├── styles.css
    │   └── style404.css
    └── img/
        ├── iconos/
        ├── speakers/
        ├── sponsors/
        └── ticket-roto.png
```

## Cómo abrir el proyecto

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/JuanSimon-del/PracticaScrum_Rolling_Web15.git
   ```

2. Abrir la carpeta del proyecto en el editor.
3. Abrir `landing-workshop/index.html` en el navegador o usar Live Server desde el editor.
4. Para consultar el diseño del error, abrir `landing-workshop/404.html`.

No es necesario instalar paquetes ni ejecutar un proceso de compilación. Se necesita conexión a Internet para cargar las fuentes, Bootstrap, Bootstrap Icons y el mapa externo.

## Trabajo en equipo

El equipo organiza los requisitos en historias de usuario con criterios de aceptación y utiliza Trello para seguir su avance.

Cada tarea se desarrolla en una rama propia. Los cambios se revisan mediante pull requests hacia `dev`, la rama de integración del equipo. Antes de integrar una entrega se revisan las diferencias y se resuelven los conflictos conservando las funcionalidades existentes.

## Comprobaciones antes de una entrega

- Revisar la página en celular, tablet y escritorio.
- Confirmar que no haya textos cortados ni desplazamiento horizontal de toda la página.
- Recorrer las diez tarjetas del carrusel móvil de Speakers.
- Comprobar la carga de fotografías, logos e iconos.
- Verificar los enlaces de navegación y los accesos a Finalizar compra.
- Abrir y cerrar los modales y probar los formularios vacíos, con formatos incorrectos y con datos ficticios válidos.
- Comprobar que el mapa y su enlace externo correspondan a la dirección del evento.
- Revisar los accesos de regreso desde la página 404.
- Confirmar que la versión publicada incluya los últimos cambios aprobados.

## Créditos

Proyecto realizado por el equipo de **Rolling Web 15** como práctica de metodología Scrum en Rolling Code School.

Los mockups y requisitos fueron proporcionados durante el curso. Las marcas y logos pertenecen a sus respectivos titulares y se utilizan como parte de la maqueta educativa; su presencia no acredita un patrocinio real.

La maquetación, la integración de recursos y los ajustes del sitio se trabajaron en equipo con acompañamiento y revisión.
