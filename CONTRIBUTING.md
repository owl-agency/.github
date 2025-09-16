# Contribuer aux projets Owl Agency

## Prérequis
- Node.js LTS (>= 18)
- Gestionnaire de packages : pnpm (recommandé)
- Installer les dépendances : `pnpm install`

## Branches
- **main** : code en production
- **develop** : intégration en cours
- **feature/** : nouvelles fonctionnalités
- **fix/** : corrections de bug
- **chore/** : maintenance, refactor, mise à jour de dépendances

## Conventions de commit
Format [Conventional Commits](https://www.conventionalcommits.org/):
```
<type>(scope): message
```
Exemples :
- `feat(auth): ajout du login OAuth`
- `fix(ui): corrige l'overflow sur mobile`
- `chore(deps): maj Firebase à vX`

## Avant de pousser
- Vérifier le lint : `pnpm lint`
- Vérifier les types : `pnpm type-check`
- Lancer les tests : `pnpm test`
