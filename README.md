# _nakl

Projet de **prévision de la fréquentation des restaurants** (dataset Recruiting The Air).

## Objectif
Prédire le nombre de visiteurs (`visitors`) par restaurant et date
Utilisation de XGBoost + Optuna + MLflow

## Dataset
- `air_visit_data.csv` : Fréquentation historique
- `air_reserve.csv` : Réservations Air
- `hpg_reserve.csv` : Réservations HPG
- 252000 observations, 2016-2017

## Features créées
- Réservations agrégées (Air + HPG)
- Features temporelles (weekday, weekend, holiday)
- Lags et moyennes mobiles (1,7 jours)



## Installation
```bash
git clone https://github.com/Lmp237/_nakl.git
cd _nakl
pip install -r requirements.txt
