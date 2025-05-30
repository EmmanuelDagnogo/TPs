# Dockerfile
FROM postgres:17.2-alpine

# Définir les variables d'environnement (à éviter en prod)
ENV POSTGRES_DB=db

# Copier les fichiers d'initialisation SQL dans le dossier d'initialisation de postgres
COPY docker-entrypoint-initdb.d/ /docker-entrypoint-initdb.d
