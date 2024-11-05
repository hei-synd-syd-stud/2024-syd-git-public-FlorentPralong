# Answers of Florent Pralong FlorentPralong

## Basics

### Task 1

Il contient tout d'abord le fichier answers.md qui vas contenir les différentes réponses durant ce laboratoire. Il y a ensuite 2 dossiers : le premier (img), contient les images qui sont / seront contenues dans le fichier answers.md. Et le deuxième (.git) sert à enregistrer l'historique de toutes les validations et toutes les autres informations requises pour le fonctionnement de git comme le contrôle des versions.

### Task 2

La commande "git status"  nous dit qu'un nouveau fichier a été ajouté et que le fichier answers.md a été modifié. Il nous dit aussi que les deux modifications n'ont pas été ajoutées a un commit. 

La commande "git log --oneline" n'a pas changé car il indique le status des commits. Et comme les modifications ne font pas partie d'un commit, il n'y a pas de différences. 

### Task 3

Le status du fichier README.md a changé, il est passé en "new file". Et answers.md est toujours en "not staged for commit".

### Task 4

On a maintenant les deux fichiers dans la catégorie "not staged for commit". Mais le fichier README.md n'est toujours pas créer sur le git local, il est donc toujours indiqué comme étant un nouveau fichier.

### Task 5

La première chaîne de caractères correspond à l'identifiant du commit. Ce qui est entre les parathèse signifie que le HEAD (pointeur désignant l'endroit où le prochain commit doit être effectué) est sur la branche main (branche principale du repo). Et finalement, on trouve après les parathèses, le nom du commit donné par l'utilisateur.

### Task 6

Les fichiers sont revenus dans leur état lors du commit initial. Puis lorsque la commande "git checkout main" a été effectuée, l'état au dernier commit a été retrouvé.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)