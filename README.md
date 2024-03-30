[![made-with-javascript](https://img.shields.io/badge/Made%20with-Javascript-326996.svg)](https://www.javascript.com)
[![made-with-javascript](https://img.shields.io/badge/Made%20with-HTML-326996.svg)](https://html.spec.whatwg.org/multipage/)
[![made-with-javascript](https://img.shields.io/badge/Made%20with-CSS-326996.svg)](https://www.w3.org/Style/CSS/)

# Projet - "Ping my tab" <img width="32" alt="redlight" src="https://github.com/PierrePedrono/projet-collectif-extension-navigateur-les-foufous-girafarbres/assets/146751236/1c7de2ac-3fb7-4249-a089-9bfce9c10463">

"Ping my tab"  est une extension du navigateur chrome qui indique à son utilisateur qu'il ou elle a ouvert trop d'onglets, en modifiant l'icône d'extension dans la barre d'outils. Ce projet a été développé en tant que project collectif  à  **_Ada Tech School_**.


## Aperçu

<img src="https://github.com/PierrePedrono/projet-collectif-extension-navigateur-les-foufous-girafarbres/assets/146751236/cc5a0430-e402-4c3a-8759-1f65462be61b" width="50%" height="50%">

Ouverture d'onglets :

![ouvertureOnglets](https://github.com/PierrePedrono/projet-collectif-extension-navigateur-les-foufous-girafarbres/assets/146751236/ce84b04c-9665-456f-b089-99a8841fef24)

Fermeture d'onglets :

![fermetureOnglets](https://github.com/PierrePedrono/projet-collectif-extension-navigateur-les-foufous-girafarbres/assets/146751236/08ddc222-2127-4ebc-b676-b48f503b5488)



## Contexte du projet

Le but du projet était de développer une extension pour le navigateur de notre choix. Plusieurs idées nous étaient proposées. Nous avons cependant fait le choix de partir sur une idée originale. "Ping my tab" a pour but de gérer le nombre d’onglets ouverts et être averti lorsque trop de pages sont utilisées. Le projet est en lien avec le thème du numérique responsable. Il a été conçu et développé en 10 jours par 4 apprenants. 


## Objectifs

Les principaux objectifs pédagogiques du projet étaient les suivants : découvrir l’écosystème d’un navigateur, explorer les mécanismes d’un navigateur (DOM, moteur exécution JS,...), se familiariser avec la documentation d’un navigateur ainsi qu'apprendre à s’organiser en équipe.




## Déroulé du projet 

Notre idée initiale du projet (MVP), était d'insérer une image dynamique sur la page visitée, évoluant selon le nombre d'onglets ouverts dans la fenêtre du  navigateur (via le content-script). Nous avons cependant dû nous réorienter en raison des interdictions d'insertion d'image sur  les pages visitées. Nous avons ainsi fait le choix de passer par l'icône de l'extension dans la barre d'outils (et donc via le background). Cette dernière peut en effet changer selon des évènements. 


## Collaboration et communication 

Le projet ayant été découpé en très petites tâches, nous avons mis en place 3 briefs par jour : en début de matinée, en début d'après-midi, et en fin d'après-midi. Et ce afin de pouvoir réunir et tester nos morceaux de code tout au long du développement du projet.
Pour effectuer le suivi de nos tâches, nous échanger des informations et des données, nous nous sommes appuyé.e.s sur des outils tels que **Trello** et **Slack**.



## Conclusion 
L'intention initiale du projet : indiquer à l'utilisateur son trop grand nombre d'onglets ouverts, a bien été respectée. Et ce grâce à notre adaptation aux contraintes rencontrées lors du développement de notre MVP initial. 

Afin d'améliorer notre extension, voici quelques pistes que nous aurions aimé creuser si nous avions eu plus de temps :
* Un menu avec des icones customisées par thème
* Une pop-up d'alerte indiquant les franchissements de seuils d'onglets ouverts 
* Adapter nos seuils d'alerte en fonction de données réelles de consommation énergétique des onglets ouverts
* Donner un indice de la consommation énergétique en fonction du nombre d'onglets ouverts 



## Comment installer et lancer le projet

1. Cloner le repo GitHub du projet sur son ordinateur

2. Installer le navigateur **Google Chrome** ou le navigateur **Opera**

3. Taper dans la barre de recherche de votre navigateur : **chrome://extensions/**

4. En haut à droite de l'écran, activer le **mode développeur**.

5. Cliquer sur "Charger l'extension non empaquetée"

6. Rechercher et sélectionner le dossier : "extension Ping my tab"

7. Activer le toggle en bas à droite du menu de l'extension pour faire apparaître l'icône en permanence dans la barre d'outils.


Vous pouvez désormais naviguer sur le web de façon plus responsable !



*A noter : une erreur s'affiche parfois, celle-ci ne gêne pas le bon fonctionnement de l'extension.*



## Crédits 
Anna T.
Florentin C.
Pierre P.
Promise H.


## Licence :
GNU GPL v3.
