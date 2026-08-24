# Portfolio BTS SIO — Baptiste Bousser

Site statique (HTML/CSS/JS pur, aucune installation nécessaire) prêt à être publié sur **GitHub Pages**.

## Contenu
- `index.html` — Accueil
- `bts.html` — Présentation du BTS SIO
- `cv.html` — CV (+ `cv_baptiste_bousser.pdf` téléchargeable)
- `lettre.html` — Lettre de motivation
- `activites.html` — Stage, atelier, mobilité, projets
- `style.css`, `script.js` — styles et script partagés

## Mettre le site en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub, par exemple nommé `portfolio` (Réglages du dépôt : Public).
2. Mets tous les fichiers de ce dossier à la racine du dépôt (ne pas les mettre dans un sous-dossier), puis envoie-les :
   ```
   git init
   git add .
   git commit -m "Portfolio BTS SIO"
   git branch -M main
   git remote add origin https://github.com/<ton-pseudo>/portfolio.git
   git push -u origin main
   ```
3. Sur GitHub, va dans **Settings → Pages**.
4. Dans **Build and deployment**, choisis la source **Deploy from a branch**, sélectionne la branche `main` et le dossier `/ (root)`, puis clique sur **Save**.
5. Après une à deux minutes, ton site sera accessible à l'adresse :
   `https://<ton-pseudo>.github.io/portfolio/`

## Personnaliser
- Le texte de la lettre de motivation (`lettre.html`) est une trame : adapte le 2ᵉ et le 3ᵉ paragraphe selon chaque entreprise visée.
- Pour mettre à jour le CV téléchargeable, remplace `cv_baptiste_bousser.pdf` par une nouvelle version en gardant le même nom de fichier (ou modifie le lien dans `cv.html`).
- Les couleurs et polices se modifient dans les variables en haut de `style.css` (bloc `:root`).
