# Page-Speed-API
Connecteur API pour Google PageSpeed Insights : Simplifiez l'accès et l'analyse des performances web

---

# Connecteur API pour Google PageSpeed Insights

## Description

Ce projet est un connecteur API conçu pour faciliter l'interaction avec [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/). Il permet de récupérer les scores de performance, d'accessibilité, de SEO, et des meilleures pratiques d'une page web en utilisant des appels simplifiés à l'API de Google. 

### Pourquoi Google PageSpeed Insights ?

Google PageSpeed Insights (PSI) est un outil puissant pour mesurer la performance d'une page web sur mobile et desktop. Il analyse une URL en fonction de divers critères, tels que :
- **Vitesse de chargement** : Indique si une page est rapide pour les utilisateurs.
- **Accessibilité** : Assure que le contenu est utilisable par tous.
- **SEO** : Vérifie si la page respecte les bonnes pratiques pour le référencement.
- **Meilleures pratiques** : Recommande des améliorations pour optimiser l'expérience utilisateur.

Utiliser ces données peut améliorer :
- L'expérience utilisateur.
- Le référencement naturel (SEO).
- La fidélité et la satisfaction des visiteurs.

## Fonctionnalités

- Récupération facile des données JSON de Google PSI.
- Analyse des performances pour les versions mobile et desktop.
- Configuration des stratégies d’analyse (ex. : mobile ou desktop).
- Gestion des erreurs pour une expérience utilisateur robuste.

## Prérequis

Pour utiliser ce connecteur, vous aurez besoin de :
- Une clé API Google Cloud (voir la [documentation officielle](https://developers.google.com/speed/docs/insights/v5/get-started)).
- Python 3.x installé sur votre machine.
- Les bibliothèques suivantes : `requests`, `python-dotenv`.

## Installation

1. Clonez ce dépôt Git :
   ```bash
   git clone https://github.com/ton-utilisateur/google-pagespeed-api-connector.git
   cd google-pagespeed-api-connector
   ```
2. Installez les dépendances nécessaires :
   ```bash
   pip install -r requirements.txt
   ```
3. Configurez votre clé API :
   - Créez un fichier `.env` à la racine du projet.
   - Ajoutez votre clé API au fichier :
     ```
     API_KEY=VOTRE_CLE_API
     ```

## Avantages de l’intégration

1. **Automatisation** : Gagnez du temps en automatisant vos analyses de performance.
2. **Optimisation continue** : Suivez l’évolution des performances de vos sites web dans le temps.
3. **Rapidité et simplicité** : Interface simplifiée pour exploiter pleinement l'API.

## Contribuer

Les contributions sont les bienvenues ! Si vous avez des idées ou des corrections :
1. Forkez le projet.
2. Créez une branche pour vos modifications :
   ```bash
   git checkout -b ma-nouvelle-fonctionnalite
   ```
3. Soumettez une pull request.

## Ressources utiles

- [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
- [Documentation de l'API PageSpeed](https://developers.google.com/speed/docs/insights/v5/get-started)

---! 🚀
