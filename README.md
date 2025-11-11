# Curso 2025 - Equipo 1
Repositorio del equipo para prácticas de Git y flujo de trabajo.
Flujo elegido: GitHub Flow
- main protegido (solo merges por PR).
- ramas: feature/<tema>
- proceso: crear rama → commit/push → PR → review → merge (squash).
  
-   **Features nuevas:** `feature/<tema-kebab-case>`
    
    -   Ej: `feature/api-health-endpoint`, `feature/ui-login-form`
        
-   **Bugs urgentes en producción:** `hotfix/<bug-descriptivo>`
    
    -   Ej: `hotfix/fix-nullref-on-auth`
