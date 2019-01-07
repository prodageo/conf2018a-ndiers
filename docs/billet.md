# Vanilla JS 2018

## Cartouche d'identification

 - Manifestation : CodeursEnSeine 2017
 - Lieu : Kindarena - Rouen
 - Conférence : Vanilla JS 2018
 - Horaire de la conférence : 11h - 11h50
 - Durée de la conférence : 50 mins
 - Conférencier(s) :
   - Matthieu LUX ([Twitter](https://twitter.com/Swiip), [Github](https://github.com/Swiip))
 - Audience : ~150 personnes
 - Auteur du billet : Nicolas DIERS
 - Mots-clés : Javascript, Web Components, Virtual DOM, State Management
 - URL de l'illustration : ![VanillaJS](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRMhzdFHl0yTu5DNQbJovnZZSl4vfDCXYr1ErHTzRkIsxr_PZijg)
   - quelques sources : http://vanilla-js.com/, https://redstapler.co/what-is-vanilla-js/

## Support
 - [Lien vers le support de la conférence](https://docs.google.com/presentation/d/e/2PACX-1vR8WYVUG87OgoKDxQ-XGCv1Y_YgZt-F27GLsWYuLUVl907FniM5g-pnaWa3PktYsYE0DZdhWRi4_3LC/pub?slide=id.g41faf9c008_0_110)
 - Nombre de diapos du support : 137
 - Plan du support : Le Diapo ne comprte pas de plan défini, il s'git d'une succession d'image supportées par un projet fil rouge.

## Résumé
Le développement sans framework passe aujourd'hui presque toujours par des outils comme le ReactJS ou WebPack. L'objectif de cette conférence est de proposer une alternative pour des projets peu volumineux. Cela passe par l'utilisation de HTTP2 et JavaScript uniquement.

Toutes les fonctionnalités requises sont en effet implémentable à la main par des librairies JS. La gestion du cache et des sources étant facilité par HTTP2. En oubliant Internet Explorer, Javascript permet l'utilisation de modules et des Web Components. Ces derniers comportent les custom elements qui permettent la définition de balises personnalisées, le shadowDOM permettant de mettre du html dans des éléments JS, les templates qui sont du code non rendu utilisé ultérieurement, et les imports de html dans html.

VanillajS est un véritable framework au sein du navigateur mais très peu utilisé. Le code produit est très verbeux mais fonctionnel. Il demande un apprentissage de l'utilisation des APIs des navigateurs. Cependant, des problèmes de compatibilités se posent pour certains navigateurs selon la fonctionnalité utilisée. VanillaJS est donc une solution viable pour des projets modestes à condition de prendre le temps de coder sa propre librairie.


## Architecture et facteur qualité
Le choix d'un framework pour une application web est lié aux facteurs qualité ISO9126:2001 que sont la Portabilité (Portability), La Maintenabilité (Maintenability), et l'Efficacité (Efficiency). Ce talk aborde le caractère universel du Javascript et sa portabilité  entre les navigateurs, sa maintenabilité de par la simplicité du code facilement lisible. L'efficacité est assurée par la non utilisation de la surcharge de code apportée par les frameworks ou le jquery.

VanillaJS respecte donc la maintenabilité car le code est composé uniquement de Javascript de base et il est donc à la charge du développeur d'écrire un code simple et lisible, le langage étant connu de tous. Les modules et les Web components permettent de plus un code modulaire. La portabilité pose problème sur les navigateurs les plus anciens n'ayant pas alors implémenté les fonctionnalités du VanillaJS. Concernant l'efficacité, malgré des performances très bonnes de par la non surcharge de code des frameworks, le temps de développement supplémentaire est un défault majeur.
