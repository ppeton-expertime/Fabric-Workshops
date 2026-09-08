# Module Copilot pour Power BI & Data Agent

Formation d'une demi-journée dédiée à **Copilot pour Power BI** et au **Data Agent**, en dehors des fonctionnalités Fabric (notebooks, dataflow, etc.).

## Objectifs

- Découvrir les cas d'usage de Copilot dans Power BI (analyse, création de rapports, génération de DAX).
- Prendre en main la création et la configuration d'un Data Agent sur un modèle sémantique.
- Savoir optimiser les instructions d'un Data Agent pour obtenir des réponses fiables sur le contexte métier.

## Programme

| Horaire | Durée | Séquence |
|---|---|---|
| 9h30 - 9h45 | 15' | Introduction : objectifs, tour de table |
| 9h45 - 10h45 | 40' support + 20' lab | Copilot pour Power BI |
| 10h45 - 11h00 | 15' | Pause |
| 11h00 - 12h30 | 45' support + 45' lab | Data Agent |
| 12h30 | - | Fin de la session |

---

## 9h30 - 9h45 : Introduction

- Présentation des objectifs de la demi-journée.
- Tour de table des participants.

---

## Copilot pour Power BI (40' support + 20' lab)

> Hors fonctionnalités Fabric (notebooks, dataflow…)

### Support (40')

- Présentation des capacités de Copilot dans Power BI.
- Slide 21 : exemples de questions sur le jeu de données Fabrikam.
- Slide 79 : création d'une page de rapport avec Copilot.
- Slide 53 & 80 : création d'un visuel à la volée.

### Lab (20')

0. Uploader **Fabrikam.pbix** dans un Workspace **[FORMATION]**.
1. Poser des exemples de questions sur Fabrikam (slide 21).
2. Générer une **smart narrative**.
3. Créer un rapport de zéro avec Copilot.
4. Créer une page de rapport (slide 79).
5. Créer un visuel à la volée (slides 53 & 80).

**Si besoin** : génération de DAX avec Copilot.

> Exemple de prompt :
> *"Create a sales performance page with date and region slicers, cards for total sales and total profit, a monthly sales trend, sales by product category, and top 10 customers by revenue."*

---

## 10h45 - 11h00 : Pause

---

## Data Agent (45' support + 45' lab)

### Support (45')

- Présentation du Data Agent et de son fonctionnement sur un modèle sémantique.
- Rédaction d'instructions (ton, longueur des réponses, etc.).
- Ajout de descriptions de mesures via Copilot dans le modèle sémantique.
- Optimisation des instructions pour répondre correctement aux questions liées au contexte métier (ex. axe du temps : "l'année dernière...", "le mois prochain...").
- Exécution de la requête DAX générée dans Power BI Desktop (DAX query view).

### Lab (45')

1. Créer un Data Agent sur un modèle sémantique.
2. Écrire des instructions pour modifier le ton et la longueur des réponses.
3. Ajouter des descriptions de mesures avec Copilot, dans le modèle sémantique.
4. Optimiser les instructions pour bien répondre sur des questions de contexte métier (axe du temps, etc.).
5. Exécuter la requête DAX générée dans Power BI Desktop (DAX query view).

---

## 12h30 : Fin de la session
