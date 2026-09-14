# Family Budget Junior — prototype cliquable

**Version 0.3** — maquette interactive servant à valider les écrans et les règles métier **avant** développement.
Ce n'est pas l'application : aucune donnée réelle, aucun backend, aucun appel à une IA.

**Démo :** https://barbaag-arch.github.io/fbj-proto/

## V0.3 — convergence avec la maquette cliente

Reprend la direction visuelle et les bonnes idées de la maquette Figma Make du client, dans le cadre
fixé par le cahier des charges V1.0.

**Repris de la maquette cliente** — cagnotte familiale et camembert de répartition, conseils dépliables
par mission, écran « Bravo » avec confettis, objectif toujours visible dans l'en-tête, missions filtrées
par âge, fond clair avec Fredoka One / Outfit / DM Mono.

**Conservé du cahier des charges** — Parent-First (l'enfant ne choisit ni son âge ni son profil),
PIN 4 chiffres avec blocage après trois échecs, validation parentale avant tout crédit (C1),
détail enfant accessible sans PIN (C2), tirelire plafonnée et en attente (C3), avatars en SVG intégrés
(aucune URL externe, conformément à la charte graphique).

## Trois points à trancher

1. **Argent réel ou virtuel ?** Le cahier des charges V1.0 § 1 indique « 100 % virtuel, aucun paiement,
   aucune connexion bancaire ». La maquette cliente propose carte bancaire, Apple Pay, PayPal et virement
   vers un Livret A. Les deux hypothèses sont incompatibles et n'ont pas les mêmes conséquences
   réglementaires. Ce prototype suit le cahier des charges : la cagnotte est un suivi, pas un paiement.
2. **Quelle charte graphique ?** La charte décrit un thème sombre néon ; la maquette est claire et ludique.
   Ce prototype suit la maquette.
3. **Combien de tranches d'âge ?** Le cahier des charges en prévoit deux avec bascule à 8 ans ;
   la maquette en propose quatre sans changement d'interface. Ce prototype suit le cahier des charges.

## Contenu
- `index.html` — prototype autonome (HTML/CSS/JS, aucune dépendance hors polices Google)

## Avertissements
- Données fictives, stockées uniquement dans le navigateur du visiteur
- Code PIN de démonstration : `1234`
- Avatars et conseils provisoires · réponses du coach simulées

## Propriété intellectuelle
Conception et réalisation : **Andy BARBA**, 2026. Tous droits réservés.
Aucune cession de droits patrimoniaux n'est intervenue à ce jour. Toute reproduction, adaptation ou
exploitation de ce prototype, par le client ou par un tiers, suppose une cession écrite préalable.
