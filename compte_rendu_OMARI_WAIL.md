# COMPTE RENDU — ANALYSE DU DASHBOARD BANK CHURNERS

---

<div align="center">

![Photo OMARI WAIL](photo_omari_wail.jpg)

## OMARI WAIL
**Analyste de Données — ENCG Settat**
Université Hassan 1er — Settat, Maroc

</div>

---

## 📋 Informations Générales

| Champ              | Détail                                          |
|--------------------|-------------------------------------------------|
| **Nom & Prénom**   | OMARI WAIL                                      |
| **Établissement**  | ENCG Settat — École Nationale de Commerce et de Gestion |
| **Université**     | Université Hassan 1er, Settat, Maroc            |
| **Fichier analysé**| `BankChurners.csv`                              |
| **Date du rapport**| Mars 2025                                       |
| **Outils utilisés**| Python (Pandas), Excel (openpyxl), HTML (Chart.js) |

---

## 🎯 Objet du Compte Rendu

Ce compte rendu présente les résultats de l'analyse du comportement des clients bancaires à travers le fichier **BankChurners.csv**, comprenant **10 127 entrées clients**. L'objectif principal est d'identifier les facteurs d'attrition (churn) et de proposer une lecture analytique des indicateurs clés de performance (KPI) à travers deux dashboards produits : un **dashboard HTML interactif** et un **dashboard Excel professionnel**.

---

## 📊 Indicateurs Clés de Performance (KPI)

| KPI | Valeur |
|-----|--------|
| 🧑‍🤝‍🧑 **Total Clients** | 10 127 |
| ✅ **Clients Actifs (Existing)** | 8 500 |
| ❌ **Clients Churners (Attrited)** | 1 627 |
| 📉 **Taux de Churn** | **16,1 %** |
| 💳 **Limite de Crédit Moyenne** | **8 632 $** |
| 💰 **Montant de Transactions Moyen** | **4 404 $** |
| 📊 **Taux d'Utilisation du Crédit Moyen** | **27,5 %** |

---

## 🔍 Analyse des Résultats

### 1. Répartition par Statut d'Attrition

Sur les **10 127 clients** analysés :
- **83,9 %** sont des clients actifs (8 500 clients)
- **16,1 %** ont résilié leur relation bancaire (1 627 clients churners)

> ⚠️ Un taux de churn de **16,1 %** représente un signal d'alarme significatif pour la banque, nécessitant des actions préventives ciblées.

---

### 2. Répartition par Genre

| Genre   | Nombre | Proportion |
|---------|--------|------------|
| Femmes  | 5 358  | 52,9 %     |
| Hommes  | 4 769  | 47,1 %     |

La base clientèle est légèrement dominée par les **femmes (52,9 %)**.

---

### 3. Répartition par Type de Carte Bancaire

| Carte     | Nombre | Proportion |
|-----------|--------|------------|
| Blue      | 9 436  | 93,2 %     |
| Silver    | 555    | 5,5 %      |
| Gold      | 116    | 1,1 %      |
| Platinum  | 20     | 0,2 %      |

La carte **Blue** domine très largement le portefeuille (93,2 %), tandis que les cartes premium (Gold, Platinum) restent marginales. La **limite de crédit moyenne par carte** est corrélée positivement au niveau de la carte :

| Carte     | Crédit Moyen |
|-----------|--------------|
| Blue      | 7 364 $      |
| Silver    | 25 278 $     |
| Gold      | 28 416 $     |
| Platinum  | 30 283 $     |

---

### 4. Répartition par Niveau d'Éducation

| Niveau d'Éducation | Clients | Churners |
|--------------------|---------|----------|
| Graduate           | 3 128   | 487      |
| High School        | 2 013   | 306      |
| Inconnu            | 1 519   | 256      |
| Sans diplôme       | 1 487   | 237      |
| College            | 1 013   | 154      |
| Post-Graduate      | 516     | 92       |
| Doctorat           | 451     | 95       |

Les clients de niveau **Graduate** représentent la majorité des churners en valeur absolue (487), mais ce phénomène s'explique par leur poids dans la base totale. Le taux de churn relatif reste comparable entre les niveaux d'éducation.

---

### 5. Répartition par Catégorie de Revenu

| Revenu          | Clients | Proportion |
|-----------------|---------|------------|
| Moins de 40K$   | 3 561   | 35,2 %     |
| 40K$ – 60K$     | 1 790   | 17,7 %     |
| 80K$ – 120K$    | 1 535   | 15,2 %     |
| 60K$ – 80K$     | 1 402   | 13,8 %     |
| Inconnu         | 1 112   | 11,0 %     |
| Plus de 120K$   | 727     | 7,2 %      |

La majorité des clients ont un revenu **inférieur à 40 000 $** (35,2 %), ce qui explique la forte proportion de cartes Blue dans le portefeuille.

---

### 6. Distribution par Tranche d'Âge

| Tranche d'Âge | Clients |
|---------------|---------|
| 21 – 30 ans   | 265     |
| 31 – 40 ans   | 2 132   |
| 41 – 50 ans   | 4 652   |
| 51 – 60 ans   | 2 673   |
| 61 – 70 ans   | 404     |
| 71 – 80 ans   | 1       |

La tranche **41–50 ans** est la plus représentée (45,9 %), ce qui constitue le cœur de la clientèle bancaire active.

---

## 💡 Recommandations Stratégiques

1. **Réduction du Churn** : Mettre en place des programmes de fidélisation ciblés pour les clients à risque, notamment ceux inactifs depuis plus de 3 mois (variable `Months_Inactive_12_mon`).

2. **Montée en Gamme** : Encourager la migration des clients Blue vers des cartes Silver/Gold afin d'augmenter la limite crédit et réduire le risque de churn.

3. **Segmentation par Revenu** : Proposer des offres adaptées aux clients à faibles revenus (< 40K$) qui constituent 35 % de la base.

4. **Ciblage par Âge** : Développer des services digitaux pour la tranche 31–40 ans, segment à fort potentiel de croissance et d'engagement.

5. **Surveillance des Clients Inactifs** : Alerter les équipes commerciales sur les clients ayant un taux d'utilisation du crédit proche de zéro, souvent précurseur du churn.

---

## 📁 Livrables Produits

| Livrable | Format | Description |
|----------|--------|-------------|
| Dashboard interactif | `.html` | 9 graphiques Chart.js, KPI cards, tableau paginé |
| Dashboard professionnel | `.xlsx` | 4 onglets : Dashboard, Données Graphiques, Analyse Churn, Données Brutes |
| Compte rendu analytique | `.md` | Présent document |

---

## ✅ Conclusion

Cette analyse du fichier **BankChurners.csv** a permis de construire deux dashboards professionnels aux couleurs de l'**ENCG Settat** (vert `#006633` / or `#D4A017`), offrant une vision complète du portefeuille clients bancaires. Le taux de churn de **16,1 %** constitue le principal indicateur de vigilance, et les segmentations réalisées (genre, âge, revenu, éducation, carte) permettent d'orienter des stratégies de rétention client ciblées et efficaces.

---

<div align="center">

*Compte rendu rédigé par **OMARI WAIL***
*ENCG Settat — Université Hassan 1er*
*Mars 2025*

---

*© ENCG Settat — Tous droits réservés*

</div>
