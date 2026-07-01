# DevSetup: environnement de developpement Fullstack 👾

se repository exitste dans le cadre de la cohorte 2 de la formation en developpement fullstack d'Akieni Academy.

## Table de matières

- [DevSetup: environnement de developpement Fullstack 👾](#devsetup-environnement-de-developpement-fullstack-)
  - [Table de matières](#table-de-matières)
  - [Description du projet 📖](#description-du-projet-)
  - [Outils configuré 💻](#outils-configuré-)
    - [Editeur de code](#editeur-de-code)
    - [Versionning software](#versionning-software)
    - [🎮 Terminal:](#-terminal)
    - [GitHub:](#github)
  - [📂 Sturctue du projet](#-sturctue-du-projet)
  - [Bonus realisé](#bonus-realisé)
  - [comment utiliser se repo](#comment-utiliser-se-repo)

## Description du projet 📖

Mise en place de l'environement de travail necessaire pour le developpement fullstack: installation d'un editeur de code, installation de Git pour le versionning, configuration d'un terminal, hosting du code avec GitHub ainsi que d'un runtime pour le javascript coté serveur.

## Outils configuré 💻

Voici les outils que j'ai eu a configurer dans mon environnement

### Editeur de code

- **Nom**: visual studio code
- **Extensions**: prettier, GitLens, Live Server, Markdown All in one
- **lien**: https://code.visualstudio.com/

### Versionning software

Git a eté installer en local via Git Bash(nom et email configurer aussi)

### 🎮 Terminal:

**Nom**: Powershell(integration au sein de VS-code)

### GitHub:

simple connexion au compte deja existant

## 📂 Sturctue du projet

Voici l'arborescence du projet:

```html
DevSetup #racine du projet ├── notes/ # Dossier contenant mes notes de la
semaine │ ├── architecture_pc_et_web.md # Fonctionnement d'un ordinateur et du
web │ ├── terminal_et_commandes.md # Guide des commandes du terminal │ └──
git_and_github.md # Concepts et commandes Git/GitHub ├── .editorconfig #
Configuration des règles de l'éditeur (Bonus) ├── .gitignore # Fichiers et
dossiers à ignorer par ├── package.json # information de base sur le projet pour
node └── README.md # Présentation du projet (ce fichier)
```

## Bonus realisé

1. ajout et configuration de `nodemon` dans le projet
2. ![alt text](image.png)
3. creation du fichier `.editorconfig`
4. creation de la branch `dev` et merging avec main

## comment utiliser se repo

Explorez se repo en local:

1. Cloner le repo:

   ```bash
   git clone https://github.com/Yggdrasil2024/DevSetup.git
   ```

2. Déplacez-vous dans le repos:
   ```bash
   cd DevSetup
   ```
3. Installer les dependances necessaire juste `nodemon` pour notre cas:
   ```bash
   npm install nodemon
   ```
4. Lancer l'environnement de developpement et:
   ```bash
   npm install nodemon
   ```

Une fois que l'environnement de developpement fonctionnel vous êtes maintenant prêt à pouvoir explorer et modifier le projet à votre sauce.
