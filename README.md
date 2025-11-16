# GithubPages
Proyecto de Despliegue con GitHub Pages

Este proyecto es una demostración simple de cómo desplegar una página web estática (index.html) utilizando GitHub Pages, siguiendo un ciclo de vida de desarrollo básico con Git.

Enlace a la web desplegada: [Inserta aquí tu URL de GitHub Pages]

Miembros del Equipo:

[Nombre Miembro 1]

Felipe Jaurena

[Nombre Miembro 3]

[Nombre Miembro 4]

Ciclo de Vida del Desarrollo

A continuación, se detalla el ciclo de vida seguido para este proyecto, tal como se solicita en el enunciado.

1. Planificación

Elección de Temática:
(Escribid aquí por qué elegisteis esta temática. Ejemplo: "Decidimos crear una 'Página de Presentación del Equipo' porque es una idea sencilla, nos permite dividir el trabajo equitativamente (cada uno hace su perfil) y es perfecta para un proyecto estático de una sola página. Cumple el objetivo sin añadir complejidad innecesaria.")

Definición de Usuarios (Personas):

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
(Aquí va vuestra explicación superficial. Ejemplo: "Nuestra aplicación sigue una arquitectura cliente-servidor muy simple.

El Servidor: En este caso, son los servidores de GitHub Pages. Su único trabajo es almacenar nuestros archivos estáticos (index.html, favicon.ico).

El Cliente: Es el navegador web del usuario (Chrome, Firefox, etc.).

El Flujo: Cuando el usuario (cliente) escribe nuestra URL en su navegador, el navegador envía una petición (request) a los servidores de GitHub (servidor). El servidor encuentra nuestro archivo index.html y se lo envía de vuelta (response) al navegador. El navegador entonces lee el HTML y el CSS para 'dibujar' la página que el usuario ve.")

3. Despliegue

Nuestra Experiencia usando GitHub Pages:
(Comentad vuestra experiencia. Ejemplo: "Nuestra experiencia ha sido muy positiva. El proceso de configuración en Settings > Pages fue intuitivo. Lo configuramos para que desplegara la rama main.

Lo más interesante fue ver el flujo de trabajo en acción: trabajábamos en ramas feature/*, las mezclábamos en develop, y no era hasta que hacíamos el merge final de develop a main que la web se actualizaba. El despliegue era automático y tardaba solo uno o dos minutos en reflejar los cambios. Es una herramienta muy potente para desplegar proyectos estáticos de forma gratuita y rápida.")

4. Mantenimiento

Errores Encontrados (y Soluciones):

(Ejemplo 1) Error: Al principio, el favicon.ico no aparecía.

Solución: Nos dimos cuenta de que el navegador lo había guardado en caché. Al borrar la caché (o probar en modo incógnito) vimos que sí funcionaba.

(Ejemplo 2) Error: Conflicto de merge.

Solución: Dos miembros editaron la misma línea en el index.html (por ejemplo, el título) en ramas diferentes. Tuvimos que resolver el conflicto manualmente en el Pull Request antes de poder mezclarlo en develop, eligiendo qué versión queríamos mantener.

Mejoras Futuras:

Añadir estilos CSS más avanzados o mover el CSS a un archivo .css separado.

Hacer que el diseño sea responsive de forma más robusta (aunque el que hemos puesto se adapta bastante bien).

Añadir fotos de perfil para cada miembro.

Añadir más páginas (ej. una página "Proyectos" o "Contacto").