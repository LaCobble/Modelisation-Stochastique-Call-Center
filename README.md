# **Analyse des Appels Téléphoniques**

## Description du Projet
_L'objectif de ce projet est d'analyser les appels effectués dans un centre d'appels, en se concentrant sur plusieurs aspects :_

*Pour des raisons de confidentialité, les ensembles de données ne seront pas disponibles sur ce dépôt.*

- étudier l'influence du jour de la semaine et de l'heure de la journée sur les résultats des appels
- évaluer la durée des appels et son effet sur le succès de ceux-ci
- et comprendre les tendances globales des appels pour améliorer les stratégies de suivi et d'engagement des leads.

Nous disposons de plusieurs ensembles de données (calls_a1.csv, calls_a2.csv, calls_a3.csv, calls_a4.csv), chacun contenant des informations sur les appels passés à différents moments.

## Modèles Réalisés

1. Analyse de l'Impact du Changement d'Appelant
Problème : Évaluer si le fait de changer d'appelant entre le premier et le second appel a un impact positif ou négatif sur la probabilité que le lead réponde.
Méthode : Calcul des probabilités de succès en fonction du changement d'appelant.

2. Analyse de l'Influence du Jour et de l'Heure
Problème : Identifier les jours et les heures où les appels sont les plus susceptibles de réussir.
Méthode : Agrégation et visualisation des taux de réponse par jour de la semaine et par heure de la journée.

3. Analyse de la Durée des Appels
Problème : Déterminer si la durée des appels a une corrélation avec leur succès.
Méthode : Calcul et comparaison des durées moyennes des appels réussis et échoués.

## Tutoriel : Reproduire l'Analyse
Prérequis
```
Python 3.x
Pandas
Matplotlib
```

### Étape 1 : Installation des Bibliothèques
```
pip install pandas matplotlib
```

### Étape 2 : Préparation des Données
Assurez-vous que les fichiers calls_a1.csv, calls_a2.csv, calls_a3.csv, et calls_a4.csv sont dans le bon répertoire.

## Performances Obtenues

1. Impact du Changement d'Appelant

  Les résultats ont montré que le changement d'appelant peut avoir un effet significatif sur la probabilité de réponse d'un lead. En moyenne, les leads qui ont été rappelés par un autre appelant avaient une probabilité de réponse plus élevée que ceux rappelés par le même appelant.

2. Influence du Jour et de l'Heure

  L'analyse a révélé que les appels effectués certains jours de la semaine et à certaines heures avaient des taux de succès significativement différents.

3. Durée des Appels

  Les appels plus longs avaient tendance à être plus souvent couronnés de succès. Les appels réussis avaient une durée moyenne supérieure à celle des appels non réussis.

## Conclusion sur l'Intérêt Métier et Recommandations Stratégiques

Optimisation des Ressources Humaines : Changer l'appelant pour les rappels peut être une stratégie efficace pour augmenter le taux de réponse des leads.

Planification des Appels : Planifier les appels aux jours et heures identifiés comme les plus propices au succès peut améliorer l'efficacité des équipes de vente.

Formation des Appelants : Former les agents pour qu'ils prolongent les appels pourrait augmenter les chances de succès.

### Impact Potentiel

Augmentation des Taux de Conversion : En appliquant les recommandations, le centre d'appels peut voir une augmentation des taux de conversion des leads.

Amélioration de la Satisfaction Client : En contactant les leads à des moments opportuns et avec des appels plus engageants, la satisfaction client pourrait s'améliorer.

###  En résumé,
cette étude fournit des insights précieux sur les meilleures pratiques pour les appels de suivi, ce qui peut directement contribuer à une meilleure performance commerciale et une utilisation plus efficace des ressources. Les visualisations fournies offrent une vue d'ensemble claire de l'impact potentiel des changements de stratégie, permettant de mieux comprendre comment l'heure, la date, ou le nombre de tentatives peuvent influencer les taux de réponse.