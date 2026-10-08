# Contribuer

Ces règles valent pour tous les dépôts de `qmmorel-creator` qui n'ont pas leur propre `CONTRIBUTING.md`.

1. **Une demande = une issue**, avec un label de statut (`statut:backlog`, `statut:en-cours`, `statut:à-tester`,
   `statut:fait`).
2. **Branches** : travail sur une branche dédiée, partie de la branche d'intégration à jour (`develop` si le dépôt en a
   une, sinon `main`). `main` ne reçoit que du code validé.
3. **Commits et pull requests** : citer l'issue avec `Ref #N`. Pas de `Closes`, `Fixes` ni `Resolves` : l'issue est
   fermée après validation, pas à la fusion.
4. **Une pull request par lot**, fusionnée quand les contrôles sont verts.
5. **Publication** : aucune mise en production automatique ; elle se fait sur décision explicite.
6. **Aucun secret** (clé, jeton, mot de passe) dans un dépôt.

Les règles détaillées d'un dépôt sont dans son `CLAUDE.md`.
