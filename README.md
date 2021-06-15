# design_pattern_doc
Documentation des differents design pattern

## Creational patterns

Il s'agit ici d'instancier des class

### Object pool

Créer plusieurs instances au lancement => ces instances peuvent être utilisées par les clients et lorsque l'on a plus besoin de cette instance elle repart dans les instances disponibles

Très utiles pour les class lourdes à instancier ==> gain de temps 

### Facade

Permet de créer une class qui va faire l'interaction avec toutes les autres class

Combine plusieurs sous systemes dans une interface simple. 


### Chain of responsability

Permet d'enchaîner plusieurs traitements lors d'une requete.


### Decorator

Permet d'avoir une class de base et on peut appeler les sous class pour ajouter des fonctionnalités en plus.

La class de base a des fonctionnalités qui seront utilisées par toutes les instances 

