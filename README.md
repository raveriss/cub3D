# **Projet cub3D**
<div align="center">
  <img src="https://github.com/ayogun/42-project-badges/blob/main/badges/cub3dm.png?raw=true" alt="Badge du projet cub3d">
</div>

##
<div align="center">
  <img src="https://github.com/Omisev/cub3D/blob/main/cub3d_representation.webp" alt="cub3d representation">
</div>

##
<div align="center">
  <img src="https://github.com/Omisev/cub3D/blob/main/screenshot.png" alt="sreenshot">
</div>

## Description
Le projet `cub3D` vise à recréer une expérience inspirée du jeu historique Wolfenstein 3D, considéré comme le premier FPS jamais développé. Ce projet permet d'explorer les techniques de ray-casting pour générer une vue en 3D dans un labyrinthe à partir d'une carte en 2D.

## Tableau des Composants du Projet

| Dossier/Fichier      | Description                                                              | Responsabilité                                     |
|----------------------|--------------------------------------------------------------------------|----------------------------------------------------|
| `Include`            | Contient les fichiers d'en-tête.                                         | Déclarations de fonctions et structures            |
| `Lib`                | Bibliothèques nécessaires au projet.                                     | Fournit des outils externes au projet              |
| `Makefile`           | Fichier pour compiler le projet.                                         | Compilation du projet                              |
| `maps`               | Cartes du jeu.                                                           | Définit les labyrinthes du jeu                     |
| `srcs`               | Sources du jeu principal.                                                | Logique du jeu principal                           |
| `srcs_bonus`         | Sources pour la version bonus du jeu.                                    | Fonctionnalités supplémentaires pour le jeu        |
| `textures`           | Textures utilisées dans le jeu. 

## Installation et Compilation
```
git clone git@github.com:raveriss/cub3D.git
cd cub3D
make bonus
```

## Utilisation
```
./cub3D maps/good/bonus/cub3d.cub
```

## Options
Aucune option disponible pour ce projet.

## Caractéristiques
- Utilisation de la bibliothèque graphique MinilibX
- Gestion des événements clavier
- Absence de fuites de mémoire
- Respect des normes de l'école 42

## Fonctions externes autorisées
- malloc
- free
- read
- write
- exit
