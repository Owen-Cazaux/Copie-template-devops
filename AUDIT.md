# Audit DevOps 

**Périmètre :** dépôt et configurations visibles dans le projet. Les paramètres GitHub (protection de branches, secrets, environnements) ne sont pas vérifiables depuis les fichiers locaux.

## Ce qui est présent

- des tests unitaires pytests.
- Tests Playwright présents
- Configuration dans le .env ignoré par git
- Dockerfiles pour l’API et le front, Compose de développement avec PostgreSQL, health checks et `.env.example`.

## Ce qui manque

- Aucune protection de la branch main
- Aucun workflow CI 
- Aucun test automatisé de déploiement


