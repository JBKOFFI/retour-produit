# Projet de Visualisation des Retours Produits

## Contexte
Projet réalisé dans le cadre du Master 1 Data Science à l’Université Félix Houphouët Boigny de Cocody.  
L’objectif est d’analyser les retours produits d’une entreprise de vente de produits électroniques afin d’identifier les facteurs influençant ces retours.

## Membres du projet
- KOFFI Kouamé Jean-Baptiste  
- KOUASSI Kouadio Prosper  
- YAO Ayéménés Marcel  

## Problématique
Quels sont les facteurs qui influencent le retour des produits par les clients ?

## Jeu de données
`synthetic_sales_data.csv` – contient plus de 10 000 transactions avec les colonnes principales :  
- `TransactionID`, `CustomerID`  
- `Product`, `Category`  
- `PurchaseDate`, `Price`, `Quantity`  
- `PaymentMethod`, `CustomerRegion`  
- `Returned` (1 = produit retourné, 0 = conservé)  
- `DeliveryDays`, `SatisfactionRating` (1 à 5)  

## Analyse
### Taux global de retour
- 5,36 % des produits ont été retournés, un indicateur positif de satisfaction client.  

### Produits les plus retournés
| Produit        | Nombre de retours |
|----------------|-----------------|
| Écran (Monitor) | ~100            |
| Casques audio (Headphones) | 92 |
| Ordinateurs portables (Laptop) | 92 |
| Montres connectées (Smartwatch) | 88 |
| Tablettes      | 87              |
| Smartphones    | 79              |

## Interprétation
Les produits les plus retournés (écrans, casques audio, laptops) nécessitent un suivi qualité et des améliorations possibles dans le descriptif produit ou le service après-vente.  

## Technologie utilisée
Power BI pour l’analyse et la visualisation des données.
