# Projet Data – Analyse d’animés

## Contexte
Une plateforme de streaming d’animés souhaite identifier rapidement des animés à forte valeur éditoriale à partir de données limitées.

## Objectif
Créer un score simple permettant de mieux mettre en avant les animés de qualité, sans se baser uniquement sur la note globale.

## Données utilisées
Le jeu de données contient :
- le nom de l’animé
- le genre
- le studio
- le nombre d’épisodes
- la note globale
- la note du meilleur épisode
- la note du pire épisode

## Méthodologie
1. Chargement et exploration des données
2. Vérification des valeurs manquantes et suppression des doublons
3. Création de nouveaux indicateurs :
   - écart entre la meilleure et la pire note
   - régularité des épisodes
   - score qualité basé sur la note globale et la régularité
4. Classement des animés selon ce score
5. Création de catégories éditoriales :
   - Chef-d’œuvre
   - Très bon mais inégal
   - Risqué
   - À éviter

## Visualisations
Des graphiques ont été réalisés pour :
- observer la distribution des notes globales
- comparer la note globale au score qualité
- visualiser la répartition des catégories éditoriales

## Résultats
L’analyse montre que la note globale seule n’est pas suffisante.
La régularité des épisodes est un critère important pour identifier des animés de forte qualité éditoriale.

## Fichiers du projet
- `projet_animes.ipynb` : notebook d’analyse
- `animes.csv` : données brutes
- `animes_clean.csv` : données nettoyées
- `slides.pdf` : présentation du projet

## Conclusion
Ce projet montre l’intérêt de combiner plusieurs critères pour prendre de meilleures décisions éditoriales.
