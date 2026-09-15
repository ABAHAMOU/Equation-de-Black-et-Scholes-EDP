# Black-Scholes PDE Solver

Pricer d'options européennes (Call / Put) basé sur la résolution numérique de l'équation de Black-Scholes par la méthode des différences finies en C++, avec module de visualisation graphique SDL2.

## Technologies

* C++ (C++11 ou supérieur, Programmation Orientée Objet)
* SDL2 (Visualisation graphique 2D)
* Algorithme de Thomas (Résolution de systèmes tridiagonaux)

## Méthodes numériques

* Schéma implicite pour l'EDP réduite (Équation de la chaleur)
* Schéma de Crank-Nicolson pour l'EDP complète
* Analyse d'erreurs numériques et comparaison des méthodes

## Dépendances

* Compilateur C++ (`g++` ou `clang++`)
* Bibliothèque `SDL2`

## Lancement en local

1. Cloner le dépôt :
   ```bash
   git clone [https://github.com/ABAHAMOU/Equation-de-Black-et-Scholes-EDP.git](https://github.com/ABAHAMOU/Equation-de-Black-et-Scholes-EDP.git)
   cd Equation-de-Black-et-Scholes-EDP
   g++ -O3 main.cpp -lSDL2 -o black_scholes_solver
   ./black_scholes_solver
