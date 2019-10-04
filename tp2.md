# TP 2: manipuler des branches

Dans ce TP comme dans le précédent, les étudiant·e·s sont invité·e·s à utiliser la documentation pour découvrir les commandes à utiliser, afin d'être autonomes.

⚠️ Tout au long de ce TP, vous pourrez utiliser la [documentation en ligne de github](https://help.github.com/en#dotcom) pour trouver les commandes et informations nécessaires à la réalisation de cet exercice.


## Rappel du TP précédent

À l'occasion du TP 1, vous avez pu utiliser les commandes suivantes:

![configuration initale](images/git-0.png)

* `git clone [adresse github]`

![git clone](images/git-clone.png)

* `git add [fichier.md]`

![git add](images/git-add.png)


* `git commit [fichier.md]` ou `git commit -a`

![git commit](images/git-commit.png)

* `git push`

![git push](images/git-push.png)

* `git pull`

![git pull](images/git-pull.png)


## Récupération du dépôt en local

Nous avons changé de salle et de machines, il est possible que vous ayez à récupérer le dépôt sur votre poste local. Utilisez **git 
clone**.

## Création d'une branche

Chaque étudiant créé une branche de travail sur son dépôt local (`git branch`) nommé suivant un des cours de son master. Chaque groupe s'arrange pour que les étudiants du groupe n'aient pas de cours en double.

## Description du cours

Chaque étudiant créé un fichier markdown décrivant le cours qu'il a choisi, puis l'ajoute à la branche du dépôt local avec `git add`. Chaque étudiant édite le fichier README.md pour y ajouter une courte description de ce cours récemment ajouté. Ces modifications sont ajoutées au dépôt local par un `git commit`. **N'oubliez pas d'indiquer au moment du *commit* un message de description explicite de la contribution**.

## Mise en commun sur le serveur

Chaque étudiant soumet sur le dépôt distant sa branche, en une nouvelle branche distante. Vérifiez que vos branches existent bien sur le dépôt serveur de github.

## Fusion de branche

Une fois que toutes les branches sont partagées sur le serveur, chacun peut récupérer les branches des autres contributeurs avec une commande `git pull` bien choisie.

La commande `git checkout` permet de se promener parmi chacune des branches disponibles. N'hésitez pas à améliorer les contributions de vos camarades sur leurs branches.

Chacun réalise alors la fusion de sa branche sur la branche principale (`git merge`), puis soumet cette nouvelle branche principale sur le dépôt distant (`git push`).

*Il est probable que vous deviez gérer des conflits de fusion. Dans ce cas, pensez à travailler ensemble !*

## Récupération du projet complet

Une fois que toutes les fusions sont réalisées, chaque étudiant peut récupérer en local la version complète du projet (`git pull`).

## Déplacement du cours dans un dossier dédié

Chaque étudiant déplace avec git son fichier markdown dans un dossier `cours` afin de structurer le dépôt (`git mv`).

## Améliorer le contenu des notes

On peut poursuivre:

* en créant un lien hypertexte dans le fichier README.md pour chacun des cours
* en améliorant le contenu des notes de cours
* en intégrant des illustration au sein des notes
* améliorer la structure hiérarchique des dossiers, par exemple en séparant les cours par sous-dossiers correspondant aux différents master (et partie commune).

A chaque fois, n'oubliez pas de partager ces améliorations sur le dépôt du serveur.




