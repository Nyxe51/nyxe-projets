# Nyxe Projets

Petite app web pour suivre tes projets : statuts, 3 projets épinglés, prochaine action, avancement, catégories, sauvegarde manuelle.
Aucun code à toucher : ce sont de simples fichiers.

## Fichiers (tous à la racine, ne pas les mettre dans un dossier)

- `index.html` : l'app
- `manifest.webmanifest`, `sw.js` : installation sur l'écran d'accueil et mode hors ligne
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` : ton logo

## Option 1 : GitHub puis Netlify (recommandé)

1. Sur github.com, crée un nouveau dépôt (New repository), par exemple `nyxe-projets`.
2. Dans le dépôt : **Add file → Upload files**, envoie les 6 fichiers (dézippés), puis **Commit changes**.
3. Sur app.netlify.com : **Add new site → Import an existing project → GitHub**, choisis le dépôt.
4. Laisse les champs de build vides (pas de commande de build, dossier à publier : `.`), puis **Deploy**.
5. Chaque fois que tu modifies un fichier sur GitHub, Netlify republie tout seul.

## Option 2 : Netlify seul

Sur app.netlify.com/drop, envoie le dossier dézippé (ça marche surtout depuis un ordinateur).

## L'installer comme une app sur iPhone

Ouvre ton adresse Netlify dans **Safari**, touche Partager, puis **Sur l'écran d'accueil**.

## Important : tes données

- Elles restent **sur ton téléphone** (stockage du navigateur), pas sur un serveur.
- Va de temps en temps dans **Stats → Sauvegarder** : ça crée un fichier `.json`. **Restaurer** le recharge.
- Changer d'appareil ou effacer les données de Safari efface la liste : d'où la sauvegarde.
- Les projets de la version hébergée chez Claude ne passent pas tout seuls ici : sauvegarde là-bas, restaure ici.
