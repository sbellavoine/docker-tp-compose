# Commandes

```bash
# vérifier la configuration du fichier compose
docker compose config

# construire et lancer la stack
docker compose up -d --build

# vérifier que les services tournent
docker compose ps

# voir les logs
docker compose logs

# arrêter la stack
docker compose down

# arrêter la stack et supprimer aussi le volume
docker compose down -v