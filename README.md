# EDU_KI — site vitrine (one-page, DE)

Projet Astro pour la landing page de Gilles F. (KI-Facilitator & Trainer).

## Structure
- `src/content/home.md` — **tout le texte du site**, éditable directement (frontmatter YAML). C'est le seul fichier à toucher pour changer un texte.
- `src/pages/index.astro` — le gabarit (structure HTML/CSS/JS). Ne pas modifier pour un simple changement de texte.
- `astro.config.mjs` — configuration Astro (minimale)
- `netlify.toml` — indique à Netlify comment construire le site (`npm run build` → dossier `dist/`)

## Modifier un texte
1. Ouvre `src/content/home.md`
2. Repère la ligne concernée (ex: `title: "Drei Wege, wie ich Menschen und Organisationen begleite"`)
3. Change uniquement le texte entre guillemets, garde les guillemets
4. Enregistre, puis pousse le fichier modifié sur GitHub — Netlify republie automatiquement

## Déploiement
Ce projet est fait pour être déposé sur GitHub, puis connecté à Netlify.
Netlify installera les dépendances et lancera la compilation automatiquement —
aucune installation locale de Node.js n'est nécessaire pour la mise en ligne.

## (Optionnel) Test en local
Si tu as Node.js installé et veux prévisualiser avant de publier :
```
npm install
npm run dev
```
