# EasyBiz
Application multiplateforme 
## Description : 
EasyBiz est une application multiplateforme (Android, iOS, PC) conçue pour aider les propriétaires de petites entreprises à présenter leurs produits dans une plateforme organisée par catégories. Les clients peuvent explorer les produits, les ajouter à un panier, et bénéficier d’un système de recommandation personnalisé qui propose des produits pertinents en fonction de leurs préférences.
*Deux options sont proposées pour confirmer les achats :

1- Utilisation de l’IA : Une IA interactive discute avec le client pour confirmer la commande. Si le client valide, l’IA envoie une notification au propriétaire avec les détails de l’achat, ajuste le stock automatiquement, et finalise la transaction.
2-Paiement par carte : Le client peut finaliser l'achat via un système de paiement sécurisé par carte D17, avec mise à jour automatique du stock et notification au propriétaire.
Cette application offre une expérience moderne et intuitive, adaptée à la gestion des petites entreprises et à la satisfaction des clients.
## Technologies utilisées :
### Frontend :
Flutter : Pour développer une interface utilisateur unique et responsive pour Android, iOS, et PC.
### Backend :
Django REST Framework : Pour gérer les API nécessaires à la gestion des utilisateurs, produits, commandes, et recommandations.
FastAPI : Pour déployer les modèles IA et les intégrer au backend de manière rapide et efficace.
### Base de données :
Firebase : Pour la gestion des notifications en temps réel.
PostgreSQL : Pour le stockage structuré des données, comme les utilisateurs, produits, et transactions.
### Intelligence Artificielle :
TensorFlow ou PyTorch : Pour entraîner et déployer le modèle d’IA interactif pour la confirmation des commandes.
Scikit-learn : Pour le système de recommandation basé sur des algorithmes de filtrage collaboratif ou de contenu.
### Paiements :
Stripe API : Pour la gestion des paiements sécurisés par carte D17.
### Déploiement :
AWS ou Google Cloud : Pour héberger l'application, assurer l'évolutivité et gérer les bases de données et les modèles IA.
Docker : Pour conteneuriser les services backend et faciliter le déploiement.
