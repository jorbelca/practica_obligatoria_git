# Introducción a Git y la metodología Git Flow

## ¿Qué es Git?

**Git** es un sistema de control de versiones distribuido que permite a los desarrolladores gestionar y controlar los cambios en el código fuente a lo largo del tiempo. Con Git, podemos trabajar de manera colaborativa en un proyecto sin preocuparnos de sobrescribir los cambios de otras personas, ya que cada desarrollador trabaja en su propia copia del repositorio.

Las características principales de Git incluyen:

- **Historial de versiones**: permite guardar el estado del proyecto en varios momentos, facilitando volver a versiones anteriores.
- **Trabajo en ramas**: permite trabajar en diferentes funcionalidades o partes de un proyecto de manera independiente, fusionando los cambios cuando estén listos.
- **Distribuido**: cada usuario tiene una copia completa del repositorio, lo que permite trabajar de manera descentralizada.

## Git Flow

**Git Flow** es una metodología o flujo de trabajo para gestionar las ramas en Git, especialmente útil en proyectos con equipos de desarrollo grandes o con múltiples versiones en desarrollo simultáneamente. Está diseñado para hacer que el ciclo de desarrollo sea más organizado y eficiente.

### Las ramas principales en Git Flow:

- **master**: contiene el código que siempre está listo para producción.
- **develop**: es la rama donde se desarrolla el código y se prepara para su integración final.

A partir de estas ramas principales, se crean otras ramas paralelas según el flujo de trabajo:

- **Feature branches**: se crean desde `develop` para añadir nuevas funcionalidades.
- **Release branches**: se crean para preparar una nueva versión del proyecto, desde `develop` hacia `master`. Incluyen la creación de una etiqueta (tag).
- **Hotfix branches**: se crean desde `master` para corregir errores en producción de manera rápida y luego se fusionan con `master` y `develop`. Incluyen la creación de una etiqueta (tag).

## ¿Por qué utilizamos Git Flow?

Git Flow facilita el mantenimiento de un proyecto con diferentes versiones en desarrollo y permite gestionar fácilmente cambios críticos, como correcciones de errores urgentes, sin interrumpir el flujo de desarrollo normal.

Los beneficios de Git Flow incluyen:

- **Organización**: ayuda a mantener el código bien estructurado con un flujo de desarrollo claro.
- **Colaboración**: permite a los equipos trabajar en múltiples funcionalidades al mismo tiempo sin conflictos.
- **Control de versiones**: asegura que las versiones estén bien definidas y listas para producción.

Esta metodología es especialmente útil en equipos de desarrollo de software que necesitan gestionar múltiples entornos, como desarrollo, pruebas y producción.

# Proyecto de Git Flow, proceso
