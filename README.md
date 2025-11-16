# GithubPages
Proyecto de Despliegue con GitHub Pages

Este proyecto es una demostración simple de cómo desplegar una página web estática (index.html) utilizando GitHub Pages, siguiendo un ciclo de vida de desarrollo básico con Git.

Enlace a la web desplegada: (https://github.com/TheBoss-01/Github-Pages.git)

Miembros del Equipo:

TheBoss-01

Felipe Jaurena

Sergio Gamero Julià

prmarango-afk

Ciclo de Vida del Desarrollo

A continuación, se detalla el ciclo de vida seguido para este proyecto, tal como se solicita en el enunciado.

1. Planificación

Elección de Temática:
Decidimos crear una 'Página de Presentación del Equipo' porque es una idea sencilla, nos permite dividir el trabajo equitativamente (cada uno hace su perfil) y es perfecta para un proyecto estático de una sola página. Cumple el objetivo sin añadir complejidad innecesaria.

Definición de Usuarios:

Usuario 1: El Profesor/Corrector:

Objetivo: Quiere verificar rápidamente que hemos cumplido todos los requisitos técnicos (despliegue, merges, favicon, index) y leer nuestra documentación (este README).

Necesidad: Enlaces claros y una web funcional.

Usuario 2: Un Compañero de Clase:

Objetivo: Quiere ver quiénes somos y qué hemos hecho.

Necesidad: Una página visualmente clara y fácil de leer.

Requisitos de la Aplicación:

R1 (Funcional): La página web debe mostrar el nombre y una breve descripción de cada uno de los 4 miembros del equipo.

R2 (Funcional): Cada perfil de miembro debe incluir un enlace funcional a su perfil personal de GitHub.

R3 (Técnico): La página debe cargarse correctamente cuando se accede a través de la URL de GitHub Pages y debe mostrar un icono (favicon) en la pestaña del navegador.

2. Diseño

Arquitectura Cliente-Servidor:
Nuestra aplicación sigue una arquitectura cliente-servidor muy simple.

El Servidor: En este caso, son los servidores de GitHub Pages. Su único trabajo es almacenar nuestros archivos (index.html, favicon.ico).

El Cliente: Es el navegador web del usuario (Chrome, Firefox, etc.).

El Flujo: Cuando el usuario (cliente) escribe nuestra URL en su navegador, el navegador envía una petición (request) a los servidores de GitHub (servidor). El servidor encuentra nuestro archivo index.html y se lo envía de vuelta (response) al navegador. El navegador entonces lee el HTML y el CSS para 'dibujar' la página que el usuario ve.

3. Despliegue

Nuestra Experiencia usando GitHub Pages:
Nuestra experiencia ha sido muy negativa ya que al ser nuevos en GitHub hemos hecho muchos errores sin darnos cuenta. Se puede observar nuestra frustación en los comentarios al hacer merge.

4. Mantenimiento

Errores Encontrados (y Soluciones):

Error: Al principio, trabajabamos todos desde "main".

Solución: Creamos un rama llamada "desarrollo" y desde ahi haciamos cad uno una branch.

Error: Conflicto de merge.

Solución: Dos miembros editaron la misma línea en el index.html en ramas diferentes. Tuvimos que resolver el conflicto manualmente en el Pull Request antes de poder mezclarlo en develop, eligiendo qué versión queríamos mantener.

Error: Conflicto de tirar de la "main" en vez de "desarrollo".

Solución: Cada vez que se crea una branch o pull requeste hay que fijarse muy bien desde donde lon haces.

Mejoras Futuras:

Hacer que el diseño sea responsive de forma más robusta (aunque el que hemos puesto se adapta bastante bien).

Añadir fotos de perfil para cada miembro.

Añadir más páginas (ej. una página "Proyectos" o "Contacto").
