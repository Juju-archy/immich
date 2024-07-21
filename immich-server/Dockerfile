# Utiliser l'image de base immich-server
FROM ghcr.io/immich-app/immich-server:release

# Copier les fichiers nécessaires
COPY . /usr/src/app

# Définir les volumes
VOLUME [/usr/src/app/upload, /etc/localtime]

# Exposer les ports nécessaires
EXPOSE 3001

# Définir le fichier d'environnement
ENV FILE .env

# Commande pour démarrer le serveur
CMD [npm, start]

