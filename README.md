# Snowriiide

## ⛷️ SNOWRIDE : GESTION D'UN DOMAINE SKIABLE EN JAVA

![Langage](https://img.shields.io/badge/langage-Java-orange)
![Projet](https://img.shields.io/badge/projet-ING2%20Th%C3%A9orie%20des%20graphes-blue)
![Statut](https://img.shields.io/badge/statut-en%20cours-yellow)

---

## 📖 Description du Projet

Projet de **Théorie des graphes** (ING2, semestre 1, 2026-2027) : une application Java qui simule la gestion d'un domaine skiable et aide les usagers à s'y déplacer.

Le domaine (pistes, remontées mécaniques, services) est **modélisé par des graphes**. Les gestionnaires mettent à jour l'état du domaine, les usagers recherchent des itinéraires et des parcours de glisse selon leurs critères. Le projet met en pratique la théorie des graphes, la programmation orientée objet et le patron **MVC**.

📅 Rendu final : **07/12/2026** · Soutenances : semaine du **14/12/2026**

---

## ✨ Fonctionnalités Principales

* **Gestion du domaine** : consulter le domaine, ouvrir/fermer une piste ou une remontée, étudier l'impact d'une fermeture sur l'accessibilité des zones.
* **Consultation usagers** : pistes et remontées disponibles en temps réel.
* **Recherche d'itinéraire** entre deux points du domaine.
* **Parcours de glisse**, avec ou sans retour au point de départ.
* **Critères multiples** : niveau des pistes, type de remontées, durée, longueur, état du domaine.
* **Multi-domaines** : chargement de plusieurs domaines depuis des fichiers texte.
* **Robustesse** : gestion des erreurs de saisie et des données incohérentes (exceptions).
* **Extension(s)** *(à définir)* : par exemple IHM graphique, multicritères, postes de secours, entretien des pistes.

---

## 🛠️ Technologies Utilisées

* **Langage** : Java
* **Architecture** : programmation orientée objet, design pattern **MVC**
* **Interface** : console (mode de base)
* **Tests** : JUnit *(à confirmer selon l'outil de build choisi)*
* **Documentation** : Javadoc

---

## 🗂️ Structure du Dépôt

```
src/main/java/snowride/
  model/        classes métier (domaine, pistes, remontées, graphe)
  algo/         algorithmes d'itinéraires et de parcours
  io/           chargement et validation des fichiers de données
  controller/   contrôleurs (MVC)
  view/         interface console (MVC)
src/test/java/snowride/   tests
data/domaines/            fichiers de données des domaines skiables
docs/livrables/           cahier des charges, diagrammes, plan de tests
```

---

## 🚀 Installation et Démarrage

### Prérequis

Vérifier qu'un JDK est installé (Java 17 ou plus recommandé) :

```bash
java -version
javac -version
```

### Compilation et exécution

*(à compléter une fois la classe principale et l'outil de build choisis)*

```bash
# exemple sans outil de build
javac -d out $(find src/main/java -name "*.java")
java -cp out snowride.Main
```

---

## 👥 Équipe

* Aksel
* *à compléter*
* *à compléter*

---

## 🔀 Workflow Git

* Une branche par fonctionnalité (`feature/...`), fusion dans `main` via pull request.
* Commits réguliers, chacun avec son propre compte : l'historique sert de preuve de participation dans le rendu final.
