# Structure du dossier

## Smiles_Volatilité_Pricing_Options.pdf

Ce fichier contient l'étude réalisée (en format PDF), qui couvre l'évaluation des smiles de volatilité, des nappes de volatilité et des prix des options Call et Put sur le marché de l'Euro-Dollar. Cette étude porte sur des données allant de 2014 à 2019. 

## Smiles_Volatilité_Pricing_Options.zip

Ce ficher ZIP contient le fichier Excel, qui ont permis de réaliser l'ensemble des calculs. Une description est présentée plus en détail ci-dessous.

La feuille "Données" contient l'ensemble des données allant de 2014 à 2019. Ces données sont constituées des "runs de volatilité", des "strangles delta 10 et delta 25" et des "risk reversals delta 10 et delta 25". 

Les feuilles "int_lin_19" et "int_lag_10" calculent les volatilités Call et Put selon le niveau de delta et l'échéance pour l'année 2019, respectivement via une interpolation linéaire et une interpolation Lagrangienne. 

La feuille "courbes_vol_19" calcule les courbes de volatilité (bid/ask/mid) selon l'échéance pour l'année 2019.

La feuille "K_call_19_2" calcule le niveau de d1 (du modèle de Black-Scholes), le prix d'exercice et le prix de l'option Call (via le modèle de Garman-Kohlhagen) selon l'échéance et le niveau de delta à partir des volatilités calculées par interpolation Lagrangienne, pour l'année 2019.  

La feuille "K-put-19_2" suit le même raisonnement que la feuille "K_call_19_2" mais appliqué à l'option Put. 

Les feuilles "nappes_18", "nappes_17", "nappes_16", "nappes_15" et "nappes_14" donnent les nappes de volatilité (via interpolation Lagrangienne), respectivement pour les années 2018, 2017, 2016, 2015 et 2014.

La feuille "comparaison_int" procéde à une comparaison entre les volatilités obtenues en 2019 grâce à une interpolation linéaire et une interpolation Lagrangienne pour chaque échéance. 
