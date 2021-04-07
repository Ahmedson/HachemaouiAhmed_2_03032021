# P2_Reservia

Formation developpeur web openclassrooms : Projet 2, intégration maquette.

7 couleurs : 

- #0065FC bleu 
- #E0EBFD bleu ciel (background-color des icônes)
- #F2F2F2 gris pour le fond
- #D5D5D5 gris pour l'étoile
- rgb 66 66 66 gris foncée (ombre des cartes)
- #fff blanc
- #000 noir 

1 Police importée via googlefonts :

- raleway 

8 types d'icônes importé via Font Awesome :

- localisation x1
- billet x1
- bonhomme x1 
- cœur x1
- chien x1 
- flèche vers le haut x1
- étoile x45

Langue : français

HEAD :

- meta charset="UTF-8
- meta viewport
- meta description

- link style.css
- link media-queries.css
- link icon (favicon)

- script fontawesome

BODY :
Div container :

1 header :

- lien > img (logo)
- div nav_log > nav* + p* 

- *nav > ul > li > a x2
- *p > a (login)

1 main : 

3 sections : 1 recherche / 1 hebergements / 1 activités

Section Recherche : 4 div 

- Div 1 : h2 + p
- Div 2 : i + input + button
- Div 3 : span + button > span > i x4
- Div 4 : p > small > i

Section Hebergements : 

2 div : hebergements + hebergements populaires

div hebergements : 

- h2 + 6 div* + p

- *div : a > div + div > h4 + p + i x5

div hebergements populaires :

- h2 > i + 3 div* 

- *div : a > div + div > h4 + p + div > i x5

Section Activités : h2 + 6 div*

- *div : a > h4 

1 Footer : 3 div* 

- *div : h4 + ul > li > a x3/2/2