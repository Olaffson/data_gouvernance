# **Configuration de Purview**

Bienvenue dans la documentation sur la configuration de Microsoft Purview. Cette section détaille les étapes essentielles pour gérer les collections, les classifications, les scans et les rôles.

---

## **Création des Collections**

Les collections ont été créées pour organiser et gérer les ressources.

![Capture d'écran des collections](images/collection.png)

---

## **Attribution des Sources**

Les sources de données ont été assignées aux différentes collections créées.

![Capture d'écran des sources de données](images/data_source.png)

---

## **Suivi des Scans**

Le suivi des scans peut être effectué dans l'onglet Monitoring. Voici quelques exemples d'écrans de suivi :

![Capture d'écran de Monitoring - Partie 1](images/monitoring.png)
![Capture d'écran de Monitoring - Partie 2](images/monitoring2.png)

---

## **Création des Classifications**

### Classifications Manuelles
Des classifications peuvent être attribuées manuellement à une ou plusieurs tables, ou à un ou plusieurs champs spécifiques.

![Capture d'écran des classifications manuelles](images/classification.png)

### Règles de Classification
Des règles de classification peuvent également être créées pour appliquer automatiquement des classifications lors des scans.

![Capture d'écran des règles de classification](images/classification_rules.png)

---

## **Classification des Bases de Données SQL**

### Vue d'Ensemble
Dans l'onglet "Overview", vous pouvez visualiser les classifications appliquées à l'ensemble de la table et à certains champs.

![Capture d'écran - Overview de la classification BDD](images/classification_bdd_overview.png)

### Vue du Schéma
Dans l'onglet "Schema", seules les classifications des champs sont affichées.

![Capture d'écran - Schema de la classification BDD](images/classification_bdd_schema.png)

---

## **Classification des Fichiers .CSV**

Les fichiers CSV dans le Data Lake peuvent également être classifiés. Voici une capture d'écran d'un aperçu des classifications :

![Capture d'écran - Classification CSV Overview](images/classification_csv_overview.png)

---

## **Gestion des Rôles**

Les rôles dans Purview peuvent être configurés pour gérer les autorisations. Par exemple, un utilisateur nommé "Jonathan" a été ajouté au rôle de Data Reader.

![Capture d'écran de la gestion des rôles](images/role_assignements.png)

---
