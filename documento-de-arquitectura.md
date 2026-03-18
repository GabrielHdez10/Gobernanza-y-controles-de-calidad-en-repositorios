# Documento de Arquitectura

**Autor:** Nombre del Alumno B  
**Fecha:** 18/03/2026  

## Contenido

Este documento describe la organización general del repositorio y el flujo de colaboración usado para controlar la calidad de los cambios antes de integrarlos a la rama principal.

### Estructura del repositorio
- `README.md`: archivo inicial del repositorio.
- `CONTRIBUTING.md`: contiene las reglas del equipo sobre nombres de archivos, estructura de documentos y formato de commits.
- `documento-de-arquitectura.md`: describe la arquitectura básica del repositorio y el flujo de revisión.

### Flujo de trabajo
1. El colaborador crea una rama nueva para trabajar.
2. Los cambios se realizan fuera de la rama `main`.
3. Se hace un commit siguiendo Conventional Commits.
4. Se suben los cambios al repositorio remoto.
5. Se abre un Pull Request.
6. El revisor analiza si el archivo cumple con `CONTRIBUTING.md`.
7. Si hay errores, se hacen correcciones en la misma rama.
8. Cuando el cambio cumple con el estándar, se aprueba.
9. Finalmente, el cambio se integra a `main`.

### Objetivo
El objetivo de este flujo es asegurar que ningún archivo sea integrado al repositorio principal sin pasar por una revisión previa y sin cumplir con los estándares definidos por el equipo.
