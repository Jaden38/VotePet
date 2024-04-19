# Image de base : nginx version 1.12
FROM nginx:1.12
# copier default.conf dans : /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/
# Fichier HTML pour réponses BACKEND-NOT-FOUND : à copier dans /var/www/html/backend-not-found.html
COPY backend-not-found.html /var/www/html/backend-not-found.html
# Configuration du proxy : copier proxy.conf dans /etc/nginx/includes/
COPY proxy.conf /etc/nginx/includes/
# Exposez le port 80 pour que le service puisse être accessible depuis l'extérieur du conteneur
EXPOSE 80
