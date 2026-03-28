
<div align="center">

<img src="photo_omari_wail.jpg" alt="OMARI WAIL" width="150" style="border-radius:50%;" />

**Réalisé par**

# OMARI WAIL

*Étudiant — ENCG Settat — Université Hassan 1er*

---

# 📊 COMPTE RENDU ANALYTIQUE

## Dashboard Bank Churners — Analyse de la Rétention Client Bancaire

**Source** : BankChurners.csv · **10 127 clients** · **ENCG Settat**

</div>

---

---

## 1. Introduction

Le présent compte rendu synthétise les résultats de l'analyse du dashboard **Bank Churners**, réalisé dans le cadre du projet mené à l'ENCG Settat (Université Hassan 1er). L'objectif principal est d'identifier les facteurs d'attrition (churn) parmi les clients bancaires et de formuler des recommandations stratégiques pour améliorer la rétention.

L'étude porte sur un échantillon de **10 127 clients**, dont les données démographiques (genre, âge, niveau d'éducation), financières (revenu, limite de crédit, type de carte) et transactionnelles (montant des transactions, taux d'utilisation) ont été exploitées pour construire un tableau de bord interactif.

### 🎯 Objectifs de l'analyse

- Mesurer le taux d'attrition global et par segment.
- Identifier les profils clients les plus à risque de churn.
- Proposer des leviers d'amélioration de la fidélisation.

---

## 2. Indicateurs Clés de Performance (KPI)

Le dashboard met en évidence les métriques clés suivantes :

### Vue d'ensemble

| 🔢 Total Clients | ✅ Clients Actifs | ❌ Churners | ⚠️ Taux de Churn |
|:-:|:-:|:-:|:-:|
| **10 127** | **8 500** | **1 627** | **16,07%** |

| 👩 Femmes | 💳 Crédit Moyen | 💰 Trans. Moyenne | 📊 Utilisation Moy. |
|:-:|:-:|:-:|:-:|
| **52,9%** | **8 632 $** | **4 404 $** | **27,49%** |

### Tableau détaillé des indicateurs

| Indicateur | Valeur |
|:---|:---:|
| Total Clients | 10 127 |
| Clients Actifs | 🟢 8 500 (83,9%) |
| Clients Attrités (Churners) | 🔴 1 627 (16,1%) |
| **Taux de Churn Global** | **🔴 16,07%** |
| Clients Femmes | 5 358 (52,9%) |
| Clients Hommes | 4 769 (47,1%) |
| Limite de Crédit Moyenne | 8 632 $ |
| Montant Transactions Moyen | 4 404 $ |
| Taux d'Utilisation Moyen du Crédit | 27,49% |

> **Interprétation** : Le taux de churn de 16,07% signifie qu'environ **1 client sur 6** quitte la banque. Les clients actifs représentent 83,9% de la base totale.

---

## 3. Répartition par Niveau d'Éducation

Le niveau d'éducation constitue un facteur important dans le comportement d'attrition. Les diplômés (**Graduate**) représentent la plus grande proportion de la base client avec 3 128 individus, mais également le plus grand nombre de churners en valeur absolue (487). Les catégories **Uneducated** et **Doctorate** présentent des taux de churn proportionnellement plus élevés.

| Éducation | Nb Clients | Churners | Taux de Churn |
|:---|:---:|:---:|:---:|
| Graduate | 3 128 | 🔴 487 | 15,57% |
| High School | 2 013 | 🔴 306 | 15,20% |
| Unknown | 1 519 | 🔴 256 | 16,85% |
| Uneducated | 1 487 | 🔴 237 | 15,94% |
| College | 1 013 | 🔴 154 | 15,20% |
| Post-Graduate | 516 | 🔴 92 | 17,83% |
| Doctorate | 451 | 🔴 95 | 21,06% |

> **Point clé** : Les titulaires d'un Doctorat présentent le taux de churn le plus élevé par éducation (21,06%), ce qui peut indiquer des attentes plus élevées non satisfaites.

---

## 4. Répartition par Tranche de Revenu

La tranche de revenu inférieure à 40 000 $ concentre le plus grand nombre de clients (**3 561**, soit 35,2% de la base totale). Cela reflète une clientèle à dominante de revenus modestes. Les hauts revenus ($120K+) ne représentent que 7,2% de l'ensemble.

| Tranche de Revenu | Nb Clients | % du Total |
|:---|:---:|:---:|
| **Less than $40K** | **3 561** | **35,2%** |
| $40K - $60K | 1 790 | 17,7% |
| $80K - $120K | 1 535 | 15,2% |
| $60K - $80K | 1 402 | 13,8% |
| Unknown | 1 112 | 11,0% |
| $120K + | 727 | 7,2% |

> **Point clé** : Plus d'un tiers de la clientèle gagne moins de 40K$, ce qui oriente la stratégie produit vers des offres accessibles.

---

## 5. Analyse par Type de Carte Bancaire

La carte **Blue** domine très largement avec 93,2% des clients (9 436). Les cartes premium (Gold, Platinum) restent marginales en volume mais offrent des limites de crédit bien supérieures. La limite de crédit moyenne augmente considérablement avec le niveau de carte : de 7 364 $ (Blue) à 30 283 $ (Platinum).

| Type Carte | Nb Clients | % du Total | Crédit Moyen ($) |
|:---|:---:|:---:|:---:|
| 🔵 Blue | 9 436 | 93,2% | 7 364 |
| ⚪ Silver | 555 | 5,5% | 25 278 |
| 🟡 Gold | 116 | 1,1% | 28 416 |
| 💎 Platinum | 20 | 0,2% | 30 283 |

> **Point clé** : L'écart de crédit moyen entre Blue et Platinum est de x4,1 — les clients premium représentent une forte valeur individuelle.

---

## 6. Répartition par Tranche d'Âge

La tranche **41-50 ans** est la plus représentée avec 4 652 clients (45,9%), suivie par les 51-60 ans (26,4%). La banque possède donc une base client majoritairement composée d'adultes en milieu de carrière. Les jeunes (21-30 ans) ne représentent que 2,6% de la base.

| Tranche d'Âge | Nb Clients | % du Total |
|:---|:---:|:---:|
| 21-30 | 265 | 2,6% |
| 31-40 | 2 132 | 21,1% |
| **41-50** | **4 652** | **45,9%** |
| 51-60 | 2 673 | 26,4% |
| 61-70 | 404 | 4,0% |
| 71-80 | 1 | 0,01% |

> **Point clé** : La concentration sur la tranche 41-50 ans crée une dépendance risquée — toute hausse du churn dans ce segment aurait un impact massif.

---

## 7. Analyse Détaillée du Taux de Churn

Cette section décompose le taux de churn par segment démographique et financier afin d'identifier les populations les plus à risque.

### ▶ 7.1 Taux de churn par Genre

Les femmes présentent un taux de churn supérieur de près de **3 points** par rapport aux hommes, ce qui suggère une insatisfaction plus marquée ou des besoins spécifiques non couverts.

| Genre | Taux de Churn | Écart vs Moyenne |
|:---|:---:|:---:|
| 🔴 **Femmes** | **17,36%** | +1,29 pts |
| Hommes | 14,62% | -1,45 pts |

### ▶ 7.2 Taux de churn par Type de Carte

Le constat le plus frappant concerne la carte **Platinum** avec un taux de churn de **25%**, soit un quart des détenteurs. La carte Gold suit avec 18,1%. Ce paradoxe (clients premium qui partent plus) mérite une investigation approfondie.

| Type de Carte | Taux de Churn | Niveau de Risque |
|:---|:---:|:---:|
| 💎 Platinum | **🔴 25,00%** | ⚠️ Critique |
| 🟡 Gold | **🔴 18,10%** | ⚠️ Élevé |
| 🔵 Blue | 16,10% | Modéré |
| ⚪ Silver | 14,77% | Modéré |

### ▶ 7.3 Taux de churn par Tranche de Revenu

De manière contre-intuitive, la tranche **$120K+** présente le taux de churn le plus élevé (17,33%), suivie de près par les revenus les plus faibles (Less than $40K : 17,19%). La tranche $60K-$80K affiche le taux le plus bas (13,48%).

| Tranche de Revenu | Taux de Churn | Niveau de Risque |
|:---|:---:|:---:|
| 🔴 $120K + | **17,33%** | ⚠️ Élevé |
| 🔴 Less than $40K | **17,19%** | ⚠️ Élevé |
| Unknown | 16,82% | Modéré |
| $80K - $120K | 15,77% | Modéré |
| $40K - $60K | 15,14% | Modéré |
| 🟢 $60K - $80K | **13,48%** | Faible |

> **Paradoxe identifié** : Les deux extrêmes de revenu (les plus riches et les plus modestes) présentent les taux de churn les plus élevés. Les clients à revenu intermédiaire sont les plus fidèles.

---

## 8. Constats et Recommandations

### ⚠️ 8.1 Principaux Constats

1. Le taux de churn global est de **16,07%**, soit environ 1 client sur 6 qui quitte la banque.
2. Les femmes présentent un taux de churn supérieur de **2,74 points** par rapport aux hommes (17,36% vs 14,62%).
3. Les détenteurs de cartes Platinum affichent un taux de churn alarmant de **25%**, suivi par Gold à **18,10%**.
4. La tranche de revenu $120K+ présente un taux de churn parmi les plus hauts (**17,33%**), révélant un problème de satisfaction chez les clients à forte valeur.
5. La tranche d'âge 41-50 ans (**46% de la base**) représente un enjeu stratégique majeur de rétention.
6. La carte Blue concentre **93% des clients** avec un crédit moyen de seulement 7 364 $, suggérant une base client peu engagée.
7. Les Graduate et High School cumulent plus de **50% de la base client** et le plus grand volume de churners.

### → 8.2 Recommandations Stratégiques

**1. Programme de fidélisation premium**
Mettre en place un programme d'accompagnement renforcé pour les détenteurs de cartes Gold et Platinum : conseiller dédié, avantages exclusifs, et enquêtes de satisfaction régulières.

**2. Offre ciblée pour la clientèle féminine**
Développer des produits et services adaptés aux besoins de la clientèle féminine, qui représente 53% de la base et affiche un taux de churn plus élevé.

**3. Rétention des clients à haut revenu**
Renforcer l'engagement des clients $120K+ par des services de gestion patrimoniale, des offres d'investissement et un accompagnement personnalisé.

**4. Modèle prédictif de churn**
Développer un modèle de machine learning basé sur les données transactionnelles et démographiques pour identifier les clients à risque et déclencher des actions préventives.

**5. Stratégie d'up-selling**
Proposer des upgrades de carte aux clients Blue les plus actifs, en mettant en avant les avantages des cartes Silver et Gold pour augmenter l'engagement et la rétention.

**6. Focus sur la tranche 41-50 ans**
Cette tranche représentant 46% de la base, développer des produits adaptés à cette période de vie (crédit immobilier, épargne retraite, assurance) pour maximiser la rétention.

---

## 9. Conclusion

> L'analyse du dashboard Bank Churners révèle des dynamiques d'attrition significatives au sein de la base client. Avec un taux de churn de **16,07%**, la banque fait face à un défi majeur de rétention.
>
> Les segments à risque identifiés — **cartes premium** (Platinum : 25%, Gold : 18,1%), **clientèle féminine** (17,36%), et **hauts revenus** (17,33%) — constituent des priorités stratégiques immédiates.
>
> La mise en œuvre d'un modèle prédictif et de programmes de fidélisation ciblés permettra d'optimiser la rétention et de réduire significativement les pertes de clientèle.

---

<div align="right">

**OMARI Wail**

*ENCG Settat — Université Hassan 1er*

</div>
