# LA TYPOGRAPHIE SINGLE LINE AVEC METAPOST

**MetaPost** est un langage de programmation open source qui permet de dessiner des figures, et donc des caractères. MetaPost décrit la lettre par son "ductus", son squelette. 
Le principe est d’utiliser des coordonnées de points pour dessiner nos lettres.

### Point historique 
MetaPost est basé sur **MetaFont** crée par Donald Knuth en 1979. MetaFont est un système de description pour dessiner une famille de fontes. 
C’est le format de fonte utilisé sous TEX. On ne programme pas des contours, mais des tracés vectoriels.

**TEX** et **MetaFont**
Donald Knuth (1938) est un informaticien américain. Déçu par le rendu des systèmes de photocomposition de l’époque, il décide de développer son propre système de composition numérique. Impressionné par la qualité d’impression des nouvelles imprimantes laser, il imagine ainsi les logiciels libres et langages de programmation **TEX** en 1978 et **METAFONT** en 1979.
**TEX** est le premier système de composition typographique numérique.

Afin d’éviter l’installation de metapost sur vos machines (très gourmande en espace), nous allons utiliser un previewer crée par Troy Henderson accessible sur le net :
http://www.tlhiv.org/mppreview/

### Les différentes étapes de la journée :
* Tirage au sort des lettres que vous allez dessiner
* Dessin à la main sur la grille fournie
* Construire les lettres sur le [MetaPost previewer](http://www.tlhiv.org/mppreview/) - Exporter chaque glyphe en svg ! Garder les fichiers .mp
* Importer les svg dans un éditeur de fonte (Glyphs/FontLab/Robofont/FontForge)
* Exporter une svg font sur FontForge en suivant les instructions de l'Isdat sur leur projet [Relief Singleline](https://github.com/isdat-type/Relief-SingleLine/tree/main)
* Télécharger Inskape et installer la fonte dans le package de l'application
https://inkscape.org/release/inkscape-1.3/
* Faire des visuels avec vos glyphes
* Impression au plotter !

## NOTRE ESPACE DE TRAVAIL
https://gitlab.com/erg-type/workshop.meta-elastique/-/blob/master/cheatsheet/cheatsheet.md

```
u:=50;
Ascender:=15u;
CapHeight:=13u;
xHeight:=8u;
Baseline:=0;
Descender:=-5u;
```
Voici le code à répéter au dessus de chaque glyphe que vous construisez

Exemple avec **Iota Singleline**:

![Dessins Iota](https://github.com/CamilleWisniewski/Metapost-type-studio/blob/a83a03d8f76e4f8b9b74ed679ee05279ee329cb2/sources/iota1.png)
![Dessins Iota](https://github.com/CamilleWisniewski/Metapost-type-studio/blob/a83a03d8f76e4f8b9b74ed679ee05279ee329cb2/sources/iota4.png)
![Metapost Iota](https://github.com/CamilleWisniewski/Metapost-type-studio/blob/83480f8b3121f405f6855e49ac23304fb5028e95/sources/metapost-online.png)
![Glyphs Iota](https://github.com/CamilleWisniewski/Metapost-type-studio/blob/83480f8b3121f405f6855e49ac23304fb5028e95/sources/editeur-glyphes.png)
![Le Trait Iota](https://github.com/CamilleWisniewski/Metapost-type-studio/blob/a83a03d8f76e4f8b9b74ed679ee05279ee329cb2/sources/le-trait.png)

### Ressources

- https://gitlab.com/erg-type/workshop.meta-elastique/-/blob/master/cheatsheet/cheatsheet.md
- https://gitlab.com/erg-type/metapost.survival-kit
- http://osp.kitchen/workshop/metapost-anrt
- https://www.tug.org/metapost.html
- https://github.com/isdat-type/Relief-SingleLine/tree/main
- https://gitlab.constantvzw.org/osp/workshop.single-line/-/tree/master/
