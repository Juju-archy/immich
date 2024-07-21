# Utiliser l'image de base immich-machine-learning
FROM ghcr.io/immich-app/immich-machine-learning:${IMMICH_VERSION:-release}

# Copier les fichiers nécessaires
COPY . /usr/src/app

# Définir les volumes
VOLUME ["/cache"]

# Définir le fichier d'environnement
ENV FILE .env

# Commande pour démarrer le service de machine learning
CMD ["npm", "start"]

