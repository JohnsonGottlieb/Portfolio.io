# Portfolio — Jeremiah Assiba Gottlieb Johnson

Site portfolio statique (HTML, CSS, JavaScript) pour présenter le parcours, les compétences et les projets.

## Aperçu local

Ouvrir `index.html` dans un navigateur, ou servir le dossier avec un serveur HTTP local :

```bash
npx --yes serve .
```

## Publier sur GitHub Pages

1. Sur [github.com/JohnsonGottlieb](https://github.com/JohnsonGottlieb), créer un dépôt (par exemple `portfolio` ou `Portffolio.io`). Laisse le dépôt vide (sans README) si tu pousses un dépôt Git déjà initialisé localement.
2. Lier le dépôt distant et pousser (adapte l’URL et le nom du dépôt) :

```powershell
cd "c:\Users\johns\OneDrive\Document\Portffolio.io"
git branch -M main
git remote add origin https://github.com/JohnsonGottlieb/NOM_DU_DEPOT.git
git push -u origin main
```

3. Activer Pages avec le workflow inclus : **Settings → Pages → Build and deployment → Source** : **GitHub Actions**. La première poussée sur `main` (ou `master`) lance le déploiement.

Si le dépôt s’appelle par exemple `portfolio`, le site sera en général à `https://johnsongottlieb.github.io/portfolio/`. L’URL exacte est indiquée dans l’onglet **Pages** du dépôt et dans le résumé du job **Deploy to GitHub Pages**.

**Alternative** : au lieu de GitHub Actions, tu peux choisir **Deploy from a branch**, branche `main`, dossier `/ (root)` — dans ce cas le fichier `.github/workflows/static.yml` est ignoré pour le build mais reste dans le dépôt.

## README de profil GitHub (optionnel)

Pour un encart sous ton avatar, crée un dépôt **public** nommé exactement `JohnsonGottlieb` (identique au pseudo) et ajoute-y un `README.md` avec une courte présentation, tes liens (portfolio, e-mail) et des badges ou sections « En cours d’apprentissage » — GitHub l’affiche automatiquement sur ton profil.

## Personnalisation

- Contenu et liens : `index.html`
- Apparence : `styles.css`
- Menu mobile : `script.js`
