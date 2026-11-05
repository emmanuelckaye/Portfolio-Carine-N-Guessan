# Portfolio — Carine N’Guessan

Site portfolio statique, responsive et prêt à être publié sur GitHub Pages.

## Contenu du ZIP
- `index.html` : accueil avec composition visuelle, sélection de projets et CTA.
- `apropos.html` : présentation, démarche, parcours et objectifs.
- `projets.html` : galerie avec filtres interactifs.
- `projet.html` : page d’étude de cas dynamique pour chaque projet.
- `competences.html` : domaines créatifs et logiciels.
- `contact.html` : formulaire validé qui prépare un email via le logiciel de messagerie.
- `404.html` : page d’erreur personnalisée.
- `styles.css` : styles et responsive design.
- `script.js` : menu mobile, filtres, pages projet, animations et contact.
- `projects.js` : contenu des projets, catégories, images et études de cas.
- `assets/images/` : images locales WebP et illustration de remplacement.

## Important à personnaliser
1. Remplacez `assets/images/portrait-placeholder.svg` par votre portrait personnel (gardez le nom ou modifiez les références HTML).
2. Remplacez les images de démonstration dans `assets/images/` par vos véritables réalisations. Les visuels actuels sont des concepts illustratifs et ne sont pas des commandes réelles.
3. Modifiez les projets, textes, catégories, descriptions et outils dans `projects.js`.
4. Ajoutez vos liens Instagram, Behance et LinkedIn dans `contact.html` et `index.html`.
5. Conservez uniquement les logiciels et compétences que vous utilisez réellement.

## Modifier un projet
Dans `projects.js`, chaque projet possède `id`, `title`, `category`, `image`, `alt`, `intro`, `role`, `tools`, `context`, `objective`, `concept`, `process` et `learning`. Pour changer son image, remplacez le fichier dans `assets/images/` et mettez à jour la propriété `image`.

Catégories des filtres : `identite`, `affiche`, `evenementiel`, `photo`, `video`, `personnel`.

## Formulaire de contact
Le formulaire valide les champs et utilise `mailto:` pour préparer un email à `carineguessan06@gmail.com`. L'envoi n'est pas automatique : le visiteur doit confirmer l'envoi dans son application de messagerie. Pour un véritable envoi depuis le site sans application mail, il faudra connecter un service de formulaire ou un backend.

## Publication gratuite sur GitHub Pages
1. Créez un dépôt GitHub, par exemple `carine-guessan-portfolio`.
2. Téléversez tous les fichiers et le dossier `assets` à la racine du dépôt.
3. Ouvrez **Settings → Pages**.
4. Dans **Build and deployment**, sélectionnez **Deploy from a branch**.
5. Choisissez la branche `main` et le dossier `/ (root)`, puis cliquez sur **Save**.
6. GitHub affichera l'adresse du site après le déploiement.

Le site n'utilise pas de serveur ni de compilation : les fichiers HTML, CSS, JS et images sont servis directement par GitHub Pages. Les polices Google nécessitent une connexion ; des polices de secours sont prévues.
