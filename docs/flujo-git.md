# Flujo de trabajo con Git y GitHub

## Ramas

| Rama | Para qué se usa |
|---|---|
| `main` | Versión estable. No se trabaja directamente sobre ella. |
| `docs/bpmn-compunor` | BPMN, historias de usuario, indicadores, flujo de Git, plantilla de PR y README con la declaración de IA. |
| `feature/...` | Código del sistema (etapa de implementación). |

## Mensajes de commit

Formato: `prefijo: descripción corta en infinitivo`.

- `docs:` documentación
- `feat:` funcionalidad nueva
- `fix:` corrección de un error
- `chore:` tareas de mantenimiento

Ejemplos:

```
docs: agrega diagrama BPMN del proceso de venta de CompuNor
docs: describe pools, lanes y compuertas del BPMN
docs: agrega historias de usuario con criterios de aceptación
docs: define indicadores de control y estándares de desempeño
docs: incorpora la declaración de uso de IA al README
```

## Pasos para cada cambio

```
git checkout main
git pull origin main
git checkout -b docs/bpmn-compunor
# ... hacer los cambios ...
git add docs/bpmn-compunor.png docs/bpmn-compunor.svg
git commit -m "docs: agrega diagrama BPMN del proceso de venta de CompuNor"
git push -u origin docs/bpmn-compunor
```

Después se abre el Pull Request hacia `main` en GitHub.

## Pull Requests

1. Se abre el PR desde la rama secundaria hacia `main` con la plantilla de `.github/pull_request_template.md`.
2. Otra persona lo revisa y deja al menos un comentario.
3. Si hay observaciones, se corrigen en la misma rama y se vuelve a pedir la revisión.
4. Con la aprobación, se hace el merge y se borra la rama.
