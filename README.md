# DSL-Déménagements — Spécification produit

Dossier de référence de l'ERP de déménagement **DSL-Déménagements** : 16 chapitres,
de la vision produit au guide d'intégration vidéo.

## Contenu

- `spec.pdf` — document A4 paginé (29 pages), prêt à diffuser.
- `spec.html` — version HTML du même document, avec les captures en annexe.
- `assets/` — 13 captures de l'application déployée.

## Ce que couvre le document

| Chapitre | Sujet |
|---|---|
| 01 – 04 | Résumé exécutif, contexte métier, rôles, cartographie des 11 modules |
| 05 | Analyse module par module : objectif, fonctions, dictionnaires de données, règles, limites |
| 06 – 07 | Parcours utilisateurs et modèle de données (7 tables) |
| 08 – 11 | Architecture, design system, Mode Démo, sécurité et conformité |
| 12 – 14 | Audit de maturité, feuille de route en 3 phases, exploitation |
| 15 – 16 | Guide vidéo (storyboard, script) et annexes (routes, dépendances, captures, glossaire) |

## Source analysée

Bundle déployé le 5 novembre 2026 sur `blueviolet-fox-642747.hostingersite.com`,
alimenté par un jeu de démonstration. Les constats cités (statuts affichés en clé brute,
absence de `tenant_id`, Mode Démo actif par défaut) proviennent de la lecture du code.

## Application

- Démonstration : https://blueviolet-fox-642747.hostingersite.com/
- Domaine prévu : `digitalsolverland.space`
