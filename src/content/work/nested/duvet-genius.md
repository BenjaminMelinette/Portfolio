---
title: RPG Python
publishDate: 2020-03-04 00:00:00
img: /Portfolio/assets/stock-3.jpg
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
  Le tout premier projet graphique en python que j'ai réalisé au lycée.
tags:
  - RPG
  - Python
---

En effet, une petite recontextualisation s'impose, en première, je découvre une vidéo parlant du développement de jeux-vidéos qui m'intéresse fortement,
je codais déjà en python un peu de mon côté, après avoir vu cela, je me renseigne un peu et découvre la lib pygame. Puis un tutoriel fait par Graven
expliquant le raisonnement derrière un jeu-vidéo pygame. C'est alors que je tape mes premières lignes de code pour créer ce qui était mon premier RPG.

Celui-ci est assez simple, le but était de visiter une carte, trouver des objets menant à une piste puis à la fin, rentrer dans une salle avec un boss
voulant nous affronter. Plusieurs problèmes se sont posés à moi, le style du combat de Boss pour commencer, celui au début devait être un simple combat
en 2D avec des flèches à lui lancer mais le principe de combat n'était pas agréable, j'ai alors décidé de changer vers un système de combat tour par tour
dans le style de dofus (celui-ci n'ayant pas été terminé malheuresement). Tout un tas de fonctionnalité a été ajouté au jeu comme un système de sauvegarde
de la position du joueur, de la carte sur laquelle il se trouve ou encore de la quête en cours. Cette sauvegarde était sauvegardé localement en fichier texte
avec une obfuscation des données afin d'empêcher l'utilisateur de tout modifier (ça aurait été trop simple).

Durant la programmation du jeu, j'étais en même temps dans une association de E-Sport à cette époque en tant que joueur, après leur avoir présenté le jeu sur
lequel je travaillais, ils ont accroché et j'ai quitté mon "poste" de joueur pour celui de développeur, le but était de se servir du jeu comme d'une pub pour
faire connaître l'équipe e-sport. Le problème étant qu'à cette époque, j'aurais eu besoin d'aide pour le système de combat et les relations avec l'association
s'étant dégradé, j'ai décidé de la quitter.

Voici une vidéo de démonstration du jeu assez simpliste :

<br>

<center>
  <video controls width = "500" muted = "False">
    <source src="/Portfolio/assets/rpjtek_video.mp4", type="video/mp4">
    <source src="/Portfolio/assets/rpjtek_video.webm", type="video/webm">
  </video>
</center>
