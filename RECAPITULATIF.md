# Récapitulatif + Informations sur notre projet.
## But du projet
Créer un **RPG (en 2D) avec Pygame**.  
Nous utiliserons des ressources **libres, prévues pour,** trouvées sur internet.

## Vocabulaire
- **Ethynd:** Nom du RPG (Généré aléatoirement)
- **Repo:** Un dossier sur Github contenant 1 projet
- **Tick:** 1 tick correspond à 1 execution de la boucle de jeu
- **TPS:** (Tick Par Seconde), correspond au nombre de fois que la boucle de jeu s'execute
- **Event/Évenement:** Qqch déclenché par une action de la personne sur son ordinateur ou directement en jeu.
- **Tuile:** Image de décor destinée à faire parti d'une map
- **Sprite:** Image d'une entitée, d'un personnage à un état fixe
- **Animation:** Regroupement de plusieurs sprites destinés à créer une animation
- **Frame:** Image d'une animation. Les frames sont stockées dans un certain ordre.
- **Map:** Regroupement de plusieurs tuiles destinées à créer un décor de jeu
- **Mapping:** Toutes choses relatives aux maps
- **CSV:** Format de stockage d'une map
- **Charger qqch:** Le stocker sous forme d'image/Le faire apparaître sur l'écran
- **Tileset:** Regroupement de plusieurs sprites/tuiles destinées à être séparés.
- **Collisions:** Le fait que certain éléments stoppent la progression du joueur
- **Hitbox:** Zone sensible d'un élément de jeu aux attaques et collisions
- **Masque:** Objet que l'on met par dessus un rectangle pygame afin de créer des collisions basées sur la transparence des images

## Structure du projet
- **[Ethynd](https://github.com/ProjetIsn2019/Ethynd)**
    - **classes** (Contient les objets utilisés pour le projet)
        - **joueur.py** (Contient les fonctions relatives au joueur)
        - **mapping.py** (Contient les fonctions relatives a la création de map)
    - **constantes** (Contient les constantes utilisées pour le projet)
        - **constantes_joueur.py** (Constantes relatives aux joueurs)
        - **constantes_partie.py** (Constantes relatives au jeu en lui même)
        - **constantes_tuiles.py** (Constantes relatives aux tuiles et aux maps)
    - **fonctions** (Contient les fonctions utilisées pour le projet)
        - **charger.py** (Fonctions pour charger des images)
        - **jeu.py** (Contient les fonctions d'évents et de boucle de jeu)
    - **images** (Contient les images utilisées pour le projet)
        - **sprites** (Contient les sprites)
        - **tuiles** (Contient les tuiles)
        - **icone.png** (Contient l'icone du jeu)
    - **maps** (Contient les maps utilisées pour le projet)
    - **main.py** (Fichier principal, celui que l'on doit executer)
    - **LICENSE** (Fichier de license pour couvrir le support et les droits)
    - **README.md** (Fichier explicatif)
## Questions - Réponses
### Comment nous chargeons une map ?
Une map n'est pas une image, c'est en réalité un assemblement de tuiles trouvables dans le dossier images/tuiles/.  
Ces dernières sont assemblés de façon à respecter le motif de la map trouvable dans le dossier map/.
### Comment afficheons-nous des animations ?
Un personnage possède un compteur. Le compteur est incrémenté chaque tick.  
Lorsque le compteur atteint le max défini dans nos constantes, nous passons à la frame suivante et le compteur est réinitialisé.
### Comment sont fait les déplacements ?
Les déplacements sont en réalité juste une prise en charge des évènements.
Lorsque vous appuyez sur la touche "gauche", l'évent "touche appuyé" se déclenche et nous vérifions si cette touche est dans nos constantes afin de déclencher l'animation.

## Tâches faites
- Hitboxs (Sofiane)
- Modification de la carte (Anthony) + Dimensions de la carte a bonne échelle (en tuiles), des petites maps etc.
- Ajouter des bruitages/Musiques + implémentation en algo/python (Anthony)
- Masques (Sofiane)
- Collisions (Sofiane)
- Créer une map simple (1 seul tile) (Dorian & Sofiane)
- Ajouter des tiles a la map (Sofiane)
- Permettre aux maps de sortir de l'écran (Anthony & Sofiane)
- Ajouter un personnage sans animation (Dorian)
- Faire une map de test en 4 couches (Anthony)
- Coder les deplacement du personnage (Dorian)
- Trouver un générateur de map (Anthony & Sofiane)
- Musiques (Anthony)
- Classe ennemi (Dorian)
- Menu (Anthony)

## Tâches à faire
- Histoire (Anthony)
- Choisir les sons et bruitages à ajouter au projet (Anthony)
- Créer des tuiles animés (Sofiane)
- S'occuper de l'attaque et des animations (Dorian)

## Sources 
- [Pygame](https://www.pygame.org) (Librairie Python "Pygame" + Documentation)
- [Piskel](https://www.piskelapp.com/) (Gérer/Modifier les sprites)
- [Google image](https://www.google.fr/imghp) (Recherche d'images libres)
- [Tuiles de jeu](https://opengameart.org/content/zelda-like-tilesets-and-sprites) (Tuiles de la map)
- [Tiled](https://www.mapeditor.org/) (Assembler les tuiles et créer les matrices)
- [Youtube](https://www.youtube.com/) (Recherche de musiques libres)
- [Créer un bouton en ligne](https://dabuttonfactory.com/fr/) (Créer les 3 boutons du menu)
- [Documentation Python](https://docs.python.org/fr/3/) (Documentation de Python)
- [Musique 1](https://www.youtube.com/watch?v=42Yw2Llnwzw) (Utilisation autorisée dans le cadre du "fair use" : projet scolaire)
- [Musique 2](https://www.youtube.com/watch?v=tlMZWKMpOn0) (Utilisation autorisée dans le cadre du "fair use" : projet scolaire)
- [Effet Spéciaux](https://www.youtube.com/watch?v=nzjtkaLCn60) (Utilisation autorisée à condition de créditer l'auteur dans les sources)
