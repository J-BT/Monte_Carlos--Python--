Approximation de la valeur de Pi
grâce à la méthode de Monte-Carlos:
-----------------------------------

Grâce à la méthode de Monte-Carlos,on est capable d'approcher la valeur de
pi en fonction de la circonference d'un cercle.

Le principe est simple, en imaginant que le cercle est une cible de
flechette dont le diamètre est égal à la longueur d'un côté du carré
qui l'entoure.
On va essayer de lancer des flechettes dans la cible.

- Les flechettes qui ont atteint la cible sont des point bleus
- Les flechettes qui  n'ont pas atteint la cible sont rouges 

Le principe est de jeter un grand nombre de fléchettes sur une cible carrée,
puis de déterminer la proportion des fléchettes arrivées dans le cercle
 (points rouge) inscrit au carré. On utilise pour cela, le rapport entre
 l’aire du cercle et celle de la cible.

Ainsi plus l'on lancera de flechettes et plus la valeurs approchée sera 
proche de la valeur exacte de pi.


N.b : Pour représenter graphiquement ce projet, j'ai utilisé un module
crée par l'auteur de : Python Programming: An Introduction to Computer
 Science, 3rd Edition (voir le pdf joint à ce repository github).
Ce module est appelé graphics.py (voir repository github) et est egalement 
disponible sur le site de l'auteur, John Zelle, à l'adresse suivante : 
https://mcsp.wartburg.edu/zelle/python/graphics.py
