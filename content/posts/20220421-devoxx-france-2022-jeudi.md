---
title: "Devoxx France 2022 - Jeudi"
date: 2022-04-21T23:40:12+02:00
tags: ['dev', 'conference']
---

Première journée de Devoxx, et découverte du Palais des Congrès (qui, il faut le dire, a de la gueule).

On a même de la pub dans les toilettes et des boutons pour noter la qualité de notre pipi (bon, en vrai, la propreté). Le véritable futur est là 🚀

Je vais mettre mettre des petits emojis à côté des titres, pour donner mon ressenti global. Et j'essaye de faire des résumés plus ou moins succints de ce qui a été abordé !

# Les keynotes

## 🫥 Devoxx France 2022 - 10 ans déjà

Bon, j'ai pas grand chose à dire. Je connais pas trop Devoxx. Ça a parlé des 10 ans, je crois.

De toute façon, j'étais en retard, j'ai du entendre 5 minutes de la keynote.

## 😐 10 ans de Tech à travers le podcast Niptech

Assez sympa. Ça parle de comment ça a évolué dans le monde du podcast, entre l'ancêtre qu'est devenu le RSS (alors que ça reste la meilleure méthode de diffusion, mais passons) et les nouvelles méthodes très fermées qu'on a aujourd'hui.

C'est assez fou de se rendre compte à quel point nos modes de consommation ont changé en 10 ans, et à quel point on s'est renfermé dans des plateformes propriétaires (qui sont certes très pratiques) au détriment d'anciennes façons de faire qui étaient quand même bien plus versatiles.

Bon, je me souviens pas de tout ce qui a été dit, c'est en tout cas ce qui m'a le plus marqué.

## 🙂 Slow.tech : il est urgent de hacker le système !

Où l'on parle du rapport du GIEC et du chiffre alarmant des 3 ans pour laisser un monde vivable aux générations futures (et à la mienne au passage, mais je suis déja suffisamment pessimiste 👍).

