# Mission 01 — Refonte du site DSR Agency

> **Première mission du trio.** Démonstration concrète de l'orchestration Hermes : Dysia cadre → Sérys crée → Rylia déploie & diffuse, avec validations d'Édouard aux portes clés.

Ce document sert à la fois de **brief de mission** et d'**exemple de référence** pour toutes les missions futures. Il s'appuie sur la mémoire centrale DSR (offres, tarifs, outils, décisions actées).

---

## Cadre de la mission

| Élément | Valeur |
|---|---|
| **Objet** | Site DSR Agency sur `dsr-agency.com` (Hostinger Web Business) |
| **Type** | Site **vitrine** au départ (présentation + vente de services) |
| **Obligatoire** | CGV + mentions légales |
| **Flux technique** | Claude → GitHub → Hostinger (déjà acté) |
| **Paiement** | Stripe, acompte 33 % + solde 67 % |
| **Formations** | Réservation en ligne, créneaux mar/ven 14h–18h, paiement immédiat |
| **Ton** | Professionnel chaleureux, premium, concret — mots bannis DSR proscrits |

**Objectif business :** transformer un visiteur (artisan, commerce local, profession libérale, PME) en **prospect qualifié** (demande de devis / prise de contact), et présenter les offres avec crédibilité.

---

## Déroulé orchestré

### Porte 0 — Hermes initialise
Charge le contexte DSR + ce dossier `personas/`. Mode : **trio**. Ordre : Dysia → Sérys → Rylia.

### Étape 1 — DYSIA cadre (amont)
**Livrables attendus :**
- **Arborescence** du site vitrine. Proposition de base à valider :
  `Accueil · Services (Site vitrine / E-commerce / Automatisations IA / Formations) · Méthode · À propos · Contact/Devis · (Réservation formations) · CGV · Mentions légales`
- **Parcours visiteur → prospect** : où on rassure, où on prouve, où on appelle à l'action.
- **Hiérarchie des offres** : mettre en avant le **site vitrine (1 900 €)** comme produit d'appel (plus rapide à vendre/produire), puis e-commerce (2 500 €), automatisations (sur devis), formations.
- **Positionnement** : agence web augmentée par l'IA pour TPE/PME, sur-mesure à budget optimisé, sans les contraintes des agences traditionnelles — **sans employer les mots bannis**.
- **Brief de passation (Contrat A)** vers Sérys.

➡️ **Porte de validation Édouard** : arborescence + positionnement + hiérarchie des offres.

### Étape 2 — SÉRYS crée (milieu)
À partir du Contrat A validé :
- **Maquette et design** premium, cohérent avec l'univers DSR (sobre, crédible, pas de surcharge).
- **Textes** de chaque page, orientés bénéfice client, lisibles, sans jargon : Accueil (hero + promesse), pages Services (chaque offre = promesse, ce qui est inclus, déroulé, preuve, CTA), Méthode, À propos, Contact.
- **Page d'offre claire** par service (ex. « Site vitrine 1 900 € tout compris, sans abonnement » explicité proprement).
- **Mise en forme** CGV + mentions légales (à partir du cadre juridique fourni).
- **Charte** : couleurs, typographies, intégration du **logo DSR à l'identique**.
- **Note de passation (Contrat C)** vers Rylia (quoi déployer, quoi diffuser).

➡️ **Porte de validation Édouard** : design + textes (parti pris créatif).

### Étape 3 — RYLIA déploie & diffuse (aval)
À partir du Contrat C validé :
- **Déploiement** GitHub → Hostinger ; vérification du rendu et de la vitesse (PageSpeed).
- **Stripe** : configuration du flux acompte 33 % + solde 67 % (en attente du test technique du flux en 2 temps).
- **Réservation formations** : agenda en ligne, créneaux mar/ven 14h–18h, paiement immédiat.
- **Diffusion de lancement** : annonce du nouveau site sur les réseaux (LinkedIn expertise, Facebook/Instagram proximité), déclinée par plateforme, logo intégré.
- **Suivi** : tableau de bord Airtable + notifications Telegram.

➡️ **Porte de validation Édouard (obligatoire)** : **avant** mise en ligne publique, **avant** activation Stripe, **avant** toute publication. Rylia présente un plan/brouillon ; Édouard donne le feu vert.

### Porte finale — Hermes compile
Récapitulatif : site en ligne, offres présentées, paiement et réservation actifs, annonce diffusée. Liste des points restés en attente de validation ou de décision.

---

## Points de vigilance (mémoire DSR)
- **Stripe** : vérifier que le flux acompte 33 % + solde 67 % en 2 transactions liées est techniquement supporté avant de l'annoncer.
- **Hostinger Plan Agency** : à prendre pour les sites clients ; ici c'est le plan **Web Business** (site DSR perso).
- **Tunnel de devis automatique** (Phase 4) : ne pas l'intégrer maintenant, mais le prévoir dans l'arborescence (page Contact/Devis simple au départ).
- **CGV + mentions légales** : non négociables pour la mise en ligne.

## Critères de réussite
- Un visiteur comprend en moins de 10 secondes ce que fait DSR et pour qui.
- Chaque offre est claire (promesse, inclus, prix le cas échéant, CTA).
- Le parcours mène naturellement à une demande de devis ou un contact.
- Rendu premium et crédible, zéro mot banni, logo intact.
- Aucune action irréversible effectuée sans le feu vert d'Édouard.

---

*Cette mission illustre le fonctionnement standard du trio. Les missions suivantes (sites clients, automatisations, campagnes) suivent la même logique : Dysia cadre, Sérys crée, Rylia exécute & diffuse, Hermes coordonne, Édouard décide.*
