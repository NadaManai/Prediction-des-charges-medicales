# Projet d'Analyse et Modélisation des Charges Médicales

## Motivation
Afin qu'une compagnie d’assurance prospère financièrement, elle doit collecter plus de primes annuelles qu'elle n'en dépense en soins médicaux pour ses bénéficiaires. En conséquence, les assureurs investissent beaucoup de temps et d'argent pour développer des modèles permettant de prédire avec précision les dépenses médicales. Ce projet a pour objectif de construire un modèle de régression pour prédire les charges médicales d'une personne et déterminer les variables les plus influentes.

## Objectifs et Méthodologie
L'objectif principal est de construire un modèle de régression précis. Les techniques de modélisation utilisées incluent la régression linéaire classique, la régression pénalisée (crête & lasso), et la régression en composantes principales.


## Présentation des Données
Pour cette analyse, nous utiliserons un ensemble de données simulées (`insurance.csv`) contenant les charges médicales des patients aux États-Unis. Les variables explicatives comprennent l'âge, le sexe, l'indice de masse corporelle (IMC), le nombre d'enfants à charge, le statut de fumeur et la région de résidence.

## Travail effectué

### Partie 1 : Exploration des Données
1. **Pré-traitement :**
   - Importation des données.
   - Traitement des valeurs manquantes et aberrantes.

2. **Analyse univariée :**
   - Étude de la distribution des variables quantitatives.
   - Étude des modalités des variables qualitatives.

3. **Analyse bivariée :**
   - Corrélation entre les variables quantitatives.
   - Dépendance de la variable cible par chacune des variables qualitatives.
   - Tests statistiques pour étudier la dépendance et l'interaction entre certaines variables qualitatives.

### Partie 2 : Modèles Linéaires
1. **Régression linéaire multiple :**
   - Construction d'un modèle linéaire et explication de la sélection des variables.
   - Diagnostic graphique du modèle développé et évaluation de sa performance.

2. **Régression linéaire améliorée :**
   - Construction d'un modèle amélioré avec des considérations non linéaires, variables binaires et interactions.
   - Évaluation et comparaison avec le modèle précédent.

3. **Régression pénalisée :**
   - Étude bibliographique sur la régression linéaire pénalisée.
   - Mise en œuvre de la régression pénalisée (ridge & lasso) et interprétation des résultats.

### Partie 3 : Analyse Multidimensionnelle
1. **Analyse en composantes principales :**
   - Étude bibliographique sur l'analyse en composantes principales.
   - Réduction de la dimension de la base de données.
   - Construction d'un modèle linéaire avec les variables résultantes.

2. **Comparaison des Modèles :**
   - Étude comparative entre les trois modèles développés.

