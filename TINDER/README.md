# 🔥 Projet Tinder – Analyse des critères de matching

## 📌 Contexte

Ce projet a pour objectif d’analyser les données issues d’une expérience type **speed-dating** afin de comprendre les critères qui influencent le plus les **matchs** entre participants.
Tinder (ou toute autre app de rencontre) pourrait tirer profit de ces résultats pour améliorer ses algorithmes de recommandation et d’appariement.

---

## 🎯 Objectifs

* Explorer les données et identifier les valeurs manquantes
* Comparer les **critères de choix Homme vs Femme** au cours de la soirée
* Évaluer l’impact de différents facteurs (intelligence, attirance, intérêts communs, origine…) sur la probabilité de match
* Fournir des recommandations concrètes pour améliorer l’expérience utilisateur

---

## 🛠️ Stack technique

* **Python** (pandas, numpy, matplotlib, seaborn)
* **Jupyter Notebook** pour l’analyse exploratoire (EDA)
* **Plotly** pour les visualisations interactives

---

## 🔄 Pipeline analytique

1. **Exploration & nettoyage des données**

   * Détection et gestion des **valeurs manquantes**
   * Standardisation des variables qualitatives et quantitatives

2. **Analyse comparative Homme vs Femme**

   * Évolution des critères au fil de la soirée
   * Importance relative de l’attirance, de l’intelligence et des intérêts communs

3. **Analyse complémentaire**

   * Impact de la position dans la soirée (effet fatigue/attention)
   * Effet des attributs perçus vs réels

4. **Visualisations & Insights**

   * Graphiques comparatifs homme/femme
   * Répartition des matchs selon les critères
   * Effet des intérêts communs et de la “même origine”

---

## 📊 Résultats principaux

* **Différence de critères Homme/Femme :**

  * Les hommes valorisent **l’attirance** dès le début
  * Les femmes privilégient d’abord **l’intelligence**, puis l’attirance monte en importance

* **Intérêts communs :**

  * Impact positif (même si modéré) sur la probabilité de match
  * Plus déterminants que l’appartenance ethnique

* **Effet du timing :**

  * Être parmi les **premiers rendez-vous** augmente légèrement les chances de match
  * Fin de soirée → fluctuations plus fortes, probablement liées à la fatigue

---

## 🚀 Recommandations pour Tinder

* **Mettre plus en avant les intérêts communs** dans le matching et la présentation des profils
* Intégrer une **pondération dynamique** selon le moment de l’interaction
* Tester un algorithme de recommandation basé sur la combinaison **attirance + intelligence + centres d’intérêt**

---

## 👨‍💻 Auteur

Projet réalisé dans le cadre du **Bootcamp Data Fullstack – Jedha**.
Auteur : MARC

---


