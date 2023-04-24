# 🎰 Projet Connect4 Agent 
Projet pour le cours de Reinforcement Learning à CentraleSupélec. 

## 🎯 Objectif
L'objectif du projet consiste à développer un agent pour Connect4, tel qu'il est implémenté dans la bibliothèque PettingZoo, en utilisant des méthodes d'apprentissage par renforcement.

## 🤔 Choix techniques
Nous avons choisi d'implémenter une version du Deep Q-Network (DQN), qui est une méthode d'apprentissage par renforcement basée sur les réseaux de neurones profonds. 

Nous avons également décidé d'établir un plateau de jeu pour qu'il soit assez flexible sur le choix des joueurs contre lequel l'agent joue. Deux joueurs sont proposés pour jouer contre l'agent: un joueur random et un joueur humain.

Une comparaison et une amélioration des performances du modèle DQN par rapport aux agents basés sur des règlés ont été mises en oeuvre, et des tests sur d'autres architectures de Reinforcement Learning ont été également été effectués.

## :card_index_dividers: Segmentation
Notre répertoire est segmenté en 2 jupyter notebooks, deux fichiers markdown, un fichier .gitinore et un fichier texte pour les requirements :

```bash 
.
├── README.md
├── CONTRIBUTING.md
├── .gitignore
├── requirements.txt 
├── project.ipynb
└── project_seongwoo.ipynb

```

- ``README.md`` contient l'ensemble des informations sur le projet pour pouvoir l'installer.
- ``CONTRIBUTING.md`` contient l'ensemble des informations sur les normes et les pratiques de collaboration et de gestion du projet.
- ``.gitignore`` contient les fichiers qui doivent être ignorés lors de l'ajout de fichiers au dépôt Git.
- ``requirements.txt`` contient la liste des modules et des bibliothèques Python qui doivent être installés, ainsi que leur version spécifique.
- ``project.ipynb`` est le notebook de notre projet qui permet d'implémenter notre agent DQN sur un plateau de jeu. Notre agent peut soit jouer contre un joueur random soit un joueur humain qui a chaque tour entre son choix via une fonction de saisie.
- ``project_seongwoo.ipynb`` est une copie du notebook ``project.ipynb`` pour permettre à Seong Woo Ahn de comparer et d’améliorer les performances du modèle de Rodolphe par rapport aux agents basés sur des règles.


## :wrench: Installation
Pour lancer, nous vous recommandons sur un terminal uniquement :

1. Tout d'abord, assurez-vous que vous avez installé une version `python` supérieure à 3.9 et `Anaconda` ou `Miniconda`. 

2. Pour cloner le répertoire, choisissez l’emplacement où vous souhaitez accéder au répertoire sur votre ordinateur, en tapant la commande suivante sur votre Terminal :
```bash
cd desktop # affichera sur votre Bureau d'ordinateur 
git clone https://gitlab-student.centralesupelec.fr/albane.michot/Projet_RL.git
cd Projet_RL
```

3. Nous vous conseillons un environnement conda avec la commande suivante qui permet d'installer directement les `requirements` sur l'environnment créé : 
```bash
conda create --name connect4 --file requirements.txt
```
- Pour activer l'environnement :
```bash
conda activate connect4
```

Exécuter ensuite les notebooks jupyter dans l'ordre suivant : 

1. project.ipynb
2. project_seongwoo.ipynb

## :pencil2: Auteurs
- AHN Seong Woo
- MICHOT Albane
- NONCLERCQ Rodolphe
- LETOURNEUR Ladislas



