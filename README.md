# Incantatio Arena — mise en ligne sur GitHub Pages

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
- **Langue du micro** : « Anglais » reconnaît mieux les noms de sorts. Si ça accroche, essaie « Français ».
- **Le créateur fait tourner la partie** (monstres, boss, parchemins). S'il ferme l'onglet, les autres continuent chacun seul.
- **Firefox** : le chat vocal marche, mais pas la reconnaissance des sorts. Il faut alors les écrire avec **Entrée**.
- **Si un ami n'arrive pas à rejoindre** : certains réseaux (école, entreprise, partage 4G) bloquent les connexions directes entre joueurs. Essayez avec un autre réseau.
- La mise en relation des joueurs passe par le serveur public gratuit de PeerJS. S'il est en panne, réessayez un peu plus tard.

## 4. Mettre à jour le jeu

Sur la page du dépôt : **Add file** → **Upload files**, glisse le nouveau `index.html` → **Commit changes**. Le site se met à jour en une minute.

## Touches

| Touche | Action |
|---|---|
| Clic | Verrouiller la vue · trait magique de base |
| Z Q S D / W A S D | Se déplacer |
| Maj / Espace | Courir / sauter |
| V | Couper ou rallumer le micro (voix + sorts) |
| Crier le nom du sort | Lancer le sort |
| Entrée | Écrire une incantation au clavier |
| T | Chat écrit |
| Molette / 1–7 | Feuilleter le grimoire |
| Tab | Scores |
| Échap | Libérer la souris, copier le lien d'invitation |
