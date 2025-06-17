# 🏢 Mini-ERP-Backend

## 📋 Description  
**Mini ERP Backend** is a modular back-end application developed in .NET. It centralizes the management of a company's core resources such as clients, orders, invoices, and inventory. The system is designed with scalability and maintainability in mind, following a clean architecture with separated concerns for each business domain.

---

## 🚀 Main Features

- 🔹 **Client Management**: Create, update, and monitor client data.
- 🔹 **Order Management**: Track orders, their status, and validation.
- 🔹 **Invoicing**: Generate and manage invoices and payment statuses.
- 🔹 **Inventory Management**: Track products, stock levels, and restocking.
- 🔹 **Access Gateway (AppGateway)**: Acts as the central API gateway for all modules.

---

## 🏗️ Project Architecture
📂 AppGateway/ - Interface API centralisant les requêtes vers les autres modules.  
📂 ERP/ - Cœur de l'application contenant les règles métiers principales.  
📂 GestionClients/ - Module de gestion des clients et de leur historique d'achats.  
📂 GestionCommande/ - Gestion des commandes et de leur traitement.  
📂 Facturation/ - Gestion des factures et paiements.  
📂 GestionStock/ - Suivi des stocks et gestion des fournisseurs.  
📂 Persistence/ - Gestion de la base de données et des entités.  


---

## 🛠️ Technologies Used

- ✅ [.NET Core](https://dotnet.microsoft.com/)
- ✅ [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/)
- ✅ [SQLite](https://www.sqlite.org/index.html) *(or any other RDBMS)*

---

## 📦 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/oussama-grami/Mini-ERP-Backend.git
cd Mini-ERP-Backend
```

### 2️⃣ Set up the Database
```bash 
dotnet ef database update
```
### 3️⃣ Run the Application
```bash
dotnet run --project AppGateway
```
## 📜 Licence
Ce projet est sous licence MIT.

## 👨‍💻👩‍💻 Developers:
   #### Oussema Guerami
   #### Mohammed Aziz Dhouibi
   #### Rayen Chemlali
   #### Khalil Ghimaji
