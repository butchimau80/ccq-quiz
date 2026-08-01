# Banque de questions CCQ

Application HTML autonome pour réviser une banque de questions CCQ.

## Statistiques du nettoyage

- Questions initiales : **480**
- Doublons supprimés : **130**
- Questions restantes : **350**
- Doublons avec options ou réponse différentes : **69**

## Utilisation

Ouvrez simplement `index.html` dans un navigateur moderne. Aucune installation n'est nécessaire.

## Fichiers

- `index.html` : application complète.
- `questions.json` : banque nettoyée.
- `duplicates_removed.json` / `.csv` : rapport des doublons supprimés.

## Méthode de déduplication

Les questions sont comparées après normalisation des espaces, de la casse, des guillemets typographiques et de la ponctuation finale. La première occurrence est conservée.
