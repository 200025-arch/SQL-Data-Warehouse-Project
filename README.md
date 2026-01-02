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
