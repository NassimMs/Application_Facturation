# Application Facturation
Activité Pratique du Contrôle : Créer une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.

# Objectif Status:  
Créer une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.
Travail à faire :

1. Créer le micro-service customer-service qui permet de gérer les client    :  Done ✔️ 
2. Créer le micro-service inventory-service qui permet de gérer les produits : Done ✔️
3. Créer la Gateway Spring cloud Gateway avec une Configuration statique du système de routage : Done ✔️
4. Créer l'annuaire Eureka Discrovery Service : Done ✔️
5. Faire une configuration dynamique des routes de la gateway : Done ✔️
6. Créer le service de facturation Billing-Service en utilisant Open Feign  Done ✔️
7. Créer un client Web Angular (Clients, Produits, Factures)   Pending ... ❌
8. Déployer le serveur keycloak :   Pending ❌
     - Créer un Realm
     - Créer un client à sécuriser
     - Créer des utilisateurs
     - Créer des rôles
     - Affecter les rôles aux utilisateurs
     - Tester les différents modes d'authentification avec Postman en montrant les contenus de Access-Token, Refresh Token 
9. Sécuriser les micro-services et le frontend angular en déployant les adaptateurs Keycloak Pending ❌
10. Ajouter des Fonctionnalités supplémentaires de votre choix  Pending ❌

# How to use : 

1 - Start each Microservice .
2 - Check in Eureka Server if the microservices are up 

![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/Backend/eureka.png)

3 - Test Billing Service Endpoints (bills,fullbill) default port 8083

![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/Backend/FullBill_Capture.png)

4 - Other functionalities still will be added ...






