# Portfolio — Jeremiah Assiba Gottlieb Johnson

Site portfolio statique (HTML, CSS, JavaScript) pour présenter le parcours, les compétences et les projets.

**Dépôt :** [github.com/JohnsonGottlieb/Portfolio.io](https://github.com/JohnsonGottlieb/Portfolio.io)

**Projet phare :** [MechAssist](https://github.com/JohnsonGottlieb/Mechassist) — application client / mécanicien (Flutter, Laravel, PostgreSQL, Firebase).

## Aperçu local

Ouvrir `index.html` dans un navigateur, ou servir le dossier avec un serveur HTTP local :

```bash
npx --yes serve .
```

## Publier sur GitHub Pages

1. **Settings → Pages → Build and deployment → Source** : **GitHub Actions** (workflow dans `.github/workflows/static.yml`).
2. Après un push sur `main`, le site est en général disponible à  
   `https://johnsongottlieb.github.io/Portfolio.io/`  
   (URL exacte indiquée dans l’onglet **Pages** du dépôt.)

**Alternative :** **Deploy from a branch** — branche `main`, dossier `/ (root)`.

## Pousser les changements depuis ta machine

```powershell
cd "c:\Users\johns\OneDrive\Document\Portffolio.io"
git remote set-url origin https://github.com/JohnsonGottlieb/Portfolio.io.git
git push -u origin main
```

## README de profil GitHub (optionnel)

Pour un encart sous ton avatar, crée un dépôt **public** nommé exactement `JohnsonGottlieb` et ajoute-y un `README.md` avec une courte présentation et le lien vers ce portfolio.

## Personnalisation

- Contenu : `index.html`
- Apparence : `styles.css`
- Menu mobile : `script.js`
