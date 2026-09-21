# Portfolio – Florian Marchal
Stagiaire développeur web front-end  
Formation IFAPME – Belgique

📄 **CV (PDF)** : [Télécharger mon CV](cv/Florian_Marchal_CV_Stage_Dev_Frontend.pdf)

🖨️ **CV Imprimable** : [Télécharger mon CV](cv/Florian_Marchal_CV_Stage_Dev_Frontend_printable.pdf)


---

## À propos
Développeur web front-end en formation IFAPME, avec un intérêt particulier pour
la création d’interfaces modernes, responsives et bien structurées.
Je recherche un **stage en développement web front-end**, idéalement avec
une possibilité de collaboration à plus long terme.

---

## Projets

### Travail de fin d'étude – AndromeSky 🌌

**TFE IFAPME · Application web Angular · Grande distinction (80,88 %)**

[Démo en ligne](https://flolink1er.github.io/andromesky/) · [Code source](https://github.com/Flolink1er/andromesky)

## Le projet en une phrase

> AndromeSky transforme l'exploration d'une carte du ciel en une expérience web plus claire et interactive, associant recherche, fiches astronomiques et quiz.

## Contexte et intention

Les outils d'astronomie existants sont souvent très complets, mais leurs interfaces peuvent être visuellement chargées pour une première exploration. Le projet ne cherche pas à remplacer un logiciel professionnel : il propose une entrée plus fluide vers des données astronomiques réelles, sans effacer leur richesse.

L'enjeu était de réunir dans une seule expérience une carte céleste, une navigation par recherche, des données cohérentes et une dimension ludique.

## Ma réponse

- Une SkyMap interactive, construite sur Aladin Lite ;
- Une recherche rapide dans un catalogue local normalisé ;
- Des fiches d'objets enrichies uniquement lorsque les résultats Wikipédia/NASA sont suffisamment pertinents ;
- Deux modes de quiz : reconnaître un objet ou le placer sur la carte ;
- Un design responsive, avec une attention particulière aux interactions tactiles et à la lisibilité mobile ;
- Une persistance locale du score et de l'historique de jeu.

## Compétences mises en œuvre

### Conception front-end

J'ai construit une SPA Angular structurée en composants autonomes. La présentation est séparée de la logique métier : les composants gèrent l'interface, tandis que les services portent l'état, les catalogues, le score, la carte et les requêtes externes.

### Gestion d'état réactive

Les Angular Signals permettent de synchroniser naturellement l'interface avec le mode courant, la question, la sélection, le score et les retours de validation. Les signaux modifiables restent privés aux services et sont exposés en lecture seule aux composants.

### Intégration d'une bibliothèque spécialisée

Aladin Lite utilise une logique impérative de canevas. J'ai encapsulé cette intégration dans `SkyMapService` afin de gérer les marqueurs, les overlays, les constellations, le centrage et les interactions sans coupler directement les composants Angular à la bibliothèque.

### Travail sur les données et les APIs

Les données astronomiques viennent de catalogues historiques et hétérogènes. Elles ont été sélectionnées, normalisées et enrichies avec des alias pour assurer une recherche cohérente et des segments de constellations fiables.

Les résultats Wikipédia et NASA sont traités avec une logique de recherche progressive, de score de pertinence et de cache. L'application préfère ne rien afficher plutôt que présenter une information d'un autre objet.

### UX et gamification

Le quiz de localisation utilise une distance angulaire vers la cible, avec des points progressifs selon la précision. Les gestes de glissement de carte sont distingués des clics pour éviter les sélections accidentelles sur mobile. Les indices apportent une aide contrôlée, en réduisant les points possibles.

## Résultat

Le projet aboutit à une application déployée, utilisable sur desktop et mobile, qui regroupe exploration, recherche, visualisation de constellations, enrichissement de contenu, quiz et suivi local des résultats.

Il a été présenté comme travail de fin d'études à l'IFAPME et a obtenu la **grande distinction (80,88 %)**.

## Technologies

`Angular` · `TypeScript` · `Tailwind CSS` · `RxJS` · `Aladin Lite` · `Wikipédia API` · `NASA Image Library` · `localStorage`

## Suite possible

Comptes et classement, données astronomiques enrichies, filtres avancés, éphémérides pour un ciel en temps réel et ajout des planètes sont les évolutions les plus naturelles du projet.

### 🎮 Jeu multijoueur en ligne – *Le dé menteur*
**Projet scolaire – réalisé en autonomie**

Jeu multijoueur tour par tour jouable de 2 à 6 joueurs, avec gestion complète
des parties, du gameplay, d’un chat en jeu et d’un système de classement.

**Points clés :**
- Application web complète (front-end, back-end, base de données)
- Gestion des états de jeu et des tours
- Chat lié aux parties
- Système de points et classement

🔗 Repository :  
https://github.com/Flolink1er/multiplayer-dice-game

---

### 🧩 Wordle en Vue.js
**Projet scolaire – travail de groupe**

Développement d’une version web du jeu Wordle avec Vue.js 3, incluant persistance
de la progression, dark mode et responsive design.

**Mon rôle dans le projet :**
- Développement des composants App, GameBoard, DarkModeInput, ResultPopout
- Initialisation de la logique du jeu
- CSS et responsivité
- Ajout de fonctionnalités bonus (paramétrage du jeu)

🔗 Repository vitrine :  
https://github.com/Flolink1er/wordle-vuejs

🔗 Code source de référence :  
https://github.com/Piquixel/vue-wordle

---

### 🌐 Site vitrine multi-pages – PHP / CSS
**Projet scolaire – réalisé en autonomie**

Site web multi-pages présentant un métier scientifique, réalisé **sans JavaScript**
(contraintes imposées), avec animations et interactions uniquement en CSS.

**Points clés :**
- Intégration HTML / CSS avancée
- Animations et effets visuels CSS-only
- Responsive design
- Structure PHP avec fichiers partagés
- Respect strict d’une charte graphique

🔗 Repository :  
https://github.com/Flolink1er/jobs-presentation-website

## Compétences mises en œuvre
- HTML / CSS (Flexbox, media queries, animations)
- JavaScript / TypeScript
- Vue.js 3 (Composition API)
- PHP / SQL
- Responsive design
- Git / GitHub

---
### Projet Angular en construction : RPG Textuel

🔗 Repository :  
https://github.com/Flolink1er/ng-rpg


## Contact
📄 [Mon CV](cv/Florian_Marchal_CV_Stage_Dev_Frontend.pdf) | 📧 [Email](mailto:flolink1er@gmail.com) | 🔗 [GitHub](https://github.com/Flolink1er)
