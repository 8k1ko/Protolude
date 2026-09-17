# 🚚 Protolude

Petit jeu vidéo créé dans le cadre du cours **Interactivité ludique**. Le joueur incarne un personnage qui doit réparer un camion abandonné pour terminer le niveau.

## 🔑 Prérequis

Pour gagner, le joueur doit récupérer le **pneu de secours** situé au début du niveau et l'apporter jusqu'au camion, à l'autre bout de la carte.

## 🎯 Interactions requises

- [x] **Ramasser le pneu** — en entrant en contact avec le pneu, celui-ci disparaît et le jeu enregistre que le joueur le possède désormais.
- [x] **Traverser le couloir de barrières** — une série de panneaux forme un couloir qui se rétrécit progressivement. Le joueur doit s'y faufiler sans toucher les parois.
- [x] **Réparer le camion** — une fois arrivé au camion avec le pneu en main, le joueur déclenche la fin du niveau (changement de scène = victoire). Sans le pneu, rien ne se passe au contact du camion.

## ⚠️ Élément pouvant faire échouer le joueur

Toucher l'une des barrières du couloir rétréci **recharge complètement le niveau** : le personnage retourne à son point de départ, le pneu réapparaît à son emplacement d'origine, et le joueur doit retenter la traversée.

## 🎮 Contrôles

| Touche | Action |
|---|---|
| `Z` `Q` `S` `D` (ou `W` `A` `S` `D`) | Déplacement |
| `Espace` | Sauter |
| Souris | Regarder autour |
