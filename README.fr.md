[English](README.md) · [Español](README.es.md) · **Français** · [Deutsch](README.de.md) · [Português](README.pt.md)

# Shania Timing

> Un tableau de bord léger, en lecture seule, qui montre ce que fait chaque session de programmation IA et le temps restant.

## Ce que c’est

Shania Timing recueille un « battement de cœur » de chaque session de programmation IA qui travaille sur un projet (état, titre de la tâche, avancement) et l’affiche dans une petite fenêtre de bureau toujours visible et dans un tableau de bord des sessions. Il est utilisé au sein du studio et disponible sur demande pour les équipes qui travaillent avec plusieurs sessions d’IA. Il n’affiche que de l’information et n’a aucun bouton agissant sur les sessions.

## Pour qui

- Les personnes qui gèrent plusieurs sessions ou machines de programmation IA en parallèle et demandent sans cesse « combien de temps reste-t-il ? ».
- Disponible sur demande pour les équipes qui travaillent avec plusieurs sessions d’IA.

## Ce que ça fait

- Battement de cœur par session avec des états explicites : en cours, en attente de la titulaire, en attente de tour, en attente de ressource, interrompue, terminée.
- Une session sans battement récent s’affiche « sans données », jamais « en cours ».
- Estimation du temps restant à partir de moyennes mesurées par type de tâche et par machine, pas de suppositions ; les attentes de tour sont affichées à part.
- Petite fenêtre de bureau sans bordure (Windows, Tauri) toujours au premier plan ; environ 28 Mo de RAM lors du test de l’équipe.
- Page de tableau de bord avec une carte par session, un graphique animé du quota d’utilisation de l’IA, une frise de la journée, les déploiements et les commits par dépôt. Lecture seule.
- Filtre de confidentialité : e-mails, numéros de téléphone espagnols et numéros d’identification fiscale sont masqués avant toute écriture ; les auteurs des commits ne sont pas copiés.

## État

**Utilisé (version 0.1.2), disponible sur demande**

Utilisé au sein du studio et disponible sur demande pour les équipes qui travaillent avec plusieurs sessions d’IA. Pas de téléchargement public. Prévu : remplacer l’icône provisoire, signature de code et rafraîchissement par événements.

## À propos de ce dépôt

Ce dépôt ne contient que des informations : le code source est privé.

## Contact

- E-mail: hola@shaniawebstudio.com
- Site web: https://shaniawebstudio.com

---
*Un produit de Shania Webstudio.* · Copyright (c) 2026 Shania Webstudio.
