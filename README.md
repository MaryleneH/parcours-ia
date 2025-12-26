# Parcours IA 🚀

[![Build and Deploy](https://github.com/MaryleneH/parcours-ia/actions/workflows/quarto-publish.yml/badge.svg)](https://github.com/MaryleneH/parcours-ia/actions/workflows/quarto-publish.yml)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://maryleneh.github.io/parcours-ia)

> **Votre guide complet pour maîtriser l'Intelligence Artificielle**

Un site web Quarto complet dédié aux professionnels des données (statisticiens, économistes, data scientists) souhaitant approfondir leurs compétences en Intelligence Artificielle.

## 🎯 À Propos

**Parcours IA** propose une progression pédagogique structurée en trois niveaux :

- 🌱 **Niveau Débutant** : Fondamentaux de l'IA et du machine learning
- 🚀 **Niveau Intermédiaire** : Algorithmes avancés et deep learning
- 💎 **Niveau Expérimenté** : IA de pointe, transformers, et MLOps

## 📚 Contenu

### Parcours d'Apprentissage IA

- **Hub IA** : Point d'entrée pour choisir votre niveau
- **Modules progressifs** : Du débutant à l'expert
- **Exemples pratiques** : Code Python et R exécutable

### PM/Scrum pour l'IA

Méthodologies agiles adaptées aux projets d'IA :

- **Cadrage** : Définir le problème et les objectifs
- **Gouvernance** : Structure et prise de décision
- **Delivery** : Livraison itérative et continue

### New Romance

Section créative explorant les applications artistiques de l'IA :

- Génération d'images et d'art
- Écriture créative avec LLM
- Projets innovants et expérimentaux

### Exemples de Code

- **Python** : Analyse de données et machine learning avec Scikit-learn
- **R** : Régression linéaire et visualisations avec ggplot2

## 🚀 Démarrage Rapide

### Prérequis

- [Quarto](https://quarto.org/docs/get-started/) >= 1.4
- Python 3.11+ avec Jupyter
- R 4.3+ avec packages tidyverse

### Installation Locale

```bash
# Cloner le repository
git clone https://github.com/MaryleneH/parcours-ia.git
cd parcours-ia

# Installer les dépendances Python
pip install -r requirements.txt

# Installer les dépendances R (dans R console)
install.packages(c("tidyverse", "ggplot2", "dplyr", "broom", "caret"))

# Prévisualiser le site
quarto preview

# Ou générer le site statique
quarto render
```

### Déploiement

Le site est automatiquement déployé sur GitHub Pages via GitHub Actions lors de chaque push sur `main`.

## 🛠️ Technologies

- **[Quarto](https://quarto.org/)** : Framework de publication scientifique
- **Python** : Machine learning et data science
- **R** : Analyses statistiques et visualisations
- **GitHub Pages** : Hébergement
- **GitHub Actions** : CI/CD automatique

## 📖 Structure du Projet

```
parcours-ia/
├── _quarto.yml           # Configuration Quarto
├── index.qmd             # Page d'accueil
├── about.qmd             # À propos
├── styles.css            # Styles CSS personnalisés
├── ia/                   # Parcours d'apprentissage IA
│   ├── index.qmd         # Hub IA
│   ├── debutant.qmd      # Niveau débutant
│   ├── intermediaire.qmd # Niveau intermédiaire
│   └── experimente.qmd   # Niveau expérimenté
├── pm-scrum/             # Méthodologies de gestion de projet
│   ├── index.qmd         # Hub PM/Scrum
│   ├── cadrage.qmd       # Phase de cadrage
│   ├── gouvernance.qmd   # Gouvernance de projet
│   └── delivery.qmd      # Delivery et déploiement
├── new-romance/          # Section créative
│   ├── index.qmd         # Hub New Romance
│   ├── explore.qmd       # Projets inspirants
│   └── create.qmd        # Guides pratiques
├── examples/             # Exemples de code exécutable
│   ├── python-example.qmd # Notebook Python
│   └── r-example.qmd      # Notebook R
└── .github/
    └── workflows/
        └── quarto-publish.yml # CI/CD GitHub Actions
```

## 🎨 Caractéristiques

- ✅ **Design premium** : Camaïeu rose grisé avec CSS variables
- ✅ **Navigation intuitive** : Navbar avec recherche intégrée
- ✅ **Code exécutable** : Notebooks Python et R intégrés
- ✅ **Responsive** : Adapté mobile et desktop
- ✅ **SEO optimisé** : Métadonnées et structure sémantique
- ✅ **Déploiement automatique** : CI/CD avec GitHub Actions

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet
2. Créez une branche (`git checkout -b feature/amelioration`)
3. Committez vos changements (`git commit -m 'Ajout d'une fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/amelioration`)
5. Ouvrez une Pull Request

## 📝 Licence

Ce projet est open source et disponible pour la communauté.

## 👥 Auteurs

- **Marylene H.** - *Créatrice du projet* - [GitHub](https://github.com/MaryleneH)

## 🙏 Remerciements

- La communauté Quarto pour cet excellent framework
- Les contributeurs open source des bibliothèques utilisées
- La communauté IA/ML pour le partage de connaissances

## 📧 Contact

Pour toute question ou suggestion :

- Ouvrez une [issue](https://github.com/MaryleneH/parcours-ia/issues)
- Participez aux [discussions](https://github.com/MaryleneH/parcours-ia/discussions)

---

**🌟 Si ce projet vous est utile, n'hésitez pas à lui donner une étoile sur GitHub !**
