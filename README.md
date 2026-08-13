# 🔢 Atelier NumPy – Traitement de données de capteurs IoT

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

Découverte et manipulation des tableaux **NumPy** appliquées à des données de
capteurs IoT, en préparation d'un futur système de Machine Learning de
détection d'anomalies.

---

## 🧭 Contexte

Une entreprise dispose de plusieurs **capteurs** installés dans différents
bâtiments. Ces capteurs mesurent régulièrement la **température**, l'**humidité**,
la **pression** et la **consommation énergétique**.

Avant d'être transmises à un système de Machine Learning capable de **détecter
des situations anormales**, les données doivent être préparées et analysées.
Cet atelier pose les bases de ce traitement à l'aide de **NumPy**, la
bibliothèque de calcul numérique de référence en Python.

---

## 🎯 Objectifs

- Comprendre la différence entre **listes Python** et **tableaux NumPy**
- Créer des tableaux de différentes façons (zéros, uns, plages, aléatoire…)
- Explorer les propriétés d'un tableau (dimensions, forme, type)
- Maîtriser l'**indexation** et le **slicing**
- Utiliser le **filtrage booléen** pour détecter des situations inhabituelles
- Manipuler les **dimensions** (reshape, transposée, extraction)
- **Concaténer** des tableaux
- Réaliser du **calcul scientifique** (stats, standardisation, normalisation)
- Comprendre le **broadcasting**

---

## 📁 Structure du projet

```
atelier_numpy_iot/
│
├── atelier_numpy_iot.ipynb    # notebook principal de l'atelier
└── README.md
```

> Les données sont **générées directement dans le notebook** (aléatoirement ou
> à la main) : aucun fichier de données externe n'est nécessaire.

---

## ⚙️ Prérequis

- **Python 3.x**
- **VS Code** avec l'extension **Jupyter** (ou Jupyter Notebook / JupyterLab)
- La bibliothèque **numpy**

---

## 🚀 Installation et mise en place

1. **Cloner le dépôt**
```bash
   git clone https://github.com/khadija470/atelier_numpy_iot.git
   cd atelier_numpy_iot
```

2. **Créer et activer un environnement virtuel**
```bash
   python -m venv .venv

   # Windows (Git Bash)
   source .venv/Scripts/activate

   # Windows (PowerShell / CMD)
   .venv\Scripts\activate

   # Linux / macOS
   source .venv/bin/activate
```

3. **Installer les dépendances**
```bash
   pip install numpy notebook
```

4. **Ouvrir le notebook**

   Ouvrir `atelier_numpy_iot.ipynb` dans VS Code, puis sélectionner le **kernel**
   correspondant à l'environnement `.venv`.

---

## 📓 Contenu du notebook

Le notebook est organisé en **10 parties**, chacune documentée
(objectif, syntaxe, exemple) :

| Partie | Thème |
|--------|-------|
| 1 | Listes Python vs tableaux NumPy |
| 2 | Création des données |
| 3 | Exploration des tableaux |
| 4 | Indexation et slicing |
| 5 | Filtrage booléen (détection d'anomalies) |
| 6 | Manipulation des dimensions |
| 7 | Concaténation |
| 8 | Calcul scientifique |
| 9 | Broadcasting |
| 10 | Bonus |

---

## 🧠 Notions clés abordées

- **Vectorisation** : appliquer une opération à tout un tableau sans boucle
- **Création de tableaux** : `zeros`, `ones`, `full`, `eye`, `arange`, `linspace`, `random`
- **Reproductibilité** : `np.random.seed()`
- **Slicing avancé** : sélection par plage, par pas, par condition
- **Statistiques** : `min`, `max`, `sum`, `mean`, `median`, `var`, `std`
- **Standardisation** et **normalisation Min-Max**
- **Broadcasting** : opérations entre tableaux de formes différentes

---

## 👩‍💻 Auteur

**Khadija Ngom** — Atelier réalisé dans le cadre d'une formation en
Intelligence Artificielle.
