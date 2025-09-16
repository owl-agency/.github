# Owl Agency – Repo .github

Ce dépôt contient les **fichiers communautaires et standards** utilisés dans tous les dépôts `owl-agency`.

## 📚 Contenu
- **Code of Conduct** → `.github/CODE_OF_CONDUCT.md`
- **Contributing guide** → `.github/CONTRIBUTING.md`
- **Security policy** → `.github/SECURITY.md`
- **Issue templates** → `.github/ISSUE_TEMPLATE/`
- **Pull request template** → `.github/PULL_REQUEST_TEMPLATE.md`
- **Workflows communs** → `.github/workflows/`

## 🔧 Conventions transverses
- **Branches** : `main` (stable), `develop`, `feature/*`, `fix/*`, `chore/*`
- **Commits** : format [Conventional Commits](https://www.conventionalcommits.org)
- **Node** : LTS (>= 18), gestionnaire recommandé : pnpm
- **Qualité** : ESLint + Prettier doivent être OK avant chaque PR
- **Tests** : PR validée = tests passés sur CI

## 🛠 Utilisation
Pour que les templates et guides soient pris en compte :
1. Vérifier que le dépôt cible **n’a pas déjà son propre `.github`** qui écrase ces fichiers.
2. Les workflows doivent être copiés manuellement dans chaque projet si on veut les exécuter.

## 👤 Mainteneur
Ce dépôt est maintenu par [@owl-agency](https://github.com/owl-agency).
