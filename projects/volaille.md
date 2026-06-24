# Projet Étude de marché volaille — Analyse de marchés internationaux

## Contexte

Ce projet consiste à réaliser une étude de marché internationale afin d’identifier les pays les plus attractifs pour développer l’exportation de produits de volaille.

L’analyse combine des données économiques, démographiques et de consommation alimentaire.

Sources utilisées :

- FAO
- Banque Mondiale
- World Governance Indicators

---

## Objectif métier

L’étude vise à :

- identifier les marchés porteurs ;
- mesurer le potentiel commercial ;
- évaluer les risques pays ;
- prioriser les pays cibles.

---

## Données utilisées

Les datasets contiennent :

### Données FAO

- production
- importations
- exportations
- disponibilité alimentaire
- consommation

### Données économiques

- PIB par habitant
- stabilité politique

### Données démographiques

- population totale

Année étudiée :

2017

---

## Préparation des données

Les étapes de nettoyage :

- suppression des valeurs manquantes ;
- harmonisation des pays ;
- fusion des datasets ;
- standardisation des variables.

Résultat :

- 135 pays retenus ;
- couverture population mondiale : 88.69 %

---

## Analyse exploratoire

L’analyse exploratoire a permis de :

- comprendre la distribution des variables ;
- détecter les corrélations ;
- identifier les indicateurs discriminants.

Variables importantes :

- importations par habitant
- consommation
- PIB par habitant
- stabilité politique
- population

---

## Réduction dimensionnelle (ACP)

Une Analyse en Composantes Principales (ACP) a été réalisée afin de :

- réduire la dimension ;
- limiter la redondance ;
- faciliter le clustering.

L’ACP met en évidence plusieurs axes expliquant la majorité de la variance.

---

## Segmentation de marché

Deux méthodes de clustering ont été utilisées :

### CAH

Clustering hiérarchique pour déterminer le nombre optimal de groupes.

### KMeans

Segmentation finale des pays selon leur attractivité marché.

Nombre de clusters retenu :

5 clusters

---

## Scoring métier

Un score d’attractivité corrigé a été construit.

Variables pondérées :

- PIB par habitant : 20 %
- stabilité : 15 %
- importations / habitant : 20 %
- dépendance importation : 20 %
- consommation : 10 %
- population : 15 %

Ce score permet de classer les marchés les plus attractifs.

---

## Résultats

Le projet permet de :

- classer les pays par attractivité ;
- identifier les marchés prioritaires ;
- différencier marchés matures et émergents.

---

## Valeur ajoutée

Ce projet démontre mes compétences en :

- analyse exploratoire ;
- statistiques multivariées ;
- clustering ;
- scoring décisionnel ;
- recommandation business.

---

## Conclusion

Cette étude montre ma capacité à transformer des données complexes en recommandations stratégiques orientées business.
