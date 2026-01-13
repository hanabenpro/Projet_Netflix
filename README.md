# 🎬 Netflix Catalogue Analytics

Présentation 

Ce projet propose une analyse complète du catalogue Netflix, depuis l’exploration des données jusqu’à la visualisation interactive, dans une logique proche des standards BI en entreprise.

L’objectif est de transformer des données brutes issues de Kaggle en insights exploitables, à travers :

Une EDA en Python
Une modélisation analytique
Un dashboard Power BI structuré et interactif


## Problématique

la diversité et la structure du catalogue Netflix ?
l’évolution des contenus dans le temps ?
la performance des films et séries (scores, revenus, budgets) ?
les collaborations clés entre acteurs et réalisateurs ?

## 📊 Données utilisées

Source & Format : Kaggle / CSV
Jeux de données :
netflix_titles.csv → catalogue, genres, pays, casting
imdb.csv → scores, budgets, revenus

## 📅 Couverture mondiale
 Période analysée : 2011 – 2021

## 🧠 Approche analytique
-Exploratory Data Analysis (Python)
-Nettoyage des données
-Gestion des valeurs manquantes
-Analyse descriptive
-Validation des hypothèses

### Stack : Python, Pandas, Matplotlib / Seaborn

## 2️⃣ Modélisation & préparation BI

- Structuration des données (logique facts / dimensions)
- Agrégations et calculs analytiques
- Préparation orientée visualisation
- Versioning du projet avec Git/GitHub

## 3️⃣ Visualisation – Power BI
Création d’un dashboard multi-pages permettant :
  une lecture synthétique (KPI)
  une exploration détaillée
  une analyse dynamique via filtres et slicers

## 📈 Contenu du dashboard
Vue d’ensemble
  -Volume total de contenus
  -Répartition Movies / TV Shows
  -Pays producteurs
  -Genres dominants
  -Score moyen du catalogue

Catalogue & popularité
  -Top films les mieux notés
  -Scores par genre
  -Part de contenus à fort score

Géographie & diversité
  -Carte mondiale des productions
  -Volume par pays
  -Genre dominant par pays
  -Part de production non américaine
  
Temporalité
  -Évolution du catalogue
  -Arrivée des séries
  -Périodes de forte activité
  -Durée moyenne vs score moyen

Analyse réseau (Acteurs / Réalisateurs)
  -Top acteurs et réalisateurs
  -Collaborations récurrentes
  -Heatmap acteur ↔ réalisateur

Budget & performance
  -Revenus vs budgets
  -Analyse par genre et par année
  -Corrélation budget / revenu / score

Technologies
  -Python (EDA)
  -Power BI (modélisation & visualisation)
  -Git & GitHub (versioning)
  -CSV – Kaggle datasets

## 🚀 Résultats clés

  -Forte diversité géographique, malgré une domination américaine
  -Les dramas, comédies et films d’action structurent le catalogue
  -Des collaborations acteur–réalisateur récurrentes émergent
  -Un budget élevé n’implique pas systématiquement un meilleur score
  -Accélération notable de la production de séries dans le temps

## 💼 Ce que démontre ce projet

✔ Capacité à mener une analyse data de bout en bout
✔ Maîtrise de l’EDA Python
✔ Compréhension des logiques BI et analytiques
✔ Création de dashboards clairs et orientés décision
✔ Utilisation professionnelle de Git/GitHub

##  Pistes d’amélioration

* Automatisation des pipelines (SQL / ETL)
* Enrichissement avec des données temps réel
* Analyse de la rétention et de l’engagement utilisateur
* Déploiement cloud 
