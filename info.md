# Informations
Des informations pour clarifier le projet
## But du projet
Créer un RPG (en 2D) avec Pygame. 
## Vocabulaire
- Ethynd: Nom du RPG (Généré aléatoirement)
- Repo: Un dossier sur Github contenant 1 projet
- Tick: 1 tick correspond à 1 execution de la boucle de jeu
- TPS: (Tick Par Seconde), correspond au nombre de fois que la boucle de jeu s'execute
- Tuile: Image de décor destinée à faire parti d'une map
- Sprite: Image d'une entitée, d'un personnage à un état fixe
- Animation: Regroupement de plusieurs sprites destinés à créer une animation
- Map: Regroupement de plusieurs tuiles destinées à créer un décor de jeu
- Mapping: Toutes choses relatives aux maps
- CSV: Format de stockage d'une map
- Charger qqch: Le stocker sous forme d'image/Le faire apparaître sur l'écran
- Tileset: Regroupement de plusieurs sprites/tuiles destinées à être séparés.
## Logiciels
- [Github](https://github.com) (Mise en forme projet)
- [Pygame](https://www.pygame.org) (Librairie Python)
- [Piskel](http://piskelapp.com) (Découper/Séparer des tilesets)
- [Tiled](https://thorbjorn.itch.io/tiled) (Créer des map à partir de tuiles)
## Structure du projet
- [Ethynd](https://github.com/ProjetIsn2019/Ethynd)
    - classes (Contient les objets utilisés pour le projet)
        - joueur.py (Contient les fonctions relatives au joueur)
        - mapping.py (Contient les fonctions relatives a la création de map)
    - constantes (Contient les constantes utilisées pour le projet)
        - constantes_joueur.py (Constantes relatives aux joueurs)
        - constantes_partie.py (Constantes relatives au jeu en lui même)
        - constantes_tuiles.py (Constantes relatives aux tuiles et aux maps)
    - fonctions (Contient les fonctions utilisées pour le projet)
        - charger.py (Fonctions pour charger des images)
        - jeu.py (Contient les fonctions d'évents et de boucle de jeu)
    - images (Contient les images utilisées pour le projet)
        - sprites (Contient les sprites)
        - tuiles (Contient les tuiles)
        - icone.png (Contient l'icone du jeu)
    - maps (Contient les maps utilisées pour le projet)
    - main.py (Fichier principal, celui que l'on doit executer)
    - LICENSE (Fichier de license pour couvrir le support et les droits)
    - README.md (Fichier explicatif)
## Sources
- Tuiles:
    - [https://opengameart.org/content/the-field-of-the-floating-islands](https://opengameart.org/content/the-field-of-the-floating-islands)
- Sprites:
    - [https://opengameart.org/content/2d-complete-characters](https://opengameart.org/content/2d-complete-characters)
