<p align="center">
  <img src="https://github.com/user-attachments/assets/7d564981-cb81-43e7-819a-25ffcfc5bd72" width="40%" height="40%" alt="Binary Tree Illustration"/>
</p>

# 🌲 C - Binary Trees & Sorting Algorithms

## 🧠 Project Overview

Ce projet explore deux piliers fondamentaux de l'informatique : les **arbres binaires** et les **algorithmes de tri**, implémentés en langage C. Il vise à renforcer ta compréhension des structures de données non linéaires et de l'efficacité algorithmique.

Tu vas construire et manipuler des arbres binaires, explorer leurs différentes formes, et implémenter plusieurs algorithmes de tri tout en analysant leur complexité temporelle avec la notation Big O.

---

## 🎯 Objectifs pédagogiques

### Arbres binaires
- Définir ce qu’est un **arbre binaire** et le distinguer d’un **Binary Search Tree (BST)**
- Comprendre et implémenter les parcours : **pré-ordre**, **in-ordre**, **post-ordre**, **niveau**
- Expliquer les notions de **profondeur**, **hauteur** et **taille** d’un arbre
- Identifier les arbres **pleins**, **complets**, **parfaits** et **équilibrés**
- Comparer la complexité des opérations sur les arbres vs. les listes chaînées

### Algorithmes de tri
- Implémenter au moins **quatre algorithmes de tri différents**
- Évaluer l’efficacité via la **notation Big O**
- Choisir l’algorithme le plus adapté à un jeu de données donné
- Comprendre ce qu’est un algorithme de tri **stable**

---

## 🛠 Contraintes techniques

- Éditeurs autorisés : `vi`, `vim`, `emacs`
- OS : Ubuntu 20.04 LTS
- Compilateur : `gcc` avec les flags `-Wall -Werror -Wextra -pedantic -std=gnu89`
- Style de code : **Betty style** (`betty-style.pl`, `betty-doc.pl`)
- Pas de variables globales
- Maximum de 5 fonctions par fichier
- Tous les fichiers doivent se terminer par une nouvelle ligne
- Un fichier `README.md` est obligatoire
- Les fichiers d’en-tête doivent être protégés contre les inclusions multiples

---

## 🌳 Structure de données : Arbre binaire

```c
/**
 * struct binary_tree_s - Noeud d’un arbre binaire
 *
 * @n: Valeur entière stockée
 * @parent: Pointeur vers le parent
 * @left: Pointeur vers l’enfant gauche
 * @right: Pointeur vers l’enfant droit
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;   /* Binary Search Tree */
typedef struct binary_tree_s avl_t;   /* AVL Tree */
typedef struct binary_tree_s heap_t;  /* Max Binary Heap */
```

 ## 👥 Authors
- [Boubouche1709](https://github.com/Boubouche1709)
