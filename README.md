# Snowriiide (SnowRide)

Projet ING2 de Théorie des graphes (semestre 1, 2026-2027) : gestion d'un domaine skiable en Java.
Le domaine est modélisé par des graphes ; l'application permet aux gestionnaires de mettre à jour l'état des pistes et remontées, et aux usagers de rechercher itinéraires et parcours de glisse.

Rendu final : **07/12/2026** — soutenances : semaine du 14/12/2026.

## Structure

```
src/main/java/snowride/
  model/       classes métier (domaine, pistes, remontées, graphe)
  algo/        algorithmes de recherche d'itinéraires et de parcours
  io/          chargement / validation des fichiers de données
  controller/  contrôleurs (MVC)
  view/        interface console (MVC)
src/test/java/snowride/   tests
data/domaines/            fichiers de données des domaines skiables
docs/livrables/           cahier des charges, diagrammes, plan de tests
```

Contraintes du sujet : Java, POO, packages cohérents, MVC (moteur séparé de l'IHM), plusieurs domaines chargés depuis des fichiers, gestion des exceptions, javadoc.

## Équipe

- Aksel
- _à compléter_
- _à compléter_

## Workflow Git

- Une branche par fonctionnalité (`feature/...`), merge dans `main` via pull request.
- Commits réguliers, chacun avec son propre compte : l'historique sert de preuve de participation dans le rendu final.
