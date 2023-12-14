<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projet d'Analyse et Modélisation des Charges Médicales</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 20px;
            color: #333;
        }

        h1 {
            color: #2c3e50;
            display: flex;
            align-items: center;
        }

        h1 i {
            margin-right: 10px;
            color: #3498db;
        }

        h2 {
            color: #2c3e50;
        }

        p {
            color: #555;
        }

        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            font-family: 'Courier New', monospace;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin-bottom: 8px;
        }

        i {
            margin-right: 8px;
            color: #3498db;
        }
    </style>
</head>
<body>

    <h1><i class="fas fa-project-diagram"></i> Projet d'Analyse et Modélisation des Charges Médicales</h1>

    <p>This README provides information about the project and how to use it.</p>

    <h2><i class="fas fa-bullseye"></i> Objectifs et Méthodologie</h2>

    <p>L'objectif principal est de construire un modèle de régression précis. Les techniques de modélisation utilisées incluent la régression linéaire classique, la régression pénalisée (crête & lasso), et la régression en composantes principales.</p>

    <h2><i class="fas fa-cogs"></i> Livrables</h2>

    <ul>
        <li><i class="fas fa-code"></i> Un script R.</li>
        <li><i class="fas fa-file-powerpoint"></i> Une présentation.</li>
    </ul>

    <h2><i class="fas fa-database"></i> Présentation des Données</h2>

    <p>Pour cette analyse, nous utiliserons un ensemble de données simulées (`insurance.csv`) contenant les charges médicales des patients aux États-Unis. Les variables explicatives comprennent l'âge, le sexe, l'indice de masse corporelle (IMC), le nombre d'enfants à charge, le statut de fumeur et la région de résidence.</p>

    <h2><i class="fas fa-tasks"></i> Travail Demandé</h2>

    <h3>Partie 1 : Exploration des Données</h3>

    <ol>
        <li><i class="fas fa-cogs"></i> **Pré-traitement :**
            - Importation des données (présentation et résumé statistique).
            - Traitement des valeurs manquantes et aberrantes.
        </li>

        <li><i class="fas fa-chart-bar"></i> **Analyse univariée :**
            - Étude de la distribution des variables quantitatives.
            - Étude des modalités des variables qualitatives.
        </li>

        <li><i class="fas fa-chart-area"></i> **Analyse bivariée :**
            - Corrélation entre les variables quantitatives.
            - Dépendance de la variable cible par chacune des variables qualitatives.
            - Tests statistiques pour étudier la dépendance et l'interaction entre certaines variables qualitatives.
        </li>
    </ol>

    <h3>Partie 2 : Modèles Linéaires</h3>

    <ol>
        <li><i class="fas fa-calculator"></i> **Régression linéaire multiple :**
            - Construction d'un modèle linéaire et explication de la sélection des variables.
            - Diagnostic graphique du modèle développé et évaluation de sa performance.
        </li>

        <li><i class="fas fa-chart-line"></i> **Régression linéaire améliorée :**
            - Construction d'un modèle amélioré avec des considérations non linéaires, variables binaires et interactions.
            - Évaluation et comparaison avec le modèle précédent.
        </li>

        <li><i class="fas fa-sliders-h"></i> **Régression pénalisée :**
            - Étude bibliographique sur la régression linéaire pénalisée.
            - Mise en œuvre de la régression pénalisée (ridge & lasso) et interprétation des résultats.
        </li>
    </ol>

    <h3>Partie 3 : Analyse Multidimensionnelle</h3>

    <ol>
        <li><i class="fas fa-cogs"></i> **Analyse en composantes principales :**
            - Étude bibliographique sur l'analyse en composantes principales.
            - Réduction de la dimension de la base de données.
            - Construction d'un modèle linéaire avec les variables résultantes.
        </li>

        <li><i class="fas fa-chart-pie"></i> **Comparaison des Modèles :**
            - Étude comparative entre les trois modèles développés.
        </li>
    </ol>

    <p><strong>Note :</strong> Veuillez vous référer au script R pour les détails de mise en œuvre et aux graphiques pour les résultats obtenus.</p>

</body>
</html>
