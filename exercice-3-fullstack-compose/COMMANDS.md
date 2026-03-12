# Commandes

```bash
# vérifier la configuration
docker compose config

# construire et lancer la stack
docker compose up -d --build

# vérifier que les services tournent
docker compose ps

# voir les logs
docker compose logs

# arrêter et supprimer la stack
docker compose down

# arrêter et supprimer la stack avec les volumes
docker compose down -v