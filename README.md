# Portfolio CV — Valentin Brizard

Portfolio personnel orienté informatique, administration système et cybersécurité.

## Présentation

Ce dépôt contient mon site CV/portfolio. Il présente mon parcours, mes compétences techniques et mes projets, notamment mon homelab personnel `serverdecaiin`.

Le site est volontairement léger et sans framework afin de rester simple à auditer, rapide à charger et facile à auto-héberger.

## Stack

- HTML5
- CSS3
- JavaScript vanilla
- Nginx
- Docker / Docker Compose

## Déploiement

Le déploiement prévu se fait sur mon serveur Ubuntu personnel avec Docker et Nginx.

```bash
docker compose up -d
```

Par défaut, le site est exposé sur :

```text
http://192.168.1.197:8080
```

## Structure

```text
portfolio-cv/
├── index.html
├── styles.css
├── script.js
├── compose.yaml
├── .gitignore
└── README.md
```

## Sécurité

Aucun secret, mot de passe, token, clé privée ou fichier `.env` sensible ne doit être ajouté au dépôt.

## Statut

Projet en cours d'amélioration : contenu du CV, projets techniques, version PDF et mise en ligne publique seront ajoutés progressivement.
