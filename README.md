# Sql Data Warehouse Project
Construire un entrepôt de données moderne avec SQL Server, incluant un processus ETL, modélisation des données et analyses.

Bienvenue dans le dépôt du projet Data Warehouse  ! 🚀
Ce projet présente une solution complète d’entreposage de données et d’analyse, allant de la construction d’un data warehouse à la production d’insights exploitables. il met en avant les meilleures pratiques du secteur en ingénierie des données et en analyse de données.

----
## Architecture DATA

L’architecture des données de ce projet suit le modèle Medallion avec les couches Bronze, Silver et Gold :

<img width="1133" height="583" alt="Image" src="https://github.com/user-attachments/assets/58fa2415-a31e-4039-a231-45b702f4eda8" />

1.**Couche Bronze** : Stocke les données brutes telles qu’elles proviennent des systèmes sources. Les données sont ingérées à partir de fichiers CSV dans une base de données SQL Server.

2.**Couche Silver** : Cette couche inclut les processus de nettoyage, de standardisation et de normalisation des données afin de les préparer pour l’analyse.

3.**Couche Gold** : Contient les données prêtes pour l’entreprise, modélisées sous forme de schéma en étoile, nécessaires pour les rapports et l’analytique.

----
📖 **Aperçu du projet**

Ce projet comprend :

1.**Architecture des données** : Conception d’un entrepôt de données moderne en utilisant l’architecture Medallion avec les couches Bronze, Silver et Gold.

2.**Pipelines ETL** : Extraction, transformation et chargement des données depuis les systèmes sources vers l’entrepôt.

3.**Modélisation des données** : Développement de tables de faits et de dimensions optimisées pour les requêtes analytiques.

4.**Analytique & Reporting** : Création de rapports et tableaux de bord basés sur SQL pour fournir des insights exploitables.

----
## 🚀 Prérequis du projet

**Objectif**
Développer un entrepôt de données en utilisant SQL Server afin de consolider les données de ventes, permettant la création de rapports analytiques et la prise de décisions éclairées.

**Spécifications**
**Sources de données** : Importer les données à partir de deux systèmes sources (ERP et CRM) fournis sous forme de fichiers CSV.

**Qualité des données** : Nettoyer et résoudre les problèmes de qualité des données avant l’analyse.

**Intégration** : Combiner les deux sources dans un modèle de données unique et convivial, conçu pour les requêtes analytiques.

**Périmètre** : Se concentrer uniquement sur le jeu de données le plus récent ; l’historisation des données n’est pas requise.

**Documentation** : Fournir une documentation claire du modèle de données pour soutenir à la fois les parties prenantes métier et les équipes analytiques.

----
## BI : Analytique & Reporting (Data Analysis)

**Objectif**
Développer des analyses basées sur SQL afin de fournir des insights détaillés sur :

* **Comportement des clients**

* **Performance des produits**

* **Tendances des ventes**

----
## Flux de données 

Le **flux de données** dans cette architecture représente le chemin que suivent les données depuis les systèmes sources jusqu’aux couches finales du modèle.

<img width="1127" height="536" alt="Image" src="https://github.com/user-attachments/assets/6f8080a3-0f0f-431b-b2e6-348fcadc34be" />

----
## Intégration des données
L’intégration dans une architecture de données consiste à fusionner et harmoniser les informations provenant de plusieurs systèmes sources afin de créer une vue unifiée et cohérente pour l’analyse.

✅ **Objectif de l’intégration :**

* Relier les données des deux systèmes pour obtenir une vision complète.

* Enrichir les dimensions (produits et clients) avec des attributs supplémentaires provenant de l’ERP.

* Préparer un modèle analytique optimisé pour le reporting et la BI.

<img width="1035" height="507" alt="Image" src="https://github.com/user-attachments/assets/c0aa12f6-2502-4fd2-ac8b-985f88ae9d43" />


