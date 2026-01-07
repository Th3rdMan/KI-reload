# ⚠️ Projet Archivé ⚠️
## 🧠 KI-reload – Interface personnalisée pour Kraland Interactif (V6)

![Status](https://img.shields.io/badge/Status-Archivé-red)
![Maintenance](https://img.shields.io/badge/Maintenance-Non-lightgrey)
[![Version](https://img.shields.io/badge/Version-4.4.0-blueviolet?style=flat-square)](https://github.com/Th3rdMan/KI-reload)
[![Licence](https://img.shields.io/badge/Licence-MIT-green?style=flat-square)](./LICENSE)
[![Installer avec Tampermonkey](https://img.shields.io/badge/Tampermonkey-Installer-orange?style=flat-square&logo=greasemonkey)](https://greasyfork.org/fr/scripts/542019-kraland-avatars-personnalis%C3%A9s)

**KI-reload** est un script utilisateur pour [Tampermonkey](https://www.tampermonkey.net/) ou [Violentmonkey](https://violentmonkey.github.io/), conçu pour moderniser et améliorer l’interface du jeu **Kraland Interactif**.

> 🎯 Objectif : rendre l'interface plus claire, plus esthétique, sans altérer l'expérience d'origine.  
> 🛠️ Technologies : JavaScript, manipulation DOM, SVG inline, CSS injecté.

---

## ✨ Fonctionnalités principales

- 🎨 **Cadres de personnages**
  - Fond coloré selon la nation (transparence harmonieuse)
  - Bordure stylisée : ronde pour PJ, carrée pour PNJ
  - Redimensionnement uniforme (75×75px)
- 🗂️ **Fonction et domiciliation** sous le nom
  - Affichage stylisé avec icônes inline
- 🚨 **Surcouche "Wanted"**
  - Image superposée pour les personnages recherchés
- ⚡ **Optimisation**
  - `IntersectionObserver` pour charger les infos au bon moment
  - Mise en cache (`functionCache`) pour éviter les doublons
- 🧩 **Affichage structuré**
  - Séparateurs entre groupes
  - En-têtes arrondis et ombrés

---

## 📸 Captures d’écran

| Avant | Après |
|:-----:|:-----:|
| ![](https://i.ibb.co/Wp5RLVdg/image.png) | ![](https://i.ibb.co/KcQMYywC/image.png) |
| ![](https://i.ibb.co/Xf43gP5r/image.png) | ![](https://i.ibb.co/S4pvgvby/image.png) |

---

## 🚀 Installation

1. Installe une extension de type **userscript** :
   - [Tampermonkey (Chrome, Firefox)](https://www.tampermonkey.net/)
   - [Violentmonkey (Firefox, Libre)](https://violentmonkey.github.io/)
2. Installe le script via ce lien :
   - 👉 **[Installer KI-reload](https://greasyfork.org/fr/scripts/542019-kraland-avatars-personnalis%C3%A9s)**
