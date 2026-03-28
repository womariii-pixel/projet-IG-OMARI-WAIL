
# 📊 COMPTE RENDU — Dashboard Bank Churners

## Analyse de la Rétention Client Bancaire

**Réalisé par : OMARI WAIL**
ENCG Settat — Université Hassan 1er

*Source : BankChurners.csv · 10 127 clients analysés*

---

## 1. Introduction

Le présent compte rendu synthétise les résultats de l'analyse du dashboard **Bank Churners**, réalisé dans le cadre du projet mené à l'ENCG Settat (Université Hassan 1er). L'objectif est d'identifier les facteurs d'attrition (churn) parmi les clients bancaires et de formuler des recommandations pour améliorer la rétention.

L'étude porte sur un échantillon de **10 127 clients**, dont les données démographiques, financières et transactionnelles ont été exploitées pour construire un tableau de bord interactif.

---

## 2. Indicateurs Clés

| Indicateur | Valeur |
|---|---|
| Total Clients | 10 127 |
| Clients Actifs | 8 500 (83,9%) |
| Clients Attrités (Churners) | 1 627 (16,1%) |
| **Taux de Churn** | **16,07%** |
| Clients Femmes | 5 358 (52,9%) |
| Limite de Crédit Moyenne | 8 632 $ |
| Transactions Moyennes | 4 404 $ |
| Taux d'Utilisation Moyen | 27,49% |

---

## 3. Répartition par Niveau d'Éducation

Le niveau d'éducation impacte le comportement de churn. Les diplômés (Graduate) représentent la plus grande proportion de la base client, mais aussi le plus grand nombre de churners en valeur absolue.

| Éducation | Nb Clients | Churners |
|---|---|---|
| Graduate | 3 128 | 487 |
| High School | 2 013 | 306 |
| Unknown | 1 519 | 256 |
| Uneducated | 1 487 | 237 |
| College | 1 013 | 154 |
| Post-Graduate | 516 | 92 |
| Doctorate | 451 | 95 |

---

## 4. Répartition par Tranche de Revenu

La tranche de revenu inférieure à 40 000 $ concentre le plus grand nombre de clients (3 561), reflétant une base client à dominante de revenus modestes.

| Tranche de Revenu | Nb Clients |
|---|---|
| Less than $40K | 3 561 |
| $40K - $60K | 1 790 |
| $80K - $120K | 1 535 |
| $60K - $80K | 1 402 |
| Unknown | 1 112 |
| $120K + | 727 |

---

## 5. Analyse par Type de Carte

La carte Blue domine largement avec 9 436 clients. Les cartes premium (Gold, Platinum) sont marginales mais présentent des taux de churn plus élevés.

| Type Carte | Nb Clients | Crédit Moyen ($) |
|---|---|---|
| Blue | 9 436 | 7 364 |
| Silver | 555 | 25 278 |
| Gold | 116 | 28 416 |
| Platinum | 20 | 30 283 |

---

## 6. Répartition par Tranche d'Âge

La tranche 41-50 ans est la plus représentée avec 4 652 clients, suivie par les 51-60 ans (2 673). Les jeunes (21-30) et les seniors (71-80) restent très minoritaires.

| Tranche d'Âge | Nb Clients |
|---|---|
| 21-30 | 265 |
| 31-40 | 2 132 |
| 41-50 | 4 652 |
| 51-60 | 2 673 |
| 61-70 | 404 |
| 71-80 | 1 |

---

## 7. Analyse Détaillée du Churn

### Taux de churn par Genre

| Genre | Taux de Churn |
|---|---|
| Femmes | **17,36%** |
| Hommes | **14,62%** |

### Taux de churn par Type de Carte

| Carte | Taux de Churn |
|---|---|
| Platinum | **25,00%** |
| Gold | **18,10%** |
| Blue | **16,10%** |
| Silver | **14,77%** |

### Taux de churn par Revenu

| Revenu | Taux de Churn |
|---|---|
| $120K + | **17,33%** |
| Less than $40K | **17,19%** |
| Unknown | **16,82%** |
| $80K - $120K | **15,77%** |
| $40K - $60K | **15,14%** |
| $60K - $80K | **13,48%** |

---

## 8. Constats et Recommandations

### Principaux constats

- Le taux de churn global est de 16,07%, soit environ 1 client sur 6 qui quitte la banque.
- Les femmes présentent un taux de churn plus élevé (17,36%) que les hommes (14,62%).
- Les détenteurs de cartes Platinum affichent le taux de churn le plus élevé (25%), malgré un crédit moyen élevé.
- La tranche de revenu $120K+ présente un taux de churn parmi les plus hauts (17,33%), ce qui est contre-intuitif.
- La tranche d'âge 41-50 ans domine la base client (46%) et représente un enjeu majeur de rétention.

### Recommandations

- Mettre en place des programmes de fidélisation ciblés pour les détenteurs de cartes premium (Gold et Platinum) afin de réduire leur taux d'attrition disproportionné.
- Développer des offres spécifiques pour la clientèle féminine, qui présente un taux de départ plus élevé.
- Renforcer l'engagement des clients à haut revenu ($120K+) par des services personnalisés et un accompagnement dédié.
- Analyser plus finement les comportements transactionnels des clients à risque pour anticiper le churn via des modèles prédictifs.
- Améliorer l'expérience client dans la tranche 41-50 ans, qui constitue le cœur de la base client.

---

## 9. Conclusion

L'analyse du dashboard Bank Churners révèle des dynamiques d'attrition significatives au sein de la base client. Avec un taux de churn de 16,07%, la banque fait face à un défi de rétention qui nécessite des actions ciblées. Les segments à risque identifiés (cartes premium, clientèle féminine, hauts revenus) constituent des priorités stratégiques pour optimiser la fidélisation et réduire les pertes de clientèle.

---

*OMARI Wail — ENCG Settat · Université Hassan 1er*

![Photo OMARI Wail](photo_omari_wail.jpg)
