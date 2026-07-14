# 1INT46 2026-2

Sitio estático del curso interdisciplinario **1INT46 Experimentos de elección en ciencias sociales**, Facultad de Ciencias Sociales PUCP, semestre 2026-2.

## Estructura

- `index.html`: página principal del curso.
- `estilo.css`: hoja de estilos única.
- `assets/`: foto del docente y favicon.
- `bitacora/`: posts individuales y listado cronológico.
- `.gitignore`: exclusiones básicas.

## Actualizar la bitácora

1. Duplica uno de los archivos HTML dentro de `bitacora/`.
2. Cambia el título, la fecha en el atributo `datetime`, los metadatos Open Graph y el contenido del post.
3. Agrega el nuevo post al inicio de la lista en `bitacora/index.html`.
4. Agrega el mismo post al inicio de la sección `Bitácora` en `index.html`.

El orden recomendado es fecha descendente: el post más reciente primero.

## Actualizar contenido del curso

- Cronograma: editar la tabla de la sección `#cronograma` en `index.html`.
- Evaluación: editar la tabla de la sección `#evaluacion`.
- Bibliografía: editar las listas de la sección `#bibliografia`.
- Estilos: ajustar solo `estilo.css`.

## Deploy en GitHub Pages

El sitio no requiere build. Para publicarlo:

1. Crea el repositorio `josemendozas/1int46-2026-2` en GitHub.
2. Sube esta carpeta a la rama `main`.
3. En GitHub, abre `Settings > Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. En `Branch`, selecciona `main` y carpeta `/ (root)`.
6. Guarda la configuración.

La URL esperada será:

```text
https://josemendozas.github.io/1int46-2026-2/
```

## Política de privacidad

El sitio no incluye analytics, cookies ni tracking.
