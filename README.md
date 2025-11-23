#  Analyse du Titanic — Projet Python  
_Un projet humain, analytique et orienté data._

##  À propos du projet
Ce projet propose une exploration pédagogique mais profondément humaine du jeu de données du **Titanic**, l’un des plus emblématiques de l’histoire de la data science.  
À partir de simples listes Python (âge, sexe, survie, nom), l’objectif était de reconstruire des analyses significatives :

- Qui avait le plus de chances de survivre ?
- Le sexe influençait-il réellement le destin des passagers ?
- L’âge a-t-il joué un rôle décisif ?
- Comment raconter une histoire uniquement à partir de données brutes ?

Sans utiliser aucune bibliothèque externe, ce projet revient aux fondations mêmes de la programmation :  
**boucles, conditions, fonctions, logique et observation.**

---

##  Objectifs pédagogiques
Le but était d’apprendre à :
- Manipuler des **listes synchronisées** contenant plusieurs centaines d’entrées ;
- Développer des **fonctions paramétrées** capables d’extraire des indicateurs ;
- Effectuer des calculs statistiques simples (taux de survie) ;
- Structurer proprement un projet Python ;
- Interpréter les résultats avec une approche analytique et humaine.

---

##  Ce que le projet analyse

###  1. Taux de survie selon le sexe  
Comment la survie diffère-t-elle entre les hommes et les femmes ?  
Historiquement, le protocole “**Women and children first**” est associé au Titanic.  
L’analyse permet de vérifier si cette règle a réellement été appliquée.

###  2. Taux de survie selon la tranche d’âge  
Les enfants ont-ils été sauvés en priorité ?  
Les jeunes adultes ont-ils eu moins de chance ?  
Les seniors étaient-ils plus vulnérables ?

Une fonction permet d’examiner n’importe quelle tranche d’âge.

---

##  Structure du projet

Le projet utilise des listes Python extraites depuis des données historiques :

- `survived[]` : 0 = décédé, 1 = survivant  
- `age[]` : âge réel (incluant enfants, adultes, personnes âgées)  
- `name[]` : nom complet du passager  
- `sexe[]` : `male` ou `female`

Toutes les listes ont la même longueur :  
chaque indice correspond au même passager.

---

##  Technologies utilisées
Même si le sujet est centré sur la data science, l’objectif était de se limiter volontairement à :

- **Python natif**
- **Boucles**
- **Conditions**
- **Fonctions**
- **Opérations statistiques simples**

Aucune librairie comme Pandas ou NumPy n’a été utilisée — pour bien comprendre la mécanique des données.

---

##  Résultats (interprétation humaine)
Sans dévoiler les calculs exacts ici, les tendances attendues et confirmées sont :

###  Survie et sexe
Les femmes ont eu un taux de survie nettement plus élevé que les hommes.  
Une réalité douloureuse, mais cohérente avec les priorités d’évacuation.

### Survie et âge
- Les très jeunes enfants ont souvent survécu en plus grand nombre.  
- Les adultes jeunes (18–30 ans) présentent un taux variable selon leur classe sociale.  
- Les personnes âgées ont été les plus vulnérables.

Derrière chaque ligne de données, il y a une histoire — le projet encourage ce regard humain.

---

## Compétences démontrées
Ce projet met en lumière des compétences précieuses :

###  Compétences techniques
- Manipulation de données brutes
- Construction de fonctions robustes
- Gestion de structures synchronisées
- Implémentation de filtres et agrégations

###  Compétences analytiques
- Interprétation statistique
- Construction d’indicateurs (taux de survie)
- Analyse croisée (âge ↔ sexe ↔ survie)

###  Compétences professionnelles
- Rédaction propre et structurée
- Pensée algorithmique claire
- Sensibilité humaine dans l’analyse de données

---

##  Fichiers du projet

- `Code_projet_analyse_titanic.pdf`  
  Contient les données brutes et le code initial du projet.

- `analyse.py` *(si vous ajoutez votre script)*  
  Contient l’implémentation des fonctions d’analyse.

- `README.md`  
  Vous êtes en train de le lire 

---

##  Contribution

Les améliorations possibles incluent :
- Migration du projet vers Pandas
- Création de visualisations (Matplotlib ou Seaborn)
- Ajout d’un tableau interactif
- Analyse par classe sociale (1st, 2nd, 3rd class)

Les contributions sont les bienvenues 

---

## Mot de fin

Ce projet est une belle manière de montrer que **la data science ne sert pas qu’à manipuler des chiffres : elle permet aussi de raconter des histoires.**  
Même avec des outils simples, il est possible d’obtenir des analyses pertinentes, humaines et riches de sens.

Merci d’avoir pris le temps d’explorer ce travail 
N’hésitez pas à laisser un commentaire ou une étoile  sur le dépôt si vous appréciez l’effort.


