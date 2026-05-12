# Site personnel - Bastien Lechardoy

Template de site personnel construit avec Jekyll et deployable facilement sur
GitHub Pages.

## Lancer en local

```bash
bundle install
bundle exec jekyll serve
```

Le site sera disponible sur `http://localhost:4000`.

## Deployer avec GitHub Pages

1. Creer un depot GitHub, par exemple `myblog`.
2. Pousser le projet :

```bash
git add .
git commit -m "Create personal website"
git branch -M main
git remote add origin https://github.com/blechardoy/myblog.git
git push -u origin main
```

3. Dans GitHub, ouvrir `Settings` puis `Pages`.
4. Dans `Build and deployment`, choisir `Deploy from a branch`.
5. Selectionner la branche `main` et le dossier `/root`.
6. Enregistrer.

L'URL sera generalement :

```text
https://blechardoy.github.io/myblog/
```

Pour utiliser `https://bastien-lechardoy.net`, configurer le domaine dans
`Settings > Pages > Custom domain`, puis ajouter les enregistrements DNS
indiques par GitHub.
