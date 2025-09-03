# 📊 Projet Actuariat Vie : Évaluation des Rentes Viagères


---

## 🎯 Introduction

L'objectif de ce projet est de **modéliser la mortalité et d’évaluer les rentes viagères** pour une cohorte d’assurés suisses nés en 1950 (70% femmes, 30% hommes).  
La problématique centrale : **comment tarifer des produits de rente viagère en tenant compte du risque de longévité et de la différence genrée** ?

---

## 🔍 Problématique

Les compagnies d’assurance doivent anticiper :

- La **mortalité future** des assurés.
- La **durée moyenne de versement des rentes**.
- L'impact des choix **genré vs unisexe** sur la valeur actuelle probable (VAP) des produits.

💡 L’analyse aide à **optimiser la tarification**, réduire le risque et améliorer la gestion financière des produits viagers.

---

## 📈 Méthodologie

1. **Source des données :** [Human Mortality Database (HMD)](https://www.mortality.org/)
2. **Extraction de la cohorte 1950** : hommes et femmes.
3. **Modélisation de la mortalité :**  
   - Utilisation du package **StMoMo** en R.  
   - Modèles stochastiques de type **Lee-Carter** pour projeter la mortalité jusqu’en 2040.
4. **Calcul de la valeur actuelle probable (VAP)** des rentes viagères.
5. **Comparaison genrée vs unisexe** pour mesurer l’impact sur la tarification.

---

## 🧰 Outils & Technologies

- **R** : langage principal pour l’analyse statistique.
- **Packages R :** `StMoMo`, `demography`, `forecast`, `fanplot`, `gnm`.
- **Sources de données :** Human Mortality Database.
- **Visualisation :** `ggplot2`, graphiques fan plot pour projection de mortalité.

---

## 📊 Résultats et Insights

- La mortalité projetée montre une **longévité croissante**, impactant directement le coût des rentes.
- Les rentes **genrées** sont légèrement plus chères pour les femmes, moins pour les hommes, mais **les rentes unisexes** permettent une **mutualisation du risque**.
- Les projections permettent d’identifier les années où la valeur actualisée des engagements sera la plus élevée.
- Ce projet fournit des **indicateurs précis pour la tarification et la gestion du risque actuariel**.

---

## 🔗 Liens Utiles

- [Human Mortality Database](https://www.mortality.org/)
- [Documentation StMoMo](https://cran.r-project.org/web/packages/StMoMo/StMoMo.pdf)
- [GitHub R Examples](https://github.com/cran/StMoMo)

---

## ⚡ À propos

Auteur : **Ahmed Trabelsi**  
Domaine : **Actuariat & Data Science**  
Année : 2025  
Objectif : **Optimiser la tarification des rentes viagères à travers la modélisation de la mortalité et l’analyse actuarielle.**

---

## 📌 Remarques

- Les résultats sont basés sur les données HMD et les modèles stochastiques, donc **sous réserve des hypothèses du modèle**.
- Ce projet illustre l’utilisation de la **data science dans l’actuariat** pour appuyer les décisions financières et produits d’assurance.
