# Prédiction de la réduction des émissions CO₂ par optimisation logistique

**Projet n°40 – Intelligence Artificielle – ENCG Settat**  
*Option Purchasing & Supply Chain Management – Mars 2026*

## 🎯 Objectif
Prédire le facteur d’émission carbone (kg CO₂e / USD) des secteurs économiques et simuler l’impact de scénarios d’optimisation logistique (report modal, mutualisation des tournées) sur les émissions totales.

## 📊 Données
- **Source** : [Supply Chain GHG Emission Factors v1.2 (Kaggle)](https://www.kaggle.com/datasets/parulpandey/global-co2-emissions-dataset?select=SupplyChainGHGEmissionFactors_v1.2_NAICS_CO2e_USD2021.csv)
- **Description** : Facteurs d’émission par secteur (NAICS) basés sur le modèle USEEIO.
- **Cible** : `Supply Chain Emission Factors with Margins` (kg CO₂e / USD)

## 🔧 Méthodologie
- Prétraitement : encodage one-hot, normalisation.
- Modèles testés :
  - Régression linéaire
  - Forêt aléatoire (Random Forest)
  - XGBoost
- Simulation : réduction de 15 % du facteur d’émission des secteurs de transport (code NAICS 48xxx) pour estimer le gain potentiel.

## 📈 Résultats
| Modèle            | MAE (kg CO₂e/USD) | RMSE (kg CO₂e/USD) | R²   |
|-------------------|-------------------|-------------------|------|
| Régression linéaire | 0.xxx           | 0.xxx            | 0.xxx |
| Forêt aléatoire    | 0.xxx           | 0.xxx            | 0.xxx |
| XGBoost            | 0.xxx           | 0.xxx            | 0.xxx |

*(Remplace les « xxx » par les valeurs obtenues dans ton notebook)*

## 🚀 Exécution
1. Ouvrir le notebook `Projet_IA_40_Logistique_Verte.ipynb` dans [Google Colab](https://colab.research.google.com/).
2. Téléverser le fichier `data/SupplyChainGHGEmissionFactors_v1.2_NAICS_CO2e_USD2021.csv` (ou utiliser le dataset sur Kaggle).
3. Exécuter toutes les cellules.

## 📽️ Vidéo explicative
[Regarder la présentation du projet](https://youtu.be/ID_DE_TA_VIDEO)

## 📁 Structure du dépôt
