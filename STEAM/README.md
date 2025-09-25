# 🎮 Projet STEAM – Analyse des jeux vidéo sur la marketplace

## 📌 Contexte

Steam est la principale plateforme mondiale de distribution numérique de jeux vidéo.
Ubisoft souhaite analyser en profondeur les données issues de Steam afin de mieux comprendre l’écosystème vidéoludique et identifier les facteurs qui influencent la **popularité** et les **ventes** des jeux.

---

## 🎯 Objectifs

* Analyser le marché global du jeu vidéo sur Steam (tendances macro)
* Étudier les **genres les plus populaires et rentables**
* Explorer les différences selon les **éditeurs** et les **plateformes** (Windows/Mac/Linux)
* Identifier des pistes stratégiques pour orienter les futurs jeux d’Ubisoft

---

## 🛠️ Stack technique

* **PySpark (Databricks)** → manipulation de données massives
* **Python** → transformations et analyses
* **Databricks Visualisation** → création de dashboards interactifs
* **S3** → stockage des données (fichier JSON semi-structuré)

---

## 🔄 Pipeline analytique

1. **Chargement et préparation des données**

   * Lecture depuis **S3** du fichier `steam_game_output.json`
   * Nettoyage des données et gestion des champs imbriqués (ex: `getField()`, `explode()`)

2. **Analyses macro**

   * Distribution des sorties par année (impact du COVID sur la production ?)
   * Répartition des prix et importance des réductions
   * Classement des éditeurs les plus actifs
   * Langues représentées et taux de jeux interdits aux moins de 16/18 ans

3. **Analyses des genres**

   * Genres les plus représentés
   * Ratio critiques positives/négatives par genre
   * Genres les plus lucratifs
   * Préférences des éditeurs par genre

4. **Analyses des plateformes**

   * Disponibilité sur Windows, Mac et Linux
   * Spécialisation de certains genres par plateforme

---

## 📊 Résultats principaux

* **Explosion du nombre de sorties entre 2010 et 2019**, ralentissement pendant la période COVID
* Les genres **Action** et **Indie** dominent en volume, mais les genres **RPG** et **Strategy** obtiennent de meilleurs retours critiques
* Les **intérêts linguistiques** montrent une forte concentration sur l’anglais, mais le chinois est en croissance
* Certains éditeurs se spécialisent dans des niches (ex : stratégie, simulation)
* Windows reste la plateforme incontournable, Mac/Linux restent marginaux mais certains genres (indie, puzzle) y sont mieux représentés

---

## 🚀 Recommandations pour Ubisoft

* Miser sur des genres avec un bon ratio **qualité/critiques positives** (RPG, Strategy)
* Renforcer la **présence multilingue** pour capter le marché asiatique en croissance
* Explorer les plateformes **Mac/Linux** pour se positionner sur des segments encore peu couverts
* Surveiller les tendances de sortie post-COVID pour ajuster les plans marketing

---

## 👨‍💻 Auteur

Projet réalisé dans le cadre du **Bootcamp Data Fullstack – Jedha**.
Auteur : MARC

---


