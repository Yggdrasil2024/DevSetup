# Git et GitHub

# 1. Git
   Git est un outil qui permet aux developpeurs de suivre les changements sur la code-base(repository) de leur projet(versionning), de capturer des moments precis au cours du projet(snapshot) pour pouvoir y revenir pour faire des experimentations ou autres complications pouvant etre lié à des bugs au autre.
   L'outil à été developper par Linus Torvald en 2005 et s'est imposer comment un standard d'industrie, un indispensable dans le domaine du developpement.
# 2. GitHub
   il s'agit d'un de collaboration en ligne permettant aux developpeurs ou aux entreprises de mettre en ligne le code de leur different projects afin que les contributeurs(les autres utilisateurs de github) ou des employé de l'entreprise de collaborer des projets.
   il est sortie le 10 Avril 2008, crée par par ses fondateurs Chris Wanstrath, Tom Preston-Werner et PJ Hyett. il vient vraiment ajouter l'aspect communautaire et social à l'experience du versionning avec Git.

# 3. les bases de Git

comme tout domaine, le versionning avec Git a sont B-A-BA

## Creation d'un repository local

pour creer un repository avec git et commencer à tracer son code il faut se placer à la racine de notre projet au sein d'un terminal et lancer la commande suivante:
git init
cela va cree un dossier caché .git qui contient tout le necessaire de fonctionnement de Git au sein du projet.

## Configuration des information utilisateur

Avant de pouvoir tracker prendre des snapshots de notre projet il est important de faire savoir à Git qui nous somme nous l'auteur du projet en donnant notre nom ou pseudo puis notre addresse email. ces informations sont celles de notre compte GitHub de preference.
voici les commandes pour cette manipulation:
```bash
git config --global user.name "nom ou pseudo"
```
```bash
git config --global user.email "addresse email"
```

## Voir l'etat du suivis de nos fichier

il peut etre pertinent de savoir quel informations ou modifications seront enregistrée au moment du prochain snapshot(commit) pour cela on utilise la commande:

```bash
git status
```

les fichiers en rouges sont ceux qui ne seront pas commités et il faudra y remedier.

## Ajouter nos modification dans la staging area:

la commande pour cela est :

```bash
git add nom_du_fichier
```
mais
```
git add .
```

est plus simple car il ajouter tous les fichiers nom suivis dans la staging zone en une seule fois.

## Enregistrer nos modifications

maintenant que toutes les modifitions de notre fichier sont dans la zone d'attente ou staging area on va les enregistrer en utilisant la commande:

```bash
git commit - m "message sur le pourquoi des modifictions"
```
## ajouter un repos distant:
tout l'interet de l'association git - gitHub reside dans la possibilité de pouvoir herberger notre projet dans une platerforme distante. pour cela il faut d'abord creer un repo dans GitHub puis copier sont lien ensuite revenir en local et lancer la commande suivante:

```bash
git remote add origin lien_du_repo
```
maintenant que le vers le depos en ligne est connu par git on peut aussi poussé le code en ligne pour le sauvegarder hors de notre environnement local via
```bash
git push
```
# 4. Notion avancée branching

il faut s'avoir que sur git l'on enregistre notre code sur des ce qu'on appele des branchs c-a-d des sortes de chemins paralleles de developpement. cela est très utile en collaboration pour developper, experimenté ou faire des reparations sur le projet sans avoir à s'inquiter de "casser" le projet principale qui est la branch "main" la branch principale et la branch par defaut.

## creer et aller vers une autre branch
```bash
git switch -c "nom_branch"
```
permert d'aller vers une nouvelle branch en la creant en meme moment. on peut pousser cette branch sur le repo distant via la commande suivant lors du premier push sur celle ci:
```bash
git push --set-upstream origin nom_branch
```
ou en plus court:
```bash
git push -u origin nom_branch
```


# 5. Ressources complementaires

1. Apprendre Git de facons interactive
https://learngitbranching.js.org/

2. tuto sur git
https://youtu.be/8JJ101D3knE?si=BQPsGlF4GJonXdSU

3. Se familiariser avec GitHub
https://youtu.be/a9u2yZvsqHA?si=vA0I9S722STK8Syn