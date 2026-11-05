💻 Supply-Chain-SQL-Portfolio 

Portfolio de requêtes SQL appliquées à la Supply Chain (SAP MM/WMS). Ce dépôt regroupe des cas pratiques d'analyse de données logistiques, de gestion des stocks et d'optimisation des flux d'achats.

À propos du projet

Ce portfolio démontre la capacité à manipuler et interroger des bases de données relationnelles pour répondre à des problématiques métiers supply chain (gestion des stocks, rotations, performances fournisseurs, traçabilité des flux).

Structure du dépôt

* queries : Scripts SQL commentés et optimisés (Jointures, Agrégations, Fonctions de fenêtrage, CASE WHEN, etc.).

* datasets : Échantillons de données structurées.

* docs : Dictionnaire de données et modélisation (schéma en étoile, tables SAP MM/WMS).

Compétences & Outils mobilisés

* Langage : SQL (PostgreSQL / MySQL / T-SQL selon ton choix)

* Domaine Métier : Supply Chain, Achats (MM), Gestion d'entrepôt (WMS)

* Concepts : Logique conditionnelle, jointures complexes, agrégations, analyse temporelle.

* ## 🏗️ Modèle de Données & Tables de la Supply Chain

Voici la structure relationnelle de la base de données utilisée pour les analyses :

* `fournisseurs` : `fournisseur_id`, `nom`, `pays`
* `articles` : `article_id`, `libelle_article`, `famille`, `prix_unitaire`, `stock_securite`
* `stocks` : `stock_id`, `article_id`, `entrepot`, `quantite_en_stock`
* `commandes_achats` : `commande_id`, `fournisseur_id`, `article_id`, `quantite_commandee`, `date_commande`, `statut`
* `livraisons` : `livraisons_id`, `commande_id`, `date_reception_effective`, `quantite_recue`, `statut_qualite`

---

## 📦 Sommaire des Modules
* [Module 1 : Fondamentaux et Filtrage Opérationnel (Exercices 1 à 5)](#module-1--fondamentaux-et-filtrage-opérationnel)
* [Module 2 : Agrégations, Analyses Financières et Groupements (Exercices 6 à 9)](#module-2--agrégations-analyses-financières-et-groupements)
* [Module 3 : Jointures Multi-tables et Logique Métier Avancée (Exercices 10 à 14)](#module-3--jointures-multi-tables-et-logique-métier-avancée)
* [Module 4 : Intelligence Temporelle, Délais et Traçabilité Globale (Exercices 15 à 21)](#module-4--intelligence-temporelle-délais-et-traçabilité-globale)

Créé par MPETI BOKATOLA Michée Christ Merveille   

---

### Contact :
* **Email** : m.c.merveillem@gmail.com
* **WhatsApp** : +242 06 186 54 23
* **LinkedIn** : Merveille MPETI

---

### Voir :
* 📄 [Cartographie Processus SAP S/4HANA](https://tinyurl.com/SAP-Flux)
* 💻 [Requêtes SQL & Cas Pratiques](https://tinyurl.com/SQL-Sc)
* 🚀 [Mon Portfolio Complet sur Notion](https://tinyurl.com/Merveille-SC)
