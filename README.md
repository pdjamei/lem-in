lem-in
======

Fourmi

Pour être lue, la carte devra avoir le format suivant :

nbr_de_fourmi
nom_de_la_salle1 x1 y1
nom_de_la_salle2 x2 y2
...
salle1-salle2
...

x et y correspondant aux coordonnées de la salle en chiffre

les commandes ##start et ##end serve à indiquer respectivement l'entrée et la sortie.

La carte                  donnera avec 3 fourmis, 0 en entrée et 3 en sortie :
                                                                                        3
              1                                                                         ##start
            /   \                                                                       0 1 0
          0       3                                                                     1 2 1
            \   /                                                                       2 0 1
              2                                                                         ##end                                                                         3 1 2
                                                                                        0-1
                                                                                        0-2
                                                                                        1-3
                                                                                        2-3

