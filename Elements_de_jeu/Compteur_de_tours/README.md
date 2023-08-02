## Contenu

Ce dossier contient les éléments qui vous permettront de fabriquer le compteur de tours du jeu (optionnel mais bien pratique !). Il s'agit d'un boitier électronique qui vous aide à suivre le déroulement d'une partie, en comptant les tours et le nombre de semaines de jeu. Il permet également de commander la tour de dés (optionnelle également). 
Nous vous fournissons le schéma électronique, la liste des composants nécessaires, ,les fichiers "gerber" pour la fabrication du circuit imprimé, et bien sûr le programme à uploader sur la carte Arduino.
Le fichier 3D pour imprimer le boitier est également inclus.

## Fabrication

### Le circuit

Vous devez utiliser les fichiers "gerber" pour faire fabriquer le circuit (PCB) ou bien le fabriquer vous-même à l'aide d'une graveuse CNC (type 3018). 

Une fois le circuit gravé, suivez le document .pdf ainsi que la liste des composants ci-dessous, pour l'assemblage.
Une fois assemblé, le circuit se branche sur une carte Arduino Uno comme un "shield". Vous n'avez plus qu'à téléverser le programme fourni dans l'Arduino.

### Liste des composants

- 1 Plaques pour PCB FR04 (cuivre+epoxy) simple face 100x70mm minimum  1x
- 2 Arduino UNO R3  1x
- 3 Potentiomètre 304 300K Ohms  1x
- 4 Bouton poussoir carré 12x12 mm   3x
- 5 Ecran LCD 1602   1x
- 6 Résistance 220 Ohms   1x
- 7 Connecteur (pin) mâle a souder  3x6 droit, 1x4 droit, 1x3 coudée, 1x2 droit.
- 8 Interrupteur à Glissière 3 Broches 2 Positions 0.5A 50V DC   1x
- 9 Adaptateur de pile 9v pour Arduino Uno   1x
- 10 Pile 9V   1x

### Fonctionnement du compteur de tours

