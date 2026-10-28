## Flujo de Trabajo y Ramas 

* **main:** Código estable listo para producción.
* **QA:** Rama de integración y pruebas. Todo el trabajo del equipo se une aquí primero.

## Reglas para Pull Requests (PR)

1. Nunca hacer commits directos a `main` ni a `QA`.
2. Todo desarrollo debe hacerse en una rama nueva que incluya el ID de Jira (Ejemplo: `feature/SCRUM-7-RF-01`).
3. Al terminar, abrir un Pull Request (PR) apuntando hacia la rama **`QA`**.
4. El PR debe ser revisado y aprobado por el Líder de Integración antes de hacer merge.
5. El código debe compilar correctamente y no tener errores para ser aceptado.