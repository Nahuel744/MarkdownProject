# Guía de Contribución

¡Gracias por tu interés en contribuir a este proyecto! Sigue estas pautas para mantener el código limpio, ordenado y fácil de revisar.

## Reporte de Issues

Antes de abrir una nueva *issue*, comprueba que no exista ya una abierta sobre el mismo problema o sugerencia.

- **Para reportar un error (Bug):** Incluye un título descriptivo, los pasos exactos para reproducirlo, el comportamiento esperado y el comportamiento real (adjunta capturas de pantalla o logs si aplica).
- **Para sugerir una mejora:** Explica detalladamente la nueva funcionalidad propuesta y qué problema resuelve.

## Estilo de Código

Para mantener la coherencia y legibilidad en todo el repositorio:

- Utiliza nombres claros y descriptivos (preferiblemente en inglés) para variables, funciones y clases.
- Mantén una indentación uniforme (4 espacios) y evita dejar código comentado o sin usar.
- Añade comentarios únicamente en bloques complejos para explicar el *porqué* de una decisión técnica.
- Verifica que el código funciona correctamente y no rompe funcionalidades existentes antes de subirlo.

## Proceso de Pull Requests (PR)

1. Haz un **Fork** del repositorio y clónalo en tu equipo local.
2. Crea una rama nueva a partir de `main` con un nombre descriptivo (por ejemplo: `feat/nueva-funcion` o `fix/error-login`).
3. Realiza *commits* pequeños y claros que describan el cambio (ej. `docs: añade guía de contribución`).
4. Sube tu rama a GitHub (`git push origin nombre-de-tu-rama`).
5. Abre una **Pull Request** hacia la rama `main`, resume los cambios realizados y referencia la *issue* correspondiente si existe (ej. `Closes #1`).
