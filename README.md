# Mi primer proyecto con Git y GitHub

Proyecto HTML introductorio que presenta una página de aprendizaje. La práctica registra dos versiones de la página y su documentación mediante Git y las sincroniza con GitHub.

## Enlaces del proyecto

- **Repositorio Git (HTTPS):** [https://github.com/Rodrigoa2197sv/mi-primer-proyecto.git](https://github.com/Rodrigoa2197sv/mi-primer-proyecto.git)
- **Sitio publicado en GitHub Pages:** [https://rodrigoa2197sv.github.io/mi-primer-proyecto/](https://rodrigoa2197sv.github.io/mi-primer-proyecto/)

## Objetivo de la práctica

Aplicar el flujo básico de control de versiones: crear un repositorio local, revisar cambios, preparar archivos, registrar commits y sincronizar el historial con GitHub. Distinguir el directorio de trabajo, el área de preparación y el repositorio, y documentar el proyecto sin publicar credenciales.

## Tecnologías utilizadas

- **HTML5:** estructura y contenido de la página.
- **Git:** control de versiones local.
- **GitHub:** alojamiento del repositorio remoto y publicación opcional con GitHub Pages.
- **Visual Studio Code:** edición de archivos y terminal integrada.

## Estructura de archivos

La carpeta local de trabajo es `actividad_practica_sesion3`; el repositorio remoto se llama `mi-primer-proyecto`.

```text
actividad_practica_sesion3/
├── index.html
└── README.md
```

La carpeta interna `.git/` guarda el historial y la configuración local del repositorio; Git la administra automáticamente.

## Instrucciones para abrir y ejecutar el proyecto

1. Descarga o clona el [repositorio del proyecto](https://github.com/Rodrigoa2197sv/mi-primer-proyecto) y abre su carpeta en Visual Studio Code.
2. Localiza [index.html](./index.html) en el Explorador de archivos de Windows y haz doble clic, o utiliza «Abrir con» para seleccionar un navegador.
3. Comprueba que aparezcan el encabezado, el párrafo introductorio y la lista de tres temas.
4. Después de editar y guardar el archivo, actualiza el navegador para ver los cambios.

La página es estática: no requiere instalación de paquetes, compilación ni un servidor. Para publicarla con GitHub Pages, se utiliza la opción de despliegue desde una rama, seleccionando `main` y la carpeta `/(root)` en la configuración del repositorio.

## Temas de aprendizaje

- HTML y CSS.
- JavaScript.
- React.

## Datos académicos

- **Autor:** Rodrigo Arévalo.
- **Curso:** Desarrollo en JavaScript.
- **Actividad:** Guía Práctica 3.
- **Año:** 2026.

## Preguntas de comprobación

1. **¿Cuál es la diferencia entre Git y GitHub?**

   Git es un sistema distribuido de control de versiones que registra el historial local de un proyecto. GitHub es una plataforma que aloja repositorios Git remotos y ofrece herramientas de colaboración.

2. **¿Qué diferencia hay entre git add y git commit?**

   `git add` incorpora el contenido actual de los archivos seleccionados al área de preparación. `git commit` registra los cambios preparados como una nueva versión del historial local, con un mensaje y datos de autoría.

3. **¿Por qué el primer commit no aparece automáticamente en GitHub?**

   Porque `git commit` solo registra una versión en el repositorio local. Es necesario configurar un remoto y enviar la rama mediante `git push`, con acceso autorizado a GitHub.

4. **¿Qué hace git push?**

   Envía al repositorio remoto los objetos Git necesarios para publicar los commits locales y solicita actualizar sus referencias de rama. Puede rechazarse si faltan permisos o si la actualización entra en conflicto con el historial remoto.

5. **¿Qué información muestra git status?**

   Muestra la rama actual, los cambios preparados, los cambios sin preparar y los archivos no rastreados. Si hay una rama remota de seguimiento, también informa de la relación con su último estado conocido localmente; no consulta la red por sí solo.

6. **¿Por qué es importante revisar git diff antes de registrar cambios?**

   Permite revisar las modificaciones, detectar errores y evitar incluir contenido accidental o sensible. `git diff` muestra los cambios no preparados de archivos rastreados; `git diff --staged` muestra lo que se incluirá en el próximo commit.

7. **¿Qué riesgos tiene subir contraseñas o tokens al repositorio?**

   Puede permitir accesos no autorizados, exposición de datos y uso indebido de servicios. Un secreto puede permanecer en el historial o en copias del repositorio aunque se borre después; debe revocarse o cambiarse de inmediato si se publica.

8. **¿Para qué sirve el archivo README.md?**

   Es el documento de entrada al proyecto: explica su propósito, tecnologías, estructura, autoría e instrucciones de uso. Su formato Markdown facilita presentar la información en la página principal de GitHub.
