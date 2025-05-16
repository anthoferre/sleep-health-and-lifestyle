# Sommeil et style de vie

**Vue d'ensemble :**

Ce jeu de données fournit des informations détaillées sur les habitudes de sommeil, les habitudes quotidiennes et les facteurs de style de vie des individus. Il comprend des mesures essentielles telles que la durée du sommeil, la qualité du sommeil, les niveaux d'activité physique, le stress, la catégorie IMC, la santé cardiovasculaire et la présence de troubles du sommeil.

**Principales caractéristiques :**

- Mesures complètes du sommeil : Explorez la durée du sommeil, la qualité et les facteurs influençant les habitudes de sommeil.
- Facteurs de style de vie : Analysez les niveaux d'activité physique, les niveaux de stress et les catégories d'IMC.
- Santé cardiovasculaire : Examinez les mesures de la pression artérielle et de la fréquence cardiaque.
- Analyse des troubles du sommeil : Identifiez l'occurrence de troubles du sommeil tels que l'insomnie et l'apnée du sommeil.

**Colonnes du jeu de données :**

- Person ID : Un identifiant pour chaque individu.
- Gender : Le sexe de la personne (Male/Female).
- Age : L'âge de la personne en années.
- Occupation : La profession de la personne.
- Sleep Duration (hours) : Le nombre d'heures que la personne dort par jour.
- Quality of Sleep (scale: 1-10) : Une évaluation subjective de la qualité du sommeil, allant de 1 à 10.
- Physical Activity Level (minutes/day) : Le nombre de minutes que la personne consacre à l'activité physique quotidiennement.
- Stress Level (scale: 1-10) : Une évaluation subjective du niveau de stress ressenti par la personne, allant de 1 à 10.
- BMI Category : La catégorie d'IMC de la personne (par exemple, Insuffisance pondérale, Normal, Surpoids).
- Blood Pressure (systolic/diastolic) : La mesure de la pression artérielle de la personne, indiquée comme la pression systolique sur la pression diastolique.
- Heart Rate (bpm): La fréquence cardiaque au repos de la personne en battements par minute.
- Daily Steps : Le nombre de pas que la personne fait par jour.
- Sleep Disorder : La présence ou l'absence d'un trouble du sommeil chez la personne (None, Insomnia, Sleep Apnea).

**Utilisations potentielles :**

*Analyse Exploratoire des Données (EDA) Avancée :*

- Identifier les distributions, les valeurs aberrantes et les relations entre les variables à l'aide de visualisations et de statistiques descriptives.
- Explorer les corrélations entre la durée et la qualité du sommeil et d'autres facteurs tels que l'activité physique, le stress et l'IMC.
- Examiner la distribution des troubles du sommeil au sein de différentes populations (par âge, sexe, profession).
- Analyser la relation entre la pression artérielle, la fréquence cardiaque et les habitudes de sommeil.

*Ingénierie des Fonctionnalités :*

- Créer de nouvelles fonctionnalités pertinentes à partir des colonnes existantes (par exemple, un indice de qualité du sommeil combiné, des catégories d'activité physique).
- Gérer les valeurs manquantes et les valeurs aberrantes à l'aide de techniques appropriées.
- Envisager des transformations de variables pour améliorer les performances des modèles.

*Modélisation Prédictive :*

- Développer des modèles de classification pour prédire la présence de troubles du sommeil (insomnie, apnée du sommeil).
- Construire des modèles de régression pour prédire la durée et la qualité du sommeil en fonction des facteurs de style de vie.
    
*Segmentation et Clustering :*

- Identifier des groupes distincts d'individus en fonction de leurs habitudes de sommeil et de leur style de vie
