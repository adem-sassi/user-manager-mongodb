Gestionnaire de Clients - Application Web
Description de l'application
L'application est un système de gestion des clients développé avec Node.js, Express, EJS et MongoDB. Elle permet aux utilisateurs d'ajouter, de lire, de mettre à jour et de supprimer des informations sur les clients. L'application offre une interface utilisateur conviviale pour gérer efficacement les données des clients.

Fonctionnalités principales :
CRUD des clients : Ajouter, lire, mettre à jour et supprimer des informations sur les clients.
Interface utilisateur intuitive : Interface utilisateur basée sur EJS pour faciliter la gestion des clients.
API RESTful : API permettant d'accéder et de manipuler les données des clients.
Guide d'utilisation de l'API
L'API fournit des endpoints pour effectuer des opérations CRUD sur les données des clients. Voici quelques exemples d'utilisation de l'API :

Endpoints disponibles :
POST /api/users : Ajouter un nouveau client.
GET /api/users : Récupérer la liste de tous les clients.
PUT /api/users/:id : Mettre à jour les informations d'un client existant.
DELETE /api/users/:id : Supprimer un client.

Exemples d'utilisation de l'API :
1. Ajouter un nouveau client
Envoyez une requête POST avec les informations du client au format JSON.
2. Récupérer la liste de tous les clients
3. Mettre à jour les informations d'un client existant
Remplacez :id par l'ID du client et envoyez une requête PUT avec les nouvelles informations au format JSON.
4. Supprimer un client
Remplacez :id par l'ID du client.
