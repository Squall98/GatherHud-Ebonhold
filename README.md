# GatherHud (Ebonhold)

HUD de récolte en **vue 3D** pour WoW 3.3.5a (WotLK). GatherHud affiche les nœuds de
minage et d'herboristerie tout autour de ton personnage, en perspective, comme s'ils
étaient posés dans le monde devant toi. Idéal pour farmer en suivant ta route sans
quitter l'écran des yeux.

Cette version est une adaptation pour la communauté **Ebonhold** : traduction française
complétée et ajout d'une icône sur la minimap.

![Interface : 3.3.5a](https://img.shields.io/badge/WoW-3.3.5a-blue) ![Dépend de GatherMate](https://img.shields.io/badge/requiert-GatherMate-green)

## Ce que fait l'addon

- Affiche en **perspective 3D** les nœuds connus (minerai, herbes) autour de toi.
- Dessine ta **route Routes** directement dans le HUD (support optionnel).
- Réglages complets : angle de vue, rayon, taille et profondeur des icônes,
  transparence, position et largeur du HUD, indicateur du Nord.
- Raccourci clavier pour afficher/masquer le HUD à la volée.

## Nouveautés de cette version (v1.1.6-fr1)

Par rapport au GatherHud d'origine :

1. **Traduction française complétée** — toutes les options et descriptions sont en
   français (les dernières chaînes d'angle de caméra, non traduites à l'origine, le sont
   désormais). Le client frFR charge le français automatiquement.
2. **Icône sur la minimap** — comme les autres addons, une icône permet d'accéder aux
   réglages sans taper de commande :
   - **Clic gauche** : ouvre les options
   - **Clic droit** : active / désactive le HUD
   - Glisser pour la déplacer autour de la minimap
   - Option « Masquer l'icône minimap » dans les réglages
3. **Bibliothèques embarquées** (`LibDataBroker-1.1`, `LibDBIcon-1.0`,
   `CallbackHandler-1.0`, `LibStub`) — l'addon est autonome, l'icône fonctionne quel que
   soit l'ordre de chargement des autres addons.

## Installation

### Via le launcher Ebonhold (recommandé)
GatherHud apparaît dans le catalogue du launcher, catégorie **Carte & voyage**.
Un clic l'installe et le tient à jour.

### Manuelle
1. Télécharge le `.zip` depuis la section [Releases](../../releases).
2. Dézippe le dossier `GatherHud` dans `Interface\AddOns\`.
3. Relance le jeu (ou `/reload`).

## Dépendances

| Addon | Statut |
|-------|--------|
| **GatherMate** (v1) | Requis — fournit la base des nœuds |
| **GatherMate_Data** | Recommandé — nœuds pré-remplis |
| **Routes** | Optionnel — affiche la route de farm dans le HUD |

> À noter : cette version s'appuie sur **GatherMate** (première version), pas GatherMate2.

## Utilisation

- Tape `/gatherhud` ou clique sur l'icône minimap pour ouvrir les options.
- Assigne une touche pour basculer le HUD : `Échap` → `Touches` → **GatherHud**.
- Active « Charger les AddOns obsolètes » à l'écran de connexion si l'addon n'apparaît
  pas (il date de l'époque WotLK et peut être marqué obsolète à tort).

## Crédits & licence

- Addon original **GatherHud** par **Grum** et **Xinhuan** (WowAce / CurseForge).
- Traduction française initiale par **pettigrow**.
- Traduction complétée, icône minimap et adaptation Ebonhold par **Squall98**.

Les bibliothèques embarquées appartiennent à leurs auteurs respectifs et sont
redistribuées selon leurs licences d'origine. Ce dépôt redistribue GatherHud à des fins
communautaires ; tout le mérite du code original revient à ses auteurs.
