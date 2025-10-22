FROM postgres:17.2-alpine

# On définit la base et l’utilisateur
ENV POSTGRES_DB=db \
   POSTGRES_USER=usr

# On copie les scripts d’initialisation
COPY initdb/ /docker-entrypoint-initdb.d/