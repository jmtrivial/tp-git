# TP 1: prise en main de git et github

L'objectif de ces séances de travaux pratiques est d'apprendre à manipuler git en créant et en alimentant un dépôt permettant la mutualisation de vos **prises de notes de cours de master**.

Tout au long de ce TP, vous pourrez utiliser la [documentation en ligne de github](https://help.github.com/en#dotcom) pour trouver les commandes et informations nécessaires à la réalisation de cet exercice.

Vous pouvez aussi trouver [un aide-mémoire pour les commandes les plus courantes](https://training.github.com/).

**Prérequis:** chaque étudiant s'est créé un compte sur [github.com](https://github.com)


## Création des groupes

Ce TP se réalise en groupes de 3 à 4 étudiants. On souhaite que les groupes ne soient pas constitués d'étudiants issus uniquement du même parcours.

## Création d'un dépôt 

Chaque groupe réalise les étapes suivantes, en utilisant le compte d'**un seul membre du groupe**.

* se connecter au site [github.com](https://github.com) et s'identifier (sign in)
* créer un nouveau dépôt, en prenant soin:
  * de le nommer de manière explicite
  * de créer un `README.md` 
  * de choisir la licence GPLv3 ou BSD (au choix)
  * de choisir une visibilité privée
* ajouter les comptes des autres membres du groupe à ce dépôt
* chacun des autres membres valide cet ajout en se connectant à son compte depuis son poste de la salle de TP


## Configuration du git local

Installation du logiciel **Github Desktop** qui contient le logiciel **git**.
Chaque personne se connecte à son compte Github.

## Création d'une copie locale

Depuis le logiciel Github Desktop, faire une copie locale du dépôt créé précédemment avec le bouton **Clone repository**.
Choisir un dossier dans votre répertoire personnel, qui sera le dossier contenant tous les fichiers de cette série de TP.

(cela correspond à la commande `clone` du logiciel git)

## Première modification

Chaque membre du groupe:

* créé un fichier au format [markdown](https://guides.github.com/features/mastering-markdown/) dans le dossier de travail du dépôt, où il se présente, en décrivant son parcours et sa formation.
* écrit un message qui décrit l'ajout du fichier
* ajoute ce fichier à la copie locale du dépôt (`git add` puis `git commit`)
* soumet cette modification au dépôt distant (`git push`)

Pendant ou après chaque modification apportée au dépôt, vous pourriez avoir besoin de mettre à jour votre copie locale depuis le dépôt distant (`git pull`).


## Création des supports de cours 

Chaque étudiant⋅e :
* choisi un module de sa formation différent du module de gestion de projets, et différent de celui de ses camarades
* créé un dossier correspondant dans la copie de travail du dépôt
* ajoute un fichier au format markdown, contenant le titre de ce module, et le nom des intervenants
* ajoute ce fichier au dépôt local, puis le soumettre au dépôt distant
* récupère les fichiers des autres membres du groupe

## Attaque et résolution

Chaque étudiant⋅e :
* Modifie le fichier d'un⋅e autre étudiant⋅e de son groupe
* Essaie de réparer les erreurs introduites dans son fichier
