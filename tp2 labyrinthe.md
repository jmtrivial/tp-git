# TP 2 : Le jeu dont vous êtes le héros

Il s’agit de réaliser un **jeu dont vous êtes le héros** en mettant à profit les **liens hypertextes**, à l’aide de documents écrits avec le **langage markdown** (fichier avec l'extension `.md`).

Dans ce jeu, la personne qui joue se retrouve à l’intérieur d'un labyrinthe, dans lequel elle peut se déplacer.
Le labyrinthe est composé de plusieurs lieux connectés entre eux. Chaque lieu est représenté par un fichier. Le passage d’un lieu à l’autre se fait grâce à des liens hypertextes.


## Partie 1

### Création des groupes

Ce TP se réalise en groupes de 3 à 5 étudiants. On souhaite que les groupes ne soient pas constitués d'étudiants issus uniquement du même parcours.

### Conception de la carte du labyrinthe
A l’aide d’un document partagé (sur Teams ou avec l'outil en ligne [ExcaliDraw](https://excalidraw.com/)), dessiner la carte secrète de votre labyrinthe, en respectant les contraintes suivantes :
    * Chacun⋅e propose 3 lieux, représentés par un cadre avec un nom de lieu, et son nom-prénom
    * Connecter les lieux entre eux. Un lieu a entre 1 et 3 passages avec d’autres lieux
    * Toutes les lieux doivent être connectées au labyrinthe
    * Le labyrinthe comporte une salle de départ nommée index.md
    * Le labyrinthe comporte une salle d’arrivée
    * Le labyrinthe comporte une salle « game-over » : uniquement un lien vers la salle de départ pour recommencer.

### Construction du labyrinthe
Un membre du groupe crée un **dépôt public** sur GitHub.com.
Ajouter les membres du groupe comme collaborateur⋅trice⋅s du projet (`Settings > Collaborators`)
Chaque membre peut cloner le dépôt sur sa machine.

Un autre membre du groupe crée un dossier **jeu-heros-nom-de-votre-labyrinthe** puis dépose dans ce dossier une image de la carte secrète du labyrinthe.
Les autres membres peuvent mettre à jour leur copie locale (avec les commandes `fetch` puis `pull`).

Chaque personne crée les fichiers qui correspondent aux lieux qu’elle a choisis. 
Chaque fichier .md correspond à un lieu, et fait apparaître :
    * nom du lieu
    * une paragraphe décrivant le lieu
    * une image
    * liens vers les autres lieux
    * nom-prénom de l’auteur⋅trice
      
Attention à ne pas oublier d'écrire des **messages de commit** !

Jouer au labyrinthe !

## Partie 2

### Objet secret

Chaque groupe choisit un **objet secret qui est caché** dans un des lieux du labyrinthe.
L’objet secret est une **image cliquable** qui renvoie vers une **salle secrète** (un nouveau lieu).
Cette salle comporte un lien renvoyant vers le lieu de départ du labyrinthe **d’une autre équipe**.

Jouer au labyrinthe !


## Partie 3 - Retour sur le TP

Où vous en êtes sur la construction du labyrinthe ?
A quoi ça peut servir dans vos projets collaboratifs ?
Quelles structure on peut donner à un dépôt partagé ?
