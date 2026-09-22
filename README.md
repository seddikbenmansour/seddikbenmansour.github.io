# seddikbenmansour.github.io

Portfolio personnel de Mohamed BENMANSOUR — Team Lead DevOps & IA Agentique.

## Structure

- `index.html` — page d'accueil (français)
- `en/index.html` — version anglaise
- `assets/style.css` — feuille de style partagée
- `assets/CV_BENMANSOUR_Mohamed_AgentsIA_2026.pdf` — CV téléchargeable

## Mettre en ligne (GitHub Pages)

1. Crée le dépôt GitHub `seddikbenmansour.github.io` (doit porter exactement ce nom pour être servi à la racine) :
   ```
   gh repo create seddikbenmansour.github.io --public --source=. --remote=origin
   ```
   (ou crée-le manuellement sur github.com, puis `git remote add origin git@github.com:seddikbenmansour/seddikbenmansour.github.io.git`)

2. Pousse le contenu :
   ```
   git push -u origin main
   ```

3. Sur GitHub : `Settings` → `Pages` → vérifier que la source est bien la branche `main` / dossier racine (souvent automatique pour un repo `<user>.github.io`).

4. Le site sera disponible sous quelques minutes à `https://seddikbenmansour.github.io/`.

## Mettre à jour le CV téléchargeable

Remplacer le fichier dans `assets/` par la nouvelle version du PDF, puis commit + push.
