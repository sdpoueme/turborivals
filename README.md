# Turbo Rivals
Code pour le jeu Turbo Rivals un un jeu de course dynamique où les joueurs affrontent des adversaires contrôlés par l'intelligence artificielle (IA) sur différents circuits. 

# Conception
TODO

## Hiérarchie de classe

### Description Textuelle

Le jeu est opéré depuis un objet unique appelé TurboRivals qui sert de gestionnaire de jeu. Nous utilisons un patron de conception de type composition pour le jeu qui est composé d'une classe Race Manager (singleton, objet unique de contrôle de la course). 
TurboRivals (Singleton)
- RaceManager (Singleton)
- Race (Composition)
  - Vehicles
     - PlayerVehicle
     - IAVehicle
  - Track
  - SpecialObjects
  - ScoreBoard

### Image

![Slide1](https://github.com/user-attachments/assets/6fa1fcb1-1c37-4807-8a32-c7f417d2afea)


## Tableau descriptif des classes

| Nom de classe  | Description  | Atrributs et Methodes  |
|--|--|--|
|RaceManager| contient un objet course...etc| Race aRace, startRace(), endRace(), setWinner ()|
|Race|TODO|TODO|
|Vehicles|TODO|TODO|
|RaceManager|TODO|TODO|
|PlayerVehicle|TODO|TODO|
|IAVehicle|TODO|TODO|
|Track|TODO|TODO|
|ScoreBoard|TODO|TODO|




## Patrons de conception utilisés
Singleton utilisé pour un seul objet de gestion de la course.
Composition car une course est composée de plusieurs véhicules, des objets spéciaux, une piste et un tableau de sport. 

## Alogrithmique du jeu

Notre circuit va être checkpoints. On va avoir 3 checkpoints qui représente 33% du circuit. Et on va utiliser Djistkra pour trouver le plus court chemin entre chaque checkpoint. 

Checkpoint 1 -> Checkpoint 2 -> Checkpoint 3

Si le joueur choisit un niveau de difficulté dans le gestionnaire de course (RaceManager), les IA seront plus intelligentes et utiliserons A* parceque il donnera des résultats plus rapidement et les IA seront plus réactives. 

# Développement
TODO
