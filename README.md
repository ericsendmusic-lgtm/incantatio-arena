# Incantatio Arena

FPS multijoueur de sorciers : criez vos sorts dans le micro, farmez monstres et boss, récupérez des parchemins pour débloquer de nouveaux sorts. En coop ou chacun pour soi, jusqu'à 3 joueurs, avec chat vocal.

**Jouer :** https://ericsendmusic-lgtm.github.io/incantatio-arena/

## Classes et sorts

| Classe | Sorts (dans l'ordre de déblocage) |
|---|---|
| Feu et Destruction | Fireball, Hellfire, Blazing Orb, Solar Flare, Cinder Storm, Inferno Blast, Pyroclasm |
| Magie Spirituelle | Magic Spirit, Arcane Soul, Astral Wave, Phantom Bolt, Spirit Lance, Ethereal Pulse, Soulfire |
| Glace et Eau | Frostbolt, Ice Nova, Glacial Spike, Tidal Wave, Frozen Orb |
| Foudre et Tempête | Chain Lightning, Thunderstrike, Arcane Spark, Stormcaller |
| Ombre et Nécromancie | Shadow Bolt, Soul Drain, Dark Pact, Necrotic Touch |

Les sorts se crient en anglais. La reconnaissance (Moonshine) tourne dans le navigateur, y compris Firefox, et réagit en une fraction de seconde.

## Butin

- **Parchemin (halo doré)** : débloque le sort suivant de votre classe. Boss : 3 garantis ; brutes : 1 chance sur 3 ; petits monstres : 1 sur 10.
- **Potion (halo vert)** : +45 PV.
- **Cristal (halo bleu)** : +60 mana.
- Un boss toutes les 5 vagues : Golem des Ruines, Liche Écarlate, Wyrm des Ombres.

## Micro

- Bouton **Tester le micro** sur l'écran d'accueil (affiche ce qui est entendu et le % de ressemblance).
- **Clic droit maintenu** : parlez puis relâchez pour lancer, idéal s'il y a du bruit (ventilateur…).
- Casque avec micro conseillé.

---

# Mise en ligne sur GitHub Pages

Le jeu tient dans un seul fichier : `index.html`. Une fois en ligne, n'importe qui peut jouer avec le lien, sans compte.

## 1. Mettre le jeu en ligne (5 minutes, une seule fois)

1. Crée un compte gratuit sur **github.com** (si tu n'en as pas).
2. En haut à droite, clique sur **+** → **New repository**.
   - Nom : `incantatio-arena`
   - Coche **Public**
   - Clique sur **Create repository**.
3. Sur la page du dépôt, clique sur le lien **uploading an existing file**.
4. Glisse le fichier `index.html` dans la page, puis clique sur **Commit changes**.
5. Va dans **Settings** → **Pages** (menu de gauche).
   - **Source** : *Deploy from a branch*
   - **Branch** : `main` et `/ (root)` → **Save**.
6. Attends 1 à 2 minutes, puis recharge la page **Pages** : l'adresse du jeu s'affiche, du genre
   `https://ton-pseudo.github.io/incantatio-arena/`

## 2. Jouer à plusieurs

1. Ouvre le jeu dans **Chrome** ou **Edge**, choisis ta classe et clique sur **Créer une partie**.
2. Autorise le micro quand le navigateur le demande.
3. Le code de la partie s'affiche en haut à droite (ex. `k7f2q`). Appuie sur **Échap** puis sur **Copier le lien d'invitation** et envoie-le à tes amis.
4. Tes amis ouvrent le lien, choisissent leur classe et cliquent sur **Rejoindre**. Ils peuvent aussi ouvrir l'adresse du jeu et taper le code.

Maximum 3 sorciers par partie. Le mode (Coop ou Chacun pour soi) est celui choisi par le créateur.

## 3. Bon à savoir

- **Casque conseillé** : sinon le micro capte les voix des autres et peut lancer leurs sorts à ta place.
- **Le créateur fait tourner la partie** (monstres, boss, parchemins). S'il ferme l'onglet, les autres continuent chacun seul.
- **Premier lancement** : le modèle vocal (environ 30 Mo) se télécharge une seule fois.
- **Si un ami n'arrive pas à rejoindre** : certains réseaux (école, entreprise, partage 4G) bloquent les connexions directes entre joueurs. Essayez avec un autre réseau.
- La mise en relation des joueurs passe par le serveur public gratuit de PeerJS. S'il est en panne, réessayez un peu plus tard.

## 4. Mettre à jour le jeu

Sur la page du dépôt : **Add file** → **Upload files**, glisse le nouveau `index.html` → **Commit changes**. Le site se met à jour en une minute.

## Touches

| Touche | Action |
|---|---|
| Clic gauche | Verrouiller la vue · petit trait blanc (attaque de base) |
| Z Q S D / W A S D | Se déplacer |
| Maj / Espace | Courir / sauter |
| V | Couper ou rallumer le micro (voix + sorts) |
| Clic droit maintenu | Parler puis relâcher pour lancer le sort |
| Crier le nom du sort | Lancer le sort |
| Entrée | Écrire une incantation au clavier |
| T | Chat écrit |
| Molette / 1–7 | Feuilleter le grimoire |
| Tab | Scores |
| Échap | Libérer la souris, copier le lien d'invitation |
