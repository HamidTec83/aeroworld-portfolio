# Projet DWFA — Drinking Water For All

## Contexte

DWFA (Drinking Water For All) est un projet de Data Visualisation réalisé sous Power BI.

L’objectif est d’analyser l’accès mondial à l’eau potable afin d’identifier les pays et régions prioritaires nécessitant des actions humanitaires.

Le projet s’appuie sur des données issues de plusieurs sources internationales :

- OMS ;
- Banque Mondiale ;
- indicateurs de stabilité politique ;
- données démographiques mondiales.

---

## Objectif métier

Le tableau de bord doit permettre de :

- mesurer l’accès à l’eau potable ;
- identifier les zones vulnérables ;
- prioriser les interventions humanitaires ;
- aider à la prise de décision stratégique.

---

## Données utilisées

Le projet fusionne plusieurs jeux de données :

### Water Access
Indicateurs d’accès à l’eau potable :

- accès basique ;
- accès sécurisé ;
- rural ;
- urbain.

Période :

2000 — 2017

### Population

Population par pays :

2000 — 2018

### Political Stability

Indice de stabilité politique :

2000 — 2018

### Mortality WASH

Mortalité liée au manque d’eau potable :

année 2016

---

## Préparation des données

Les étapes de préparation comprennent :

- nettoyage des valeurs manquantes ;
- harmonisation des noms de pays ;
- suppression des incohérences ;
- fusion des tables ;
- création d’un modèle en étoile.

Après nettoyage :

- 194 pays retenus ;
- données cohérentes pour l’analyse globale.

---

## Architecture Power BI

Le modèle utilise un schéma en étoile avec :

- tables de faits ;
- dimensions pays ;
- dimensions année ;
- dimensions régions OMS.

Relations :

- relation 1 → plusieurs ;
- filtrage unidirectionnel.

---

## Dashboards réalisés

Le projet comporte trois vues principales :

### Vue mondiale

Elle présente :

- population mondiale ;
- accès eau basique ;
- accès eau sécurisé ;
- stabilité politique ;
- carte mondiale ;
- top 10 pays vulnérables.

### Vue régionale OMS

Elle permet de comparer :

- régions OMS ;
- mortalité ;
- évolution temporelle ;
- indicateurs régionaux.

### Vue nationale

Analyse détaillée par pays :

- KPI nationaux ;
- évolution temporelle ;
- comparaison rural / urbain ;
- score de priorité.

---

## KPI principaux

KPI construits :

- Population mondiale : 7.45 milliards (2016)
- Accès eau basique
- Accès eau sécurisé
- Stabilité politique
- Score priorité DWFA

---

## DAX / Calculs métier

Des mesures DAX avancées ont été développées :

- agrégations conditionnelles ;
- KPI dynamiques ;
- calculs de population ;
- score de priorité humanitaire.

Exemple :

Score priorité basé sur :

- manque d’accès sécurisé ;
- mortalité WASH ;
- instabilité politique.

---

## Valeur ajoutée

Ce projet démontre mes compétences en :

- Power BI ;
- modélisation de données ;
- DAX ;
- data storytelling ;
- analyse décisionnelle.

---

## Conclusion

DWFA illustre ma capacité à transformer des données hétérogènes en tableau de bord décisionnel orienté impact social.
