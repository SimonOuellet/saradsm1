# TD infrastructure M1

Objectif : Comprendre ce qu'est l'infrastructure d'un système d'information, ses composants et savoir les utiliser.

Type d'environnement : Infrastructure Cloud  
Cloud : [Google Cloud Plateform (GCP)](https://console.cloud.gogle.com)  

Composants utilisés :  
- Google storage / Buckets
- BigQuery
- Lookers
- IAM / sécurité

Notions à observer 
- Localisation des composants
- Authentification / Habilitation / Audit
- Utilisation de fichiers plats
- Utilisation d'un moteur de base de données orientée colonnes
- Redressement de données statistiques
- Réaliser un dashboard démontrant l'effet du redressement des données.

# Déroulement du TD

1. Vous allez vous mettre en équipe étude statistique.
2. Nommez un responsable d'équipe qui aura les droits administrateur du projet GCP. C'est avec cette personne que le reste de l'équipe devra collaborer pour obtenir les droits sur les autres composants. Cette personne devra communiquer son adresse mail "gmail" à iriaf.m1.2023@gmail.com pour que son compte soit ajouté en tant qu'administrateur de la plateforme.
3. Vous allez créer un composant de stockage (bucket) par équipe et y déposez vos données en format fichier plat (csv ou json).
4. Depuis BigQuery, vous créez un ensemble de données (dataset) par équipe et y importez vos données.
5. Créez une table externe vers un fichier plat contenant vos indices de redressement.
6. Créez la ou les requêtes SQL de vos données avec des valeurs redressées et non redressées.
7. Créer un dashboard Lookers (ou autres outils qui peut se connecter à BigQuery) qui démontre la différence entre les données redressées et non redressées.
8. Présentez vos résultats en classe.