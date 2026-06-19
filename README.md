# Analyse des offres d'emploi en France (ST2MLE)

Projet ML sur donnees mixtes (numeriques + textuelles) issues de l'API France Travail.

## Objectifs de modelisation
- **Numerique** : predire le **salaire** (regression : Decision Tree, Random Forest, Boosting).
- **Textuel** : predire le **metier (ROME)**, le **secteur d'activite** et le **type de contrat**
  a partir de la description (Naive Bayes, Regression Logistique) en comparant
  **BoW / TF-IDF / Doc2Vec / BERT**.

## Installation
Il faut télécharger le fichier de Data très volumineux (0.5Go), qui contient toutes les offres d'emplois, il faut ensuite le placer dans data/

