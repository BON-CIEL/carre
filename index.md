\mainpage Documentation du programme principal
[TOC]

# Programme CCarre
## Objectifs
- Illustrer l'utilisation d'une classe C++ pour manipuler des objets g�om�triques.
- D�montrer les concepts de :
  - Constructeurs par d�faut et param�tr�s.
  - M�thodes de d�placement d'objets.
  - Gestion dynamique de la m�moire.
- Apprendre � manipuler des tableaux d'objets en C++.

## Avertissements
- Tous les fichiers sources doivent �tre soigneusement comment�s pour garantir leur lisibilit� et leur maintenabilit�.
- Les allocations dynamiques n�cessitent un nettoyage explicite pour �viter les fuites m�moire.

## Mod�lisation UML
- Utilisation de MagicDraw ou tout autre outil compatible UML pour visualiser la structure de la classe `CCarre` et ses relations.

## G�n�ration de la documentation
- Utilisation de **Doxygen** pour produire une documentation compl�te en HTML et PDF.

## Exemples Markdown
### Code principal
Voici un exemple de code extrait du programme principal :  
```cpp
#include "carre.h"

int main() {
    CCarre carre1; // Constructeur par d�faut
    CCarre carre2(10, 20, 30); // Constructeur param�tr�

    cout << "Carre 1 (par d�faut):" << endl;
    carre1.Afficher();

    cout << "Carre 2 (param�tr�):" << endl;
    carre2.Afficher();

    return 0;
}

|cellule 1|cellule 2|
|--------|--------|
| A | B |
| C | D |
Ce qui suit est un [lien](https://example.com/ "titre de lien optionnel").
*Texte en italique*
**Texte en gras**
\author Maxime Bonnevay
\date 2024
\version 0.1
Version g�n�r�e en HTML :