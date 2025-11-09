# PROYECTO FILTRO - Sistema de Panel de Indicadores Kario Media

<img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5 Badge"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3 Badge"/>


## Descripción

Este proyecto fue desarrollado para **Kario Media** como una solución web simple para la gestión de indicadores de rendimiento dentro de la empresa. La idea es que los equipos puedan tener una forma clara de consultar, registrar y eliminar indicadores que estén relacionados con sus proyectos o áreas de trabajo.

Se diseñó como un sistema estático, funcional y con una estructura clara para organizar la información. Todas las vistas están pensadas para ser fáciles de navegar, y los estilos están separados por página para mantener todo ordenado.

---

## Autores

- Sharick Pinto  
- Gustavo Navarro  

---

## Tecnologías Usadas

- **HTML5** para la estructura de las páginas  
- **CSS3** para los estilos y el diseño responsive  
- **Git** como herramienta de control de versiones  
- **Figma** para hacer el diseño inicial de las vistas

---

## Estructura General del Proyecto

A continuación se muestra cómo está organizado el proyecto por carpetas y archivos:

```bash
PROYECTO-FILTRO/
├── index.html              # Página principal
├── pages/
│   ├── inicio.html         # Vista de login
│   ├── usuario.html        # Perfil del usuario
│   ├── panel.html          # Vista del panel de indicadores
│   ├── añadir.html         # Formulario para crear nuevos indicadores
│   ├── borrar.html         # Vista para eliminar indicadores
│   ├── reportar.html       # Generación de reportes
│   └── help.html           # Página de ayuda para el sistema
├── styles/
│   ├── styles.css          # Estilos base del proyecto
│   ├── inicio.css          # Estilos para la vista de login
│   ├── user.css            # Estilos del perfil de usuario
│   ├── panel.css           # Estilos del panel de indicadores
│   ├── añadir.css          # Estilos del formulario de creación
│   ├── borrar.css          # Estilos de la sección de eliminación
│   └── reportar.css        # Estilos de la parte de reportes
├── img/
│   ├── icon.png            # Icono principal
│   ├── karioMediaLogo.png  # Logo de la empresa
│   ├── profilePicture.png  # Imagen de perfil
│   └── [iconos extra]
└── README.md               # Documentación del proyecto
```
___
## Explicación Rápida de las Vistas

- Inicio de sesión (inicio.html): pantalla de acceso al sistema

- Perfil de usuario (usuario.html): muestra la información personal del usuario

- Panel principal (panel.html): donde se ven los indicadores registrados

- Formulario de creación (añadir.html): para ingresar nuevos indicadores

- Sección de eliminación (borrar.html): elimina indicadores ya creados

- Reportes (reportar.html): genera informes a partir de los indicadores

- Ayuda (help.html): incluye una guía básica del uso del sistema

---

## Observaciones

Se optó por separar cada vista en su propio archivo HTML y CSS para que fuera más fácil de modificar o escalar más adelante. Esto también ayuda si se quiere convertir el sistema en una versión dinámica o conectarlo con una base de datos en el futuro.

Todo el código fue estructurado de forma que otros desarrolladores puedan entender fácilmente qué hace cada parte y hacer ajustes si es necesario.

---

## Conclusión 

Este sistema cumple con el objetivo principal de ofrecer una herramienta sencilla para que los equipos de Kario Media gestionen sus indicadores de forma más organizada. Aunque es un sistema estático, su estructura permite avanzar fácilmente hacia versiones más completas si en algún punto se quiere ampliar la funcionalidad.
