# Incantatio Arena

FPS multijoueur de sorciers : criez vos sorts dans le micro, farmez monstres et boss, récupérez des parchemins pour débloquer de nouveaux sorts. En coop ou chacun pour soi, jusqu'à 3 joueurs, avec chat vocal.

**Jouer :** https://ericsendmusic-lgtm.github.io/incantatio-arena/

**Version précédente (sauvegarde) :** https://ericsendmusic-lgtm.github.io/incantatio-arena/backup/ — aussi sur la branche `backup-avant-etape3`.

## Classes et sorts

| Classe | Sorts (dans l'ordre de déblocage) |
|---|---|
| Feu et Destruction | Fireball, Hellfire, Blazing Orb, Solar Flare, Cinder Storm, Inferno Blast, Pyroclasm |
| Magie Spirituelle | Magic Spirit, Arcane Soul, Astral Wave, Phantom Bolt, Spirit Lance, Ethereal Pulse, Soulfire |
| Glace et Eau | Frostbolt, Ice Nova, Glacial Spike, Tidal Wave, Frozen Orb |
| Foudre et Tempête | Chain Lightning, Thunderstrike, Arcane Spark, Stormcaller |
| Ombre et Nécromancie | Shadow Bolt, Soul Drain, Dark Pact, Necrotic Touch |

Les sorts se crient en anglais. La reconnaissance (Moonshine) tourne dans le navigateur, y compris Firefox, et réagit en une fraction de seconde.

## Grimoire

Vous commencez avec **un sort tiré au hasard** dans votre école. Chaque parchemin ajoute **un autre sort au hasard** parmi ceux qui restent ; le grimoire liste vos sorts dans l'ordre où vous les avez appris (touches 1 à 7 = 1er à 7e sort de la liste). **L'incantation tourne** : chaque sort a un cycle de 4 phrases (ex. Blazing Orb : « Blazing Orb », « Molten Globe », « Ember Sun », « Lava Pearl »). Seule la phrase affichée dans le grimoire lance le sort ; après chaque lancer, le grimoire passe à la suivante : les 4 défilent dans un ordre mélangé, chacune une fois par tour, puis un nouveau tour recommence dans un autre ordre. Chaque phrase a ses 10 premiers essais d'apprentissage, et ce qui est appris reste propre à cette phrase.

## Histoire et campagne

L'Archimage Velkar a brisé le Cristal d'Harmonie. Le Golem (vague 5), la Liche (vague 10) et le Wyrm (vague 15) en gardent chacun un fragment : chaque victoire répare le cristal au centre de l'arène et débloque une page du récit (touche L pour l'écouter). À la vague 20, affrontez **Velkar** : il renvoie les sorts des cinq écoles, et quand il lance un **Mot de pouvoir**, criez la phrase affichée avant la fin de la barre pour l'étourdir. Ensuite, mode infini.

**Survie** : la vie remonte très lentement après 6 s sans dégâts ; criez **« Healing »** (ou H) pour échanger 30 mana contre 22 PV. **G** ouvre le guide du sorcier (tout est expliqué en jeu).

## Boss (toutes les 5 vagues, seuls avec leurs propres troupes)

- **Golem des Ruines** : lance des rochers sur un joueur au hasard — un cercle rouge marque l'impact, sortez-en ! Sous 50 % de vie, il en lance trois à la fois. Faible à la Glace.
- **Liche Écarlate** : vole à distance, garde toujours 4 serviteurs et ressuscite ceux qu'on abat (rayon vert). Tant que 3 serviteurs vivent, un bouclier d'âmes réduit ses dégâts subis de 75 %. Elle tire des orbes d'âme (cercle vert au sol).
- **Wyrm aux trois têtes** : tête de feu (faible à la Glace), de glace (faible au Feu) et d'ombre (faible à l'Esprit). Chaque tête crache un souffle en cône annoncé au sol. Le corps est invulnérable : tranchez les trois têtes en moins de 25 s après la première, sinon les têtes tombées repoussent.

