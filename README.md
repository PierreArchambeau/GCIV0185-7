# Introduction

Le projet s’intéressera à l’étude du parcours instationnaire d’un constituant passif advecté par un fluide incompressible. Le domaine sera bidimensionnel.

# Approche générale

Les équations en jeu seront détaillées lors de la première séance. Une attention particulière sera portée à la compréhension physique du problème avant de passer à toute étape de résolution numérique.

Cette résolution numérique exploitera la méthode des volumes finis pour calculer l’évolution temporelle, dans un champ de vitesse, du champ du constituant selon une approche eulérienne. Le projet débutera avec des champs simples avant d’aborder des situations plus complexes. Cependant, dès le début, certaines propriétés devront utilement être vérifiées par le code.

La notion de condition limite sera discutée et il devra être possible d’utiliser une condition périodique.

# Objectifs

L’objectif principal de ce travail est de construire un outil de résolution par volumes finis d’une équation linéaire d’advection en 2D sur base d’un champ de vitesses connu, de le valider de manière objective et structurée, de l’appliquer sur différents sets de données pour ensuite faire preuve d’esprit critique dans l’analyse des résultats.

Les notions de reproductibilité/symétrie, de stabilité temporelle, et de précision du schéma spatial seront abordées avant toute simulation. Les résultats seront analysés et comparés.

# Rendus

Le projet consiste en un code complet en python sous la forme de modules et d’un Jupyter Notebook fonctionnel (qui servira de rapport dynamique exécuté indépendamment lors de la correction).

L’ensemble des codes sera uniquement hébergé sur le serveur : https://classroom.github.com/

Le travail sera réalisé par groupe de maximum 2 étudiants.

Une progression régulière est attendue et sera vérifiée par les apports successifs sur le serveur de chaque membre du groupe.

# Points d’attention

- Le code doit être écrit en Python3.
- Le code devra idéalement être réfléchi dès le départ sous la forme de fonctions simples paramétrées.
- Les copier/coller de parties de code seront à proscrire et à remplacer dans la mesure du possible par des fonctions.
- La résolution complète sera dans la mesure du possible une succession d’appels à ces fonctions.
- Une résolution par volumes finis en reconstruction constante et linéaire devra être possible.
- Seules des résolutions temporelles explicites seront utilisées (Euler et Runge-Kutta 22).
- Comme pour tout problème numérique, des choix assez radicalement différents sont possibles dans l’approche de programmation. Il est recommandé de débuter avec des approches simples et pragmatiques. Cependant, une réflexion sur des optimisations pertinentes est à prévoir et, dans la mesure du temps disponible, à implémenter pour en objectiver l’efficacité.
- La vitesse totale d’exécution sur un cas « non documenté » pourra servir lors de la correction.
