# Weather_data_analysis
Analyse Météorologique des Départements de Creuse et Isère
Description
Ce projet effectue une analyse des données météorologiques pour les départements de Creuse et Isère en France. L'objectif principal est d'explorer les mesures d'humidité, l'altitude des stations météorologiques, et les précipitations en fonction des saisons et des mois de l'année. Les résultats incluent des statistiques descriptives et des visualisations graphiques qui permettent d'interroger des hypothèses sur les variations climatiques entre ces deux départements.

Contenu du Projet
Données Météorologiques: Les données sont contenues dans un fichier CSV (meteo.csv) qui inclut des mesures d'humidité, d'altitude, et de précipitations pour différentes stations météo.
Script R Markdown: Le fichier weather_data_analysis.Rmd contient le code pour l'analyse des données et génère un rapport au format HTML (weather_data_analysis.nb.html), qui présente les résultats de l'analyse.
Analyses Réalisées
Statistiques Descriptives:

Nombre de mesures d'humidité pour chaque département.
Calcul de l'humidité moyenne et de l'écart-type pour chaque département et saison.
Comparaison des données de Creuse et Isère à l'aide de tests statistiques (test de Wilcoxon pour la latitude, etc.).
Visualisations:

Boxplots des latitudes des stations météorologiques pour comparer Creuse et Isère.
Histogrammes et QQ-plots pour évaluer la normalité des données.
Tests Statistiques:

Test de Wilcoxon pour évaluer les différences de latitude entre les départements.
Analyse de régression pour déterminer l'effet du mois sur les précipitations.
Instructions pour l'Utilisation
Installation des Packages R: Assurez-vous d'avoir installé les packages nécessaires, notamment ggplot2 pour la visualisation.

R
Copier le code
install.packages("ggplot2")
Chargement des Données: Le fichier meteo.csv doit être présent dans le même répertoire que le script R pour charger correctement les données.

R
Copier le code
fa <- read.csv("meteo.csv")
Exécution de l'Analyse: Ouvrez le fichier weather_data_analysis.Rmd dans RStudio et exécutez les chunks de code pour générer le rapport HTML.

Conclusion
Ce projet permet de mieux comprendre les variations climatiques dans les départements de Creuse et Isère, et les résultats pourraient être utiles pour des études futures ou des décisions basées sur des données climatiques.
