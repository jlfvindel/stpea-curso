# STPEA · Soporte Tecnológico a Procesos de Enseñanza y Aprendizaje

Sitio de la asignatura, hecho con [MyST](https://mystmd.org). Se organiza en tres bloques:

1. Gestión de espacios de aprendizaje propios
2. Producción de contenidos y actividades
3. Tutorización de cursos

Los ejemplos del bloque 2 son proyectos independientes (repositorios `stpea-myst-*`), que se publican en la subcarpeta `ejemplos-myst/` de este mismo sitio.

## Ponerlo en marcha

1. Instala [Node.js](https://nodejs.org) (versión 22 o superior) y MyST: `npm install -g mystmd`.
2. Desde esta carpeta: `myst start`, y abre <http://localhost:3000>.

En local, los enlaces a `/ejemplos-myst/…` no llevan a ningún sitio: los ejemplos solo existen en el servidor.

## Publicarlo

```bash
BASE_URL=/ruta/del/sitio myst build --html
```

y se copia el contenido de `_build/html` a la carpeta del servidor. Los ejemplos van en la subcarpeta `ejemplos-myst/` de esa misma carpeta; los enlaces del sitio a `/ejemplos-myst/…` se construyen a partir del mismo `BASE_URL`.

## Licencia

José Luis Fernández Vindel. Contenido bajo licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Preparado con la ayuda de un asistente de inteligencia artificial (Claude, de Anthropic); el autor responde de su contenido.
