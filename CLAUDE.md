# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Rôle de Claude

**David fait le jeu lui-même ; Claude l'aide** (demande de David, 2026-10-11). Par défaut, Claude conseille et ne code pas dans le projet Godot.

- Permis : expliquer, comparer des options, recommander, relire le code de David, répondre aux questions, rédiger la documentation (fiches `.cpt`, README, CLAUDE.md), gérer le suivi dans Nexus et les fichiers de dépôt.
- Les décisions de design reviennent à David : proposer des options, ne pas trancher à sa place.
- Avant d'écrire du code ou des fichiers de projet Godot, demander à David.

## Projet

**Axiomm Industries** : jeu de gestion d'une industrie galactique (Axiomm). Vue inspirée d'Idle Planet, profondeur de production inspirée de Satisfactory.

- Moteur : Godot **4.5**, GDScript. Plateforme : **Android**. But : publier.
- Clé Nexus : `axiomm`.
- Référence « Idle Planet » = Idle Planet Miner (Tech Tree Games).
- État : 0.2.0 (définir le jeu) en cours ; reste la synthèse (`t-g0d`). Dépôt public : github.com/David-Bambi/axiomm-industries. Aucun projet Godot pour l'instant.

## Documentation

Source de vérité : les fiches `.cpt` (format Concept) dans `docs/`, racine `axiomm-industries.cpt` (à la racine du dépôt : Concept n'accepte qu'une fiche `.cpt` au premier niveau du dossier enregistré). Utiliser la skill `documenter-cpt`. Garder la documentation à jour à chaque tâche.

Références externes :
- Game design : `/home/david/projets/6_documentation/documents_cpt/game_design`
- Godot : `/home/david/projets/6_documentation/documents_cpt/godot`
- Modules Godot réutilisables : `/home/david/projets/5_développement/godot_module`

## Suivi

Projet `axiomm` dans Nexus (outils MCP `mcp__nexus__*`). Feuille de route résumée dans `docs/feuille-de-route.cpt` ; garder Nexus et la fiche cohérents.
