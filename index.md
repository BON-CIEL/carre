\mainpage Documentation du programme principal
[TOC]

# Programme CCarre
## Objectifs
- Illustrer l'utilisation d'une classe C++ pour manipuler des objets géométriques.
- Démontrer les concepts de :
  - Constructeurs par défaut et paramétrés.
  - Méthodes de déplacement d'objets.
  - Gestion dynamique de la mémoire.
- Apprendre à manipuler des tableaux d'objets en C++.

## Avertissements
- Tous les fichiers sources doivent être soigneusement commentés pour garantir leur lisibilité et leur maintenabilité.
- Les allocations dynamiques nécessitent un nettoyage explicite pour éviter les fuites mémoire.

## Modélisation UML
- Utilisation de MagicDraw ou tout autre outil compatible UML pour visualiser la structure de la classe `CCarre` et ses relations.

## Génération de la documentation
- Utilisation de **Doxygen** pour produire une documentation complète en HTML et PDF.

## Exemples Markdown
### Code principal
Voici un exemple de code extrait du programme principal :  
```cpp
#include "carre.h"

int main() {
    CCarre carre1; // Constructeur par défaut
    CCarre carre2(10, 20, 30); // Constructeur paramétré

    cout << "Carre 1 (par défaut):" << endl;
    carre1.Afficher();

    cout << "Carre 2 (paramétré):" << endl;
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
Version générée en HTML :