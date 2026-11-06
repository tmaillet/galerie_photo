# Galerie Photo

Site de gestion de galeries photo (Symfony + Docker).

## Fonctionnalités
- Inscription / connexion (blocage après 3 échecs)
- Upload de photos (JPEG/PNG, 5 Mo max)
- Publication ordonnée dans une galerie publique
- Espace administrateur (suppression / déblocage de comptes)

## Prérequis
- Docker et Docker Compose

## Lancement
docker compose up -d --build

- Site : http://localhost:8080
- Mailpit (e-mails de test) : http://localhost:8025

Commandes Symfony :

docker compose exec php php bin/console <commande>
docker compose exec php composer <commande>
