# Mise à jour de l’attribut occupation des sols de la base de données cadastrales : Etude de cas dans le département de l'Aude

![Licence](https://img.shields.io/badge/Licence-MIT-yellow)
![Python](https://img.shields.io/badge/Python-3.9+-3776AB)
![Plateforme](https://img.shields.io/badge/Visualisation-GitHub--Pages-blue)

---

## Présentation du projet
Ce projet s'inscrit dans une démarche de mise à jour de l’attribut Occupation du Sol (OS) associé aux parcelles cadastrales françaises.

L'objectif principal est de proposer une méthode reproductible permettant :

- d’intégrer plusieurs sources de données vectorielles (BD TOPO, BD FORÊT, RPG & RPG COMPLETE) et issues de la télédétection (OSO, COSIA) ;
- d’harmoniser leurs nomenclatures ;
- d’automatiser le processus de décision ,
- et de qualifier le niveau de confiance de la classification à l'échelle des parcelles ;

L’étude est menée sur un territoire test : le département de l’Aude, servant de cas d’application méthodologique.

---

## ⚙️ Démarche méthodologie
De manière générale, la démarche méthodologique repose sur l'harmonisation des nomenclatures des différents sources de données et l'application deux modèles d'arbitrages : Fusion décisionnelle par scoring et Arbre de décision. 

> **Evaluation de la fiabilité** : Un indice de confiance est calculé pour chaque parcelle. cet indice permet dans une certaine mesure d'identifier les zones nécessitant un contrôle ou une expertise complémentaire. 

---

## 🌐 Interface de Géo-visualisation
Le site web est hébergé via GitHub Pages et permet une consultation directe des résultats sans installation locale :  
[**Accéder à la Géo-visualisation interactive**](https://angeevrard.github.io/GEOLAB_GROUPE_3_MISE_A_JOUR_CADASTRE/)

---

## 📜 Licence
Ce projet est sous licence **MIT**. Consulter le fichier `LICENSE` pour les conditions de réutilisation.

---

## 👥 Equipe projet
**A. Sery, T. Liegeon, S. Mercier, M. Uozumi,**
***Master 2 Observation de la Terre et Géomatique (OTG),***
***Université de Strasbourg - Année universitaire 2025-2026***
