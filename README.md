# Event Badge Generator
## Instructions
Attention: le format de sortie est adapté à **A4** pour des badge de 95 x 65mm horizontal.

Pour changer le format, il faut changer les mesures en mm dans les classes css selon les dimensions du format papier souhaité.

Finalement, pour tous les autres changements (images, positionnement...), il faut aussi éditer le css directement.

[Démonstration](http://myselfhimself.github.io/medjugorje-event-badge-generator/)

### Étape 1
Choisir un fichier .csv avec 4 colonnes :
```csv
Name,Role,Country,ISO
```
Le code ISO sert a fabriquer un drapeau emoji.

### Étape 2
Imprimer la page générée avec **Ctrl + p**

Voici la configuration de l'impression :

![Instructions](https://raw.githubusercontent.com/gnut3ll4/event-badge-generator/master/img/instruction1.png)

### Étape 3
Valider !

## Librairies utilisées
- [PapaParse](https://github.com/mholt/PapaParse)

## Credits
Merci à [@ttauveron](https://github.com/ttauveron) ayant créé le projet à l'origine de ce léger fork.
