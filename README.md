# Projet DevOps – Déploiement CI/CD avec GitHub Actions

## Objectif
Ce projet contient une page HTML statique utilisée pour tester :
- Les actions Git (push, commit, branches)
- Un pipeline CI/CD avec GitHub Actions
- Le déploiement automatique via GitHub Pages
- Le fonctionnement d'un runner GitHub Actions


---

## Déploiement GitHub Pages
Le workflow GitHub Actions :
1. Se déclenche lors d’un `push` sur la branche `main`
2. Exécute les étapes définies dans `.github/workflows/`
3. Déploie automatiquement sur la branche `gh-pages`
4. Met la page en ligne via GitHub Pages
