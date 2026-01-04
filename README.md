# 🩺 Miscarriage Prediction – Risk Factors  
### Analyse exploratoire et préparation des données

## 📌 Présentation du projet
Ce projet porte sur l’analyse des facteurs de risque associés aux **fausses couches (miscarriages)** à partir de données médicales et comportementales collectées auprès de femmes enceintes.

Il s’appuie sur le dataset **“HIBA ASRI – Miscarriage Prediction Risk Factors”**, publié le **25 mai 2021** sur la plateforme **Mendeley Data** et contribué par **Hiba Asri**.

L’objectif est de comprendre les relations entre les **variables physiologiques**, **comportementales** et la survenue de fausses couches, à travers un travail rigoureux de **prétraitement**, **nettoyage** et **analyse exploratoire des données (EDA)**.

---

## 🎯 Objectifs du projet
- Comprendre la structure et la qualité du dataset  
- Nettoyer et préparer les données pour l’analyse  
- Gérer les valeurs manquantes et les duplicatas  
- Réaliser une analyse exploratoire univariée et bivariée  
- Mettre en évidence les variables potentiellement liées au risque de fausse couche  
- Présenter les résultats de manière claire et reproductible avec **Quarto**

---

## 📊 Description du dataset
Le dataset regroupe des informations issues de plusieurs sources :

### 🔹 Capteurs de santé (IoT)
- Fréquence cardiaque (*Heart Rate*)
- Niveau de stress
- Température corporelle
- Tension artérielle

### 🔹 Téléphones mobiles
- Activité physique (marche, vélo, conduite, position assise)
- Indice de masse corporelle (IMC)
- Localisation
- Antécédents médicaux

Population étudiée : **femmes enceintes**.

---

## 🧪 Méthodologie
Le projet suit les étapes suivantes :

1. **Importation des librairies**
2. **Chargement du dataset**
3. **Exploration initiale des données**
4. **Nettoyage et prétraitement**
   - gestion des types de variables
   - traitement des valeurs manquantes
   - suppression des duplicatas
5. **Analyse exploratoire des données (EDA)**
   - variables numériques
   - variables catégorielles
6. **Visualisation et interprétation des résultats**

---

## 🛠️ Technologies et outils utilisés
- **R**
- **Quarto**
- **RStudio / VS Code**
- **Colab**
- Librairies R :
  - `tidyverse`
  - `skimr`
  - `psych`
  - `GGally`

---

## 📁 Structure du projet
```text
miscarriage-quarto/
│
├── Miscarriage_Prediction_Risk_Factors.ipynb   # Notebook principal
├── Miscarriage_Prediction_Risk_Factors.html   # Présentation Reveal.js
├── _quarto.yml                                # Configuration Quarto
├── default.qmd                                # Fichier par défaut Quarto
└── README.md   
└── slides.md                                # Description du projet

Dataset disponible ici : [Télécharger le dataset](https://drive.google.com/file/d/1awRjwGJsnR2Mmxul6WTqT_Q1PvnHA-SR/view?usp=drive_link)
