https://github.com/CamilleWisniewski/Metapost-type-studio.git

*Metapost Online
http://www.tlhiv.org/mppreview/

*Ressources

https://gitlab.com/erg-type/workshop.meta-elastique/-/blob/master/cheatsheet/cheatsheet.md
https://gitlab.com/erg-type/metapost.survival-kit
http://osp.kitchen/workshop/metapost-anrt
https://www.tug.org/metapost.html
https://github.com/isdat-type/Relief-SingleLine/tree/main
https://gitlab.constantvzw.org/osp/workshop.single-line/-/tree/master/

LA TYPOGRAPHIE SINGLE LINE AVEC METAPOST

MetaPost est un langage de programmation open source qui permet de dessiner des figures, et donc des caractères. Metapost décrit la lettre par son "ductus", son squelette. Le principe est d’utiliser des coordonnées de points pour dessiner nos lettres.

Point historique 
Metapost est basé sur Metafont crée par Donald Knuth en 1979. Metafont est un système de description pour dessiner une famille de fontes. C’est le format de fonte utilisé sous TEX. On ne programme pas des contours, mais des tracés vectoriels.

TEX et Metafont
Donald Knuth (1938) est un informaticien américain. Déçu par le rendu des systèmes de photocomposition de l’époque, il décide de développer son propre système de composition numérique. Impressionné par la qualité d’impression des nouvelles imprimantes laser, il imagine ainsi les logiciels libres et langages de programmation TEX en 1978 et METAFONT en 1979.
TEX est le premier système de composition typographique numérique.


Afin d’éviter l’installation de metapost sur vos machines (très gourmande en espace), nous allons utiliser un pre- viewer crée par Troy Henderson accessible sur le net :
http://www.tlhiv.org/mppreview/

Les différentes étapes de la journée :
- tirage au sort des lettres que vous allez dessiner
- Dessin à la main sur la grille fournie
- Construire la lettre sur le MetaPost previewer - exporter chaque glyphe en svg ! Garder les fichiers .mp
- Importer les svg dans un éditeur de fonte (Glyphs/FontLab/Robofont/FontForge)
- Exporter une svg font sur Font Forge en suivant les instructions de l'Isdat sur leur projet Relief Singleline

Cette typographie single line est utile pour l’utilisation sur une cnc, plotter, gravure laser...

Avec cette solution la svg font n'est pas utilisable sur la suite Adobe, mais elle est supporter par son concurrent libre InsKape
- Télécharger Inskape et installer la fonte dans le package de l'application
https://inkscape.org/release/inkscape-1.3/




