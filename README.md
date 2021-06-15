# design_pattern_doc
Documentation des différents design pattern

Il existe 3 types de design patterns :

- Creational patterns : on parle ici d'instanciation de class
- Structural design patterns : classes et objets qui vont se composer
- Behavioral design patterns : communication entre les différents objets


## Creational patterns

### Object pool

Créer plusieurs instances au lancement => ces instances peuvent être utilisées par les clients et lorsque l'on a plus besoin de cette instance elle repart dans les instances disponibles

Très utiles pour les class lourdes à instancier ==> gain de temps 


## Structural design patterns

### Facade

Permet de créer une class qui va faire l'interaction avec toutes les autres class

Combine plusieurs sous systemes dans une interface simple. 

### Decorator

Permet d'avoir une class de base et on peut appeler les sous class pour ajouter des fonctionnalités en plus.

La class de base a des fonctionnalités qui seront utilisées par toutes les instances 

## Behavioral design patterns

### Chain of responsability

Permet d'enchaîner plusieurs traitements lors d'une requete.

### Strategy

Ce design pattern permet d'avoir plusieurs algorithmes pour un même objet ==> On choisi l'algo selon ce que l'on souhaite faire ==> L'interface va décider quel objet va être implémenté
Par rapport au design pattern decorator, la stratégie va changer le contenu de l'objet or le decorator va changer sa devanture.
Par exemple, nous souhaitons monter notre ordinateur, l'objectif étant que cela fonctionne et fasse tourner des jeux videos puissants. On va donc opter pour des composants au coût élevé et aux performances élevées. 


