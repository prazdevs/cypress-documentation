---
title: Pourquoi Cypress?
---

{% note info %}
# {% fa fa-graduation-cap %} Vous allez apprendre

- ce qu'est Cypress
- notre mission, et ce en quoi nous croyons
- les fonctionnalités principales de Cypress

{% endnote %}

<!-- textlint-disable -->
{% video youtube LcGHiFnBh3Y %}
<!-- textlint-enable -->

# En un mot

Cypress est un outil de test nouvelle génération, orienté front end et adapté au web moderne. Nous répondons au principaux problèmes recontrés par les développeurs et ingénieurs QA pour tester des applications modernes.

Cypress nous permet de:

- {% urlHash 'Parametrer des tests' Parametrer-des-tests %}
- {% urlHash 'Ecrire des test' Ecrire-des-tests %}
- {% urlHash 'Executer des tests' Executer-des-tests %}
- {% urlHash 'Deboguer des tests' Deboguer-des-tests %}

Cypress est très souvent comparé à Sélénium; cependant Cypress est à la fois fondamentalement et architecturalement différent. Cypress ne subit pas les mêmes contraintes que Sélénium.

Cela vous permet d'implémenter des tests **plus rapides**, **plus faciles** et **plus fiables**.

# Qui utilise Cypress?

Nos utilisateurs sont typiquement des développeurs ou des ingénieurs QA qui construisent des applications utilisant des frameworks JavaScript modernes.


Cypress vous permet d'écrire tout type de test:
- Tests de bout-en-bout (E2E)
- Tests d'intégration
- Tests unitaires

Cypress peut tester tout ce qui s'exécute dans un navigateur.

# L'écosystème Cypress

Cypress consiste en un exécuteur de tests gratuit, {% url "open source" https://github.com/cypress-io/cypress %}, {% url "installé localement" installing-cypress %} et en un service de tablea de bord pour {% url 'enregistrer vos tests' dashboard-introduction%}

- ***First:*** Cypress vous aide a mettre en place et à commencer à écrire des tests chaque jour lorsque vous intégrez votre solution localement. ***Le parfait outil du TDD*
- ***Later:*** Après la réalisation de votre suite de tests et {% url "l'intégration de Cypress" continuous-integration %} à votre fournisseur d'intégration continue, notre {% url 'service de tableau de bord' dashboard-introduction%} peut enregistrer les exécutions et résultats des tests. Vous n'aurez plus à vous demander: *Pourquoi est-ce en échec?*

# Notre mission

Notre mission est de construire un écosystème open source robuste, améliorant la productivité, transformant la réalisation de tests en une expérience agréable et rendant le développeur heureux. Nous nous tenons responsables de défendre un processus de test **qui fonctionne vraiment**.

Nous croyons que notre documentation doit être accessible. Ce qui signifie permettre au lecteur de comprendre pleinement le **quoi** mais aussi le **pourquoi**.

Nous voulons aider les développeurs a créer une nouvelle génération d'applications modernes plus rapides, performantes, et sans le stress et l'anxiété liées a la gestion des tests.

Nous savons que pour réussir, nous devons mettre en place, entretenir et promouvoir un écosystème qui se développe grâce à l'open source. Chaque ligne de code de test est un investissement dans **votre codebase**, il ne vous sera jamais facturé comme service payant. Les tests pourront être exécutés et fonctionner indépendamment, *toujours*.

Nous croyons que le testing a besoin de beaucoup de {% fa fa-heart %} et sommes la pour créer un outil, un service et une communeauté où chacun peut apprendre et qui bénéficie à tous. Nous résolvons les difficultés partagées par chaque développeur travaillant dans le web. Nous croyons en cette mission et espérons que vous vous joignerez à nous pour faire de Cypress un écosystème durable qui rend tout le monde heureux.

# Fonctionnalités

Cypress est prêt-à-l'emploi, piles incluses. Voici une liste des choses qu'il peut faire, qu'aucun autre framework de testing ne permet: 

- **Voyage dans le temps:** Cypress prend des captures d'écran pendant l'exécution des tests. Passez la souris au dessus des commandes dans {% url 'l historique des commandes' test-runner#Command-Log %} pour voir exacterment ce qu'il s'est passé à chaque étape. 
- **Débogage:** Fini de deviner pourquoi les tests échouent. {% url 'Deboguez directement' debugging %} depuis des outils familiers comme les DevTools. Nos erreurs lisibles et traces de la pile permettent de déboguer en un éclair.
- **Attente automatique:** N'ajoutez jamais de *wait* ou *sleep* dans vos tests. Cypress {% url 'attend automatiquement' introduction-to-cypress#Cypress-is-Not-Like-jQuery %} vos commandes et assertions avant d'avancer. Fini l'enfer asynchrone.
- **Spies, Stubs, et Clocks:** Vérifiez et {% url 'contrôlez le comportement' stubs-spies-and-clocks %} des fonctions, des réponses du serveur, ou des timers. La même fonctionnalité que vous appréciez dans vos tests unitaire est a portée de main.
- **Contrôle du traffic réseau:** {% url 'Contrôlez, simulez, et testez les cas particuliers' network-requests %} facilement sans impliquez votre serveur. Vous pouvez simuler le traffic réseau comme bon vous semble.
- **Résultats consistants:**  Notre architecture n'utilise pas Selenium ou WebDriver. Dites bonjour à des tests rapide, consistants et fiables.
- **Captures d'écran et vidéos:** Observez des captures d'écran prises automatiquement lors d'un échec ou une vidéo de l'exécution d'une suite de tests lancée depuis la ligne de commande.
- **Testing multi-navigateur:** Exécutez des tests depuis Firefox ou des navigateurs basés sur Chrome (dont Edge et Electron) localement et {% url "de façon optimale dans un processus d'intégration continue" cross-browser-testing %}.

## {% fa fa-cog %} Parametrer des tests

Il n'y a ni serveur, ni driver, ni aucune autre dépendance à installer ou à configurer. Vous pouvez écrire votre premier test réussi en 60 secondes.
There are no servers, drivers, or any other dependencies to install or configure. You can write your first passing test in 60 seconds.

{% video local /img/snippets/installing-cli.mp4 %}

## {% fa fa-code %} Ecrire des tests

Les tests écrits avec Cypress sont fait pour être facile à lire et à comprendre. Notre API est fournie complète, basée sur des outils avec lesquels vous êtes déjà familiers.

{% video local /img/snippets/writing-tests.mp4 %}

## {% fa fa-play-circle %} Executer des tests

Cypress s'exécute aussi rapidement que votre navigateur inteprête du contenu. You pouvez regarder les tests en temps réel pendant que vous développez vos applications! TDD FTW!

{% video local /img/snippets/running-tests.mp4 %}

## {% fa fa-bug %} Deboguer des tests

Des messages d'erreurs lisibles vous aident à déboguer rapidement. Vous avez aussi accès à tous les outils de développement que vous connaissez et appréciez.

{% video local /img/snippets/debugging.mp4 %}
