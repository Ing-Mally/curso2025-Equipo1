# Curso 2025 - Equipo 1
Repositorio del equipo para prácticas de Git y flujo de trabajo.
Flujo elegido: GitHub Flow
- main protegido (solo merges por PR).
- ramas: feature/<tema>
- proceso: crear rama → commit/push → PR → review → merge (squash).

 ### Nombres de ramas 
-   **Features nuevas:** `feature/<tema-kebab-case>`
    
    -   Ej: `feature/api-health-endpoint`, `feature/ui-login-form`
        
-   **Bugs urgentes en producción:** `hotfix/<bug-descriptivo>`
    
    -   Ej: `hotfix/fix-nullref-on-auth`
### Convención de commits (Conventional Commits + ejemplos)
**Formato:**
```
<type>(<scope>): <mensaje en imperativo>
```
**Tipos comunes:**
-   `feat` (nueva funcionalidad)
-   `fix` (arreglo de bug)
-   `docs` (documentación)
-   `chore` (mantenimiento, ajustes no funcionales)
-   `refactor` (cambia estructura sin cambiar comportamiento)
-   `test` (añade o ajusta pruebas)
-   `build` (cambios en build, dependencias)
-   `ci` (cambios en pipelines)
**Scope** (opcional): `api`, `db`, `ui`, `infra`, `auth`, etc.

**Ejemplos buenos:**
```text
feat(api): añade endpoint /health
fix(auth): corrige validación de token expirado
docs(readme): agrega diagrama de flujo git
refactor(db): separa repositorio de consultas
ci(workflow): agrega job de build en PRs
chore(repo): inicializa .gitignore y license
```
**Ejemplos a evitar:**
```text
update files
fix stuff
final version
```