## Faiblesses des monstres

Chaque monstre encaisse plus ou moins selon l'école de magie (chiffre jaune avec « ! » = faiblesse, petit chiffre gris = résistance ; le jeu l'annonce la première fois).

| Monstre | Faible contre | Résiste à |
|---|---|---|
| Diablotin | Glace ×1,5, Esprit ×1,25 | Feu ×0,5 |
| Goule | Esprit ×1,6, Feu ×1,25 | Ombre ×0,5 |
| Ogre | Foudre ×1,4, Ombre ×1,25 | Glace ×0,7 |
| Squelette archer | Esprit ×1,4, Foudre ×1,2 | Ombre ×0,6, Glace ×0,75 |
| Araignée des cryptes | Feu ×1,6, Glace ×1,25 | Ombre ×0,75 |
| Slime / Petit slime | Foudre ×1,6, Glace ×1,25 | Feu ×0,6 |
| Loup spectral | Esprit ×1,5, Feu ×1,2 | Ombre ×0,5, Glace ×0,75 |
| Golem des Ruines | Glace ×1,4 | Foudre ×0,5, Feu ×0,6 |
| Liche Écarlate | Esprit ×1,5, Feu ×1,25 | Ombre ×0,4 |
| Wyrm des Ombres | Esprit ×1,5, Glace ×1,25 | Ombre ×0,4 |

## Butin et survie

- **Pas de régénération de vie** : seules les potions soignent. La mana remonte très lentement.
- **Parchemin (rouleau scellé, faisceau doré)** : débloque le sort suivant de votre classe. Rare : boss 1 garanti (parfois 2), ogre 12 %, autres monstres 3,5 %.
- **Croix de soin (émeraude)** : +45 PV.
- **Cristaux de saphir** : +60 mana.
- **Rune de puissance (pierre noire, rune de feu)** : dégâts ×1,5 pendant 25 s.

## Monstres

Diablotin, Araignée des cryptes, Goule, Squelette archer (tire à distance, esquivez !), Slime (se divise), Loup spectral, Ogre.
Un boss toutes les 5 vagues : Golem des Ruines, Liche Écarlate, Wyrm des Ombres.

## Graphismes

Rendu physique (lumières réelles, reflets, ombres douces, rayons de lune, braises), bâton sculpté qui suit vos mouvements et change de couleur selon le sort, sorts en shaders (plasma de feu, éclairs fractals, cristaux de givre, sphères nécrotiques à tentacules), impacts avec onde de choc et traces au sol, araignée, goule et squelette archer sculptés, mages sculptés et animés (chapeau ou capuche, yeux lumineux, robe qui flotte, effets propres à chaque école).

## Ambiance

Musique médiévale générée en direct (touche **M** pour la couper), minicarte, chiffres de dégâts. Réglage **Graphismes** (Auto allège le décor si ça saccade).

## Micro

- Bouton **Tester le micro** sur l'écran d'accueil (affiche ce qui est entendu et le % de ressemblance).
- **Apprentissage par sort** : pour chaque sort, les 10 premières incantations dites quand sa page est ouverte dans le grimoire le lancent à coup sûr, et le jeu retient ce que le micro a entendu (progression affichée dans le grimoire). Un autre sort reconnu très nettement part quand même.
- **Clic droit après un sort raté** : le jeu retient ce qu'il a entendu pour le sort ouvert dans le grimoire.
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
| Espace | Sauter |
| Échap | Pause (solo : partie figée ; en ligne : déconnexion, puis « Se reconnecter » au même code) |
| V | Couper ou rallumer le micro (voix + sorts) |
| Clic droit | Après un raté : apprendre le mot entendu au sort ouvert |
| Crier le nom du sort | Lancer le sort |
| Entrée | Écrire une incantation au clavier |
| T | Chat écrit |
| Molette / 1–7 | Feuilleter le grimoire |
| Tab | Scores |
| Échap | Libérer la souris, copier le lien d'invitation |