On y parle de pas mal de choses censées, qui portent le nom de *slow tech* (terme que j'ai découvert sur le moment) : utiliser les nouvelles technologies à bon escient, afin de remplacer des processus plus coûteux énergétiquement, par des processus plus efficients avec les nouvelles technologies.

Ou bien encore des problématiques d'obégiciels, ce qui pousse à augmenter (souvent inutilement) la RAM de nos appareils, impliquant l'extraction et l'utilisation de ressources ...

# Les conférences

## 🥰 Comprendre les enjeux de consommation de ressource et d’énergie dans le secteur numérique

Une excellente conférence qui vise à dé-diaboliser le numérique, souvent critiqué comme l'un des gros pollueurs.

On remet un peu en place les médais et les chiffres qui sont mis en avant, souvent scientifiquement douteux ou peu expliqués. Et on dénonce des foutaises du *greenwashing digital*.

Oui, le streaming ça consomme beaucoup. Oui, les data center aussi. Mais finalement, les disque durs, ils sont déja là. Le taux carbone d'un email par exemple n'a pas de sens si on prend pas en compte l'horaire d'envoi et le pays de l'expéditeur et du destinataire (bah oui, le bilan carbone d'un pays n'est pas le même que celui de son voison).

On rappelle à quel point le numérique est une chance, qui permet par exemple de réduire le transport : le télétravail, ça consomme beaucoup de réseau (surtout si on met sa webcam), mais ça reste mieux que prendre sa voiture pour aller à 1h de chez soi faire le même travail que si on restait chez soi - en tout cas en France.

J'ai aussi adoré le rappel sur le fait qu'acheter des produits daubés qui vont tomber en rade en 1 an, où n'auront aucun support logiciel, c'est de la merde, et que si on a la possibilité, c'est évidemment mieux d'acheter des trucs qui vont durer.

Parce que finalement, ce qui pollue le plus dans le numérique, c'est la conception de tous nos produits.

Bref, c'était passionnant, et un petit thread qui en parle est disponible sur le Twitter de [davlgd](https://twitter.com/davlgd/status/1517055462277062656?).

*Évidemment, rester sobre numériquement, c'est toujours un plus. Mais aucun intérêt de se sentir sale parce qu'on a reçu un email et que ça y est, on a ajouté 10 degrés à la planète. Le problème écologique est ailleurs, dans nos habitudes de consommation et de transport.*

## 🙂 Licences open source : entre guerre de clochers et radicalité

Une conférence sur l'open source, chouette ! On parle évidemment des licences usuelles, entre MIT, Apache 2.0, GPL 2.0, LGPL 3.0, les licences éthiques ... Licences éthiques ?

C'est un peu ce qui m'a le plus marqué : la quantité de licences qui ont émergé ces dernières années, et dont je n'avais pas entendu parler auparavant. Souvent basées sur des licences plus "classiques", on retrouve par exemple, des licences [anti-nucléaire](https://spdx.org/licenses/BSD-3-Clause-No-Nuclear-License.html), anti-militaire, [anti-exploitation des travailleurs en Chine](https://github.com/kattgu7/Anti-996-License), [anti-captalisme](http://wiki.commonstransition.org/wiki/Peer_Production_License), ...

Bref, les licences, ça a jamais été simple, mais c'est devenu encore plus complexe récemment.

Ça nous invite à réfléchir, nous, développeurs, à l'éthique des produits que l'on développe : suis-je en accord avec la licence proposée, et donc prêt à la suivre ? Est-ce que mon entreprise serait en accord avec des licences plus radicales, et sinon, comment faire ? Est-ce que l'entreprise elle-même est en accord avec mes idées ?

Et puis, ça montre que le métier de juriste, il sert pas à rien. Car bon courage pour déchiffrer toutes les nuances de certaines licences par rapport au produit que l'on développe ...

## 😐 Quickie : Introduction à REMIX

Une conférence bien plus courte, qui présente [Remix](https://remix.run/), un framework fullstack en Javascript.

C'est intéressant, c'est fonctionnel, ça a l'avantage de fonctionner même si l'utilisateur n'a pas Javascript d'activé.

Mais je trouve que ça lie trop le code front et le code back, au point où il est presque impossible de les séparer sans repartir à zéro.

## 😐 Protéger son organisation des attaques par le système de build

Ce n'est pas totalement mon domaine, mais c'était intéressant d'être rappelé au fait que le code exécuté pendant la CI/CD est une source d'exploitation des systèmes, et que le nombre de vecteurs d'attaque est assez grand : dépendances abusives, dépendances vulnérables (par exemple log4j / colors.js), *pull request* malicieuses qui viennent exécuter du code non attendu, ...

En bref, il faut réussir à sécuriser autant que possible, sans pour autant que ça ajoute trop de complexité pour les développeurs ... Et c'est pas tâche aisée ! (possibilité de tricher sur les signatures, confiance aux contributeurs, ...)

## 🙂 De OUI.sncf à SNCF Connect, 10 ans de mobile natif à Flutter

C'était un retour d'expérience assez enrichissant. Flutter a l'air d'être une très bonne alternative sur mobile pour avoir un code source unique entre iOS et Android (et donc la parité des fonctionnalités).

On ne rencontre pas les problèmes de performance de React Native par exemple (coucou Discord !), et on gagne aussi en simplicité dans le code, car Dart est bien moins lourd.

Je trouve quand même que Flutter a l'air encore trop jeune, car les devs eux-même mentionnaient des choses qui ont changé du tout au rien il y a à peine 1 an. Le choix de la SNCF était osé, mais le pari a l'air réussi : l'application est robuste (au contraire d'applications en React Native, comme celle de Discord - oui, je lâcherai pas l'affaire 😡), et ils ont gagné en rapidité de développement.

Flutter sur le web a l'air par contre bien moins prometteur, et je doute que ça change : l'utilisation d'un canvas plutôt que du DOM flingue son utilisation dans beaucoup de domaines (pas d'accessibilité notamment).

Je reste convaincu que des applications natives, c'est préférable lorsque possible. Pour moi, Flutter restera au mobile ce qu'Electron est à Windows/Mac/Linux : de la simplicité au détriment de l'exploitation à 100% de l'OS et de l'hardware.

## 🙂 Save the date !

Une conférence sur les dates, qui était très intéressante, bien que j'ai peu à dire : on a surtout évoqué les problématiques de stockage des dates, compliqué par les fuseaux horaires notamment.

J'y ai appris que Javascript va enfin avoir une véritable API dédiée, et que je connais toujours pas par coeur le nom de la norme ISO-8601 (un jour, peut-être).

La morale : ne pas réinventer la roue, et utiliser les API natives et des librairies toutes prêtes (et fiables) lorsque nécessaire.

## 🥰 Apprendre la musique - developer edition

Une petite conférence de fin de journée, très sympathique. Je suis seulement en train d'apprendre les bases de la théorie musicale, donc je comprenais pas tout, mais on a découvert [Sonic Pi](https://sonic-pi.net/). Ça a l'air marrant, et faudra que j'essaye un jour.

On a révisé de la physique et des mathématiques autour des signaux et de la conversion analogique vers numérique. Souvenirs de prépa ...

Ah, et on s'est fait *rickroller*  par un programme qui joue de la musique. Et ça, c'était beau.

# "Tools in action"

## 😐 Git, back to the future

Bon, ça parle de Git quoi. On mentionne des commandes comme `git reflog`, `git rebase`, `git fixup`. C'était intéressant, parce que c'est pas tous les jours qu'on pense à réécrire l'historique de son dépôt (ou qu'on utilise ces commandes).

Mais bon, je vois pas d'applications pratiques, parce que réécrire un historique, c'est quelque chose que je trouve dangereux (sauf cas particuliers).

## 🫥 Jouer à Minecraft avec une IA générée par GPT-3

Je suis resté parce que je pensais que ça serait marrant. J'ai un peu regretté, parce que finalement, l'IA réagit surtout à des commandes sans réellemment paraitre intelligente.

Et comme la demo a vite coulée (comprendre : le bot s'est retrouvé dans l'eau et savait pas en sortir, ce qui le faisait crasher), bah je suis pas très convaincu. Peut-être que ça aurait été plus intéressant si ça avait duré !
