# Política central de Renovate de GUNDO

Este repositorio define el comportamiento común de Renovate para los repositorios activos de GUNDO.

La política prioriza tres objetivos:

- las correcciones de seguridad las gestiona Dependabot sin esperar la ventana de mantenimiento;
- las actualizaciones rutinarias se agrupan y se ejecutan una vez por semana;
- los cambios mayores requieren aprobación explícita desde el Dependency Dashboard.

Los repositorios de la organización adoptan `default.json` automáticamente al incorporarse a Renovate. Los repositorios personales de JP lo heredan mediante `jplannnou/renovate-config`.
