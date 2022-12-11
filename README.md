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
7. Créer un client Web Angular (Clients, Produits, Factures)   Done ✔️
8. Déployer le serveur keycloak :   Done ✔️
     - Créer un Realm
     - Créer un client à sécuriser
     - Créer des utilisateurs
     - Créer des rôles
     - Affecter les rôles aux utilisateurs
     - Tester les différents modes d'authentification avec Postman en montrant les contenus de Access-Token, Refresh Token 
9. Sécuriser les micro-services et le frontend angular en déployant les adaptateurs Keycloak Done ✔️
10. Ajouter des Fonctionnalités supplémentaires de votre choix  

# How to use : 

1 - Start each Microservice .
2 - Check in Eureka Server if the microservices are up 

![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/Backend/eureka.png)

3 - Test Billing Service Endpoints (bills,fullbill) default port 8083

![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/Backend/FullBill_Capture.png)



## Main APIs Endpoints via Gateway 
```
    http://localhost:8888/CUSTOMER.SERVICE/customers <- Get All Customers
    http://localhost:8888/BILLING-SERVICE/fullBill/ <- Get Full Bill
    http://localhost:8888/PRODUCT.SERVICE/products  <- Get All Products
```

# Functionnalities : 

## Creating Keycloak Realm :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/realm-creation.png)

## Creating Users :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/users.png)

## Creating Roles :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/roles.PNG)

## Getting Access Token :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/token_endpoint.png)

## JWT IO Decoding :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/jwt_io.png)

## Angular Frontend + Keycloak Login  :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/login_screen.png)

## Angular Frontend + Keycloak Login  :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/login_screen.png)

## Products Frontend  :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/products.png)

## Customers Frontend  :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/customers.png)

## Bill Frontend  :
![enter image description here](https://github.com/NassimMs/Application_Facturation/blob/master/All%20Captures/bill.png)







