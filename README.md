# DB

👨‍💻 Présentation
Cette comparaison met en évidence les principales différences entre MongoDB, une base de données NoSQL orientée documents, et les bases de données SQL traditionnelles comme MySQL ou PostgreSQL.
Elle vise à clarifier leurs fonctionnalités, leurs avantages, leurs limites et les cas d'utilisation adaptés.

1️⃣ Définition des deux types
🧩 SQL (SGBD relationnels) :
Structure rigide basée sur des tables (lignes et colonnes).

Données fortement typées et liées par des relations (clés étrangères).

Utilisation du langage SQL (Structured Query Language).

Nécessite un schéma défini à l'avance.

Exemples : MySQL, PostgreSQL, Oracle.

🧩 MongoDB (NoSQL documentaire) :
Utilise des documents JSON stockés dans des collections.

Pas de schéma strict (données semi-structurées).

Requêtes sous forme de filtres JSON/BSON.

Scalabilité horizontale native.

Idéal pour les applications modernes et les gros volumes de données.

2️⃣ Fonctionnalités principales
Fonctionnalité	SQL (MySQL, PostgreSQL)	MongoDB (NoSQL)
Modèle de données	Tables relationnelles	Documents JSON
Langage de requête	SQL (SELECT, JOIN, etc.)	Méthodes JS-like (find, aggregate)
Schéma	Défini et rigide	Flexible et dynamique
Relations	Fortement supportées	Faiblement supportées
Transactions	ACID complet	ACID (depuis MongoDB 4.0)

3️⃣ Avantages et inconvénients
Critère	SQL	MongoDB
✅ Avantages	Cohérence des données, relations solides	Haute performance, souplesse des données
❌ Inconvénients	Schéma rigide, moins flexible	Relations complexes moins naturelles
📦 Stockage	Structuré	Semi-structuré / non structuré
⚙️ Scalabilité	Verticale principalement	Horizontale native

4️⃣ Cas d'utilisation typiques
SQL :
Applications financières

ERP

Gestion de clients (CRM)

Systèmes de réservation

MongoDB :
Réseaux sociaux

Applications mobiles/web modernes

Données IoT ou big data

CMS ou catalogues produits flexibles

5️⃣ Conclusion
MongoDB (NoSQL) est idéal pour des projets flexibles, à grande échelle ou avec des données variées.

SQL reste incontournable pour les projets structurés et à fort besoin d’intégrité relationnelle.

Le bon choix dépend de votre type de données, du volume, et des besoins de performance/scalabilité.

