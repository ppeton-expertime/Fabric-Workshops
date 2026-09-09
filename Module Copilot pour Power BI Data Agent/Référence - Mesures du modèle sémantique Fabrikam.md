# Référence - Mesures du modèle sémantique Fabrikam

Ce document liste les principales mesures DAX du modèle sémantique **Fabrikam Company Sales Report**, regroupées par table. Il sert de référence pour les modules **1.x (Copilot pour Power BI)** et **2.x (Data Agent)**, notamment pour rédiger des descriptions de mesures (voir [2.3. Ajouter des descriptions de mesures avec Copilot, dans le modèle sémantique.md](2.3.%20Ajouter%20des%20descriptions%20de%20mesures%20avec%20Copilot%2C%20dans%20le%20mod%C3%A8le%20s%C3%A9mantique.md)) ou des instructions de Data Agent.

## 1. Table Sales (cœur du modèle) – mesures de ventes

| Mesure | Description |
|---|---|
| `Sales` | Montant des ventes (format monétaire) |
| `Sales Orders` | Nombre de commandes de vente |
| `Total Units Sold` | Nombre d'unités vendues |
| `Distinct Products Sold` | Nombre de produits distincts vendus |
| `Gross Margin` | Marge brute |
| `Gross Margin %` | Marge brute en pourcentage |
| `Sales YoY%` | Variation annuelle des ventes (Year over Year) |

**Mesures liées au "best seller" et au top produit :**

| Mesure | Description |
|---|---|
| `Highest Selling Product Sales` | Ventes du produit le plus vendu |
| `Total Sales Best Selling` | Total des ventes du meilleur produit |
| `Best Selling Units Sold` | Unités vendues du meilleur produit |
| `Top units sold unit count` | Nombre d'unités du produit le plus vendu (en unités) |
| `Total Sales of Top Selling Unit` | Total des ventes de l'unité la plus vendue |
| `Profit of Best Selling Item` | Profit généré par le meilleur produit |

**Mesures dérivées / techniques :**

| Mesure | Description |
|---|---|
| `Avg Order` | Montant moyen par commande |
| `MoM Sales Change` | Variation des ventes mois sur mois (Month over Month) |
| `Trend Icon` | Icône de tendance (visuel) |
| `Sales2` | Mesure technique dérivée des ventes |
| `SalesNet` | Ventes nettes |
| `SalesExtendedPrice` | Prix étendu des ventes |

## 2. Table Purchase Orders – suivi des achats / stocks

| Mesure | Description |
|---|---|
| `Spend` | Dépenses d'achat |
| `Avg PO` | Montant moyen par commande d'achat |
| `PO Units` | Unités en commande d'achat |
| `PO Units in Stock` | Unités en commande d'achat disponibles en stock |
| `PO Units Planned` | Unités planifiées en commande d'achat |
| `Purchase Orders` | Nombre de commandes d'achat |
| `In Stock` *(cachée)* | Stock disponible, dans le contexte des commandes d'achat |

## 3. Table Reseller – vente via revendeurs

| Mesure | Description |
|---|---|
| `Reseller Sales` | Ventes réalisées via les revendeurs |
| `Sales by reseller` | Ventes ventilées par revendeur |

## 4. Table Product – vues "top produit"

| Mesure | Description |
|---|---|
| `Highest sold product name` | Nom du produit le plus vendu |
| `Highest Sold StockName` | Nom de stock du produit le plus vendu |
| `Top N1 Sales` | Ventes du top 1 produit |
| `BestSellingUnitPrice` | Prix unitaire du produit le plus vendu |
| `Unit price of most sold unit` | Prix unitaire de l'unité la plus vendue |
| `Supplier Sales` | Ventes par fournisseur |

## Mesures clés pour l'analyse globale

En pratique, les mesures vraiment "clés" pour l'analyse globale du modèle sont :

- **Sales** : `Sales`, `Gross Margin`, `Gross Margin %`, `Sales Orders`, `Total Units Sold`, `Distinct Products Sold`, `Sales YoY%`
- **Purchase Orders** : `Spend`, `Avg PO`
- **Reseller** : `Reseller Sales`

> 💡 Ces mesures clés sont de bonnes candidates prioritaires pour l'exercice [2.3. Ajouter des descriptions de mesures avec Copilot, dans le modèle sémantique.md](2.3.%20Ajouter%20des%20descriptions%20de%20mesures%20avec%20Copilot%2C%20dans%20le%20mod%C3%A8le%20s%C3%A9mantique.md) et pour rédiger les instructions du Data Agent (module 2.x).
