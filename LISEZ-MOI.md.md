# Mettre le portfolio en ligne sur GitHub Pages

Ce dossier contient votre site complet : `index.html`, le dossier `media/` (vidéos, captures, diplômes masqués, image d'aperçu) et `robots.txt`.
GitHub Pages l'héberge gratuitement, en HTTPS, sans publicité et sans quota qui mettrait le site en pause.

## 1. Créer un compte GitHub
- Allez sur https://github.com/signup et créez un compte.
- Choisissez bien votre nom d'utilisateur : il devient l'adresse du site.
  Exemple : `pierresylva` donne `https://pierresylva.github.io`.

## 2. Créer le dépôt du site
- En haut à droite : **+** puis **New repository**.
- **Repository name** : exactement `pedy99-ia.github.io` .
- Cochez **Public**, puis **Create repository**.

## 3. Envoyer les fichiers
- Sur la page du dépôt, cliquez sur le lien **uploading an existing file**.
- Ouvrez le dossier décompressé et glissez **son contenu** (le fichier `index.html`, le dossier `media` et `robots.txt`) dans la fenêtre. Ne glissez pas le dossier parent lui-même : `index.html` doit être à la racine.
- Attendez la fin de l'envoi (environ 30 Mo), puis cliquez sur **Commit changes**.

## 4. Activer le site
- Onglet **Settings** puis **Pages** dans le menu de gauche.
- **Source** : *Deploy from a branch*. **Branch** : `main`, dossier `/ (root)`, puis **Save**.
- Après 1 à 2 minutes, le site est en ligne à `https://pedy99-ia.github.io`.

## 5. Aperçu LinkedIn
Déjà réglé pour l'adresse `https://pedy99-ia.github.io`. Vous pouvez vérifier l'aperçu sur https://www.linkedin.com/post-inspector/

## 6. Votre propre nom de domaine (facultatif)
- Achetez un domaine (ex. `pierresylva.com`) chez un registraire : OVHcloud, Gandi, Namecheap… environ 10 à 15 € par an.
- Dans GitHub : **Settings > Pages > Custom domain**, tapez votre domaine, **Save**.
- Chez le registraire, dans la zone DNS, ajoutez :
  - 4 enregistrements **A** pour le domaine nu vers `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
  - 1 enregistrement **CNAME** `www` vers `pedy99-ia.github.io`
  (Vérifiez ces valeurs sur la page d'aide GitHub « Managing a custom domain for your GitHub Pages site ».)
- Une fois le domaine validé, cochez **Enforce HTTPS**.
- Demandez alors à Claude de mettre à jour l'adresse dans `index.html` (lignes og:image, og:url, canonical).

## 7. Être trouvé sur Google (facultatif)
- Le site est autorisé à l'indexation. Pour accélérer, déclarez-le sur https://search.google.com/search-console
- Mettez le lien sur LinkedIn, dans votre CV et votre signature d'e-mail : c'est ce qui le fait connaître.

## Mettre le site à jour
Remplacez simplement les fichiers modifiés : **Add file > Upload files**, glissez la nouvelle version, **Commit changes**.

## À savoir
Le site est public : votre e-mail et votre téléphone y sont visibles par tous. Les diplômes affichés ont leurs données personnelles masquées.
