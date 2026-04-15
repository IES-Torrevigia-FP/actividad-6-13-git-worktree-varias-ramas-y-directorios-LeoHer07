# Reflexión sobre Git Worktree

## ¿Qué ventajas tiene usar worktrees frente a cambiar de rama en el mismo directorio?
El uso de worktrees permite trabajar en diferentes ramas de un repositorio sin tener que hacer checkout de cada una, lo cual ahorra tiempo y evita interferencias entre ramas. Puedes tener múltiples directorios con diferentes ramas activas simultáneamente.

## ¿Qué ventajas tiene usar worktrees frente a clonar el repositorio varias veces?
Los worktrees no requieren duplicar el repositorio completo, lo cual ahorra espacio y facilita la sincronización de cambios entre directorios. Solo se necesita un repositorio central y los worktrees pueden compartirse entre ellos.

## Dos situaciones reales donde usaría git worktree
1. Revisar un pull request mientras se desarrolla una nueva funcionalidad en otra rama.
2. Probar un hotfix en paralelo sin tocar el trabajo actual de la rama principal.

## Buenas prácticas para nombrar y organizar los worktrees
Se recomienda usar un esquema de nombres claro para los directorios de los worktrees, como , y limpiar periódicamente los worktrees no utilizados para evitar acumular directorios innecesarios.
