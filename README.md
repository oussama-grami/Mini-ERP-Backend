# Mini-ERP-Backend
Description
Mini ERP Backend est une application back-end développée en .NET qui centralise la gestion des ressources d'une entreprise. Ce système modulaire permet d'assurer différentes fonctions essentielles telles que la gestion des clients, des commandes, de la facturation et du stock.

🚀 Fonctionnalités principales:  
🔹 Gestion des clients : Création, modification et suivi des informations clients.  
🔹 Gestion des commandes : Suivi des commandes, état de traitement et validation.  
🔹 Facturation : Génération et suivi des factures.  
🔹 Gestion du stock : Suivi des produits, quantités disponibles et réapprovisionnement.  
🔹 Passerelle d’accès (AppGateway) : Point central pour les communications entre les différents modules.  

🏗️ Architecture du projet  
📂 AppGateway/ - Interface API centralisant les requêtes vers les autres modules.  
📂 ERP/ - Cœur de l'application contenant les règles métiers principales.  
📂 GestionClients/ - Module de gestion des clients et de leur historique d'achats.  
📂 GestionCommande/ - Gestion des commandes et de leur traitement.  
📂 Facturation/ - Gestion des factures et paiements.  
📂 GestionStock/ - Suivi des stocks et gestion des fournisseurs.  
📂 Persistence/ - Gestion de la base de données et des entités.  

🛠️ Technologies utilisées  
.NET Core  
Entity Framework (ORM)  
SQLite (ou autre SGBD)   
## 📦 Installation et utilisation    
### -1- Cloner le projet   
    git clone https://github.com/oussama-grami/Mini-ERP-Backend.git
    cd Mini-ERP-Backend
### -2- Configurer la base de données   
    dotnet ef update database
### -3- Lancer l'application 
    dotnet run --project AppGateway

## 📜 Licence
Ce projet est sous licence MIT.
    
