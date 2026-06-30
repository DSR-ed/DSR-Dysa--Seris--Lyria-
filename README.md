# DSR — Dysia · Sérys · Rylia (V6)

Univers des trois **égéries de DSR** (Digital Solutions Réseaux) et de leur orchestration par le super-agent **Hermes**.

Les égéries sont à la fois une **identité de marque** (personas) et des **agents IA** : elles incarnent les trois forces de l'agence et servent à produire les livrables DSR (site, réseaux, vidéo, automatisations).

## Les trois égéries

| | **Dysia** (D) | **Sérys** (S) | **Rylia** (R) |
|---|---|---|---|
| **Pôle** | Stratégie & Conseil | Création & Expérience | Automatisation & Diffusion |
| **Rôle** | Cadre, audite, architecture | Crée sites, branding, textes, UX | Automatise, déploie, diffuse |
| **Moment** | Amont | Milieu | Aval |
| **Visuel** | Cheveux bruns, palette bleu acier | Cheveux platine, palette champagne | Cheveux cuivrés, palette cuivre |

**Ordre canonique :** Dysia cadre → Sérys crée → Rylia exécute & diffuse. **Hermes** coordonne et garde la mémoire ; **Édouard** décide.

> **Acronyme D-S-R.** Les noms d'origine étaient Dysa · Seris · **Lyria** — « Lyria » commençait par L et cassait l'acronyme. Le passage à **Rylia** (R) le corrige ; Dysa→Dysia et Seris→Sérys harmonisent l'ensemble.

## Contenu du dépôt

- **`index.html`** — interface V6 « Cyborg Universe » : personnages, prompts réseaux (FB/Insta/LinkedIn), attitudes solo/duo/trio, script vidéo 8 s, et l'onglet **« Interactions & Hermes »**. Cache image local via IndexedDB.
- **`images/`** — références visuelles officielles : `Dysia.jpeg`, `Serys.jpeg`, `Rylia.jpeg`, et le logo `dsr-logo.png`.
- **`personas/`** — **source de vérité** des égéries pour Hermes : fiches détaillées (`.md`), configs machine (`.json`), modèle d'interactions, et première mission. Voir [`personas/README-personas.md`](personas/README-personas.md).

## Utilisation

- **Consulter / produire** : ouvrir `index.html` dans un navigateur (ou via GitHub Pages). Importer les planches, copier les blocs de prompts, exporter en PDF si besoin.
- **Piloter le trio (Hermes)** : charger `personas/hermes.json` (orchestration) + `personas/dysia.json`, `serys.json`, `rylia.json` (agents). Détails et scénarios dans `personas/interactions-hermes.md`.

## Règle logo DSR (absolue)

Le logo officiel `images/dsr-logo.png` ne doit **jamais** être déformé, recolorisé, remplacé ou modifié — toujours intégré à l'identique, dans l'interface comme dans tous les prompts image et vidéo.

## Continuité V5 → V6

La V6 conserve tout le travail V5 (identités visuelles, palettes, voix, attitudes, prompts, script vidéo) et ajoute : les **noms corrigés** (Dysia/Sérys/Rylia), des **rôles élargis** (Sérys = création complète ; Rylia = automatisation + diffusion), l'onglet **Interactions & Hermes**, et le dossier **`personas/`** prêt pour l'agent.

---

*DSR Agency — agence web augmentée par l'IA pour TPE/PME. Garder DSR au centre : premium, concret, crédible.*
