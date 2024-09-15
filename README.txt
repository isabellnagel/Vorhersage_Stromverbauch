######################################################
Aufbau
######################################################
Dieses Repositiory enthält Daten und Code:

## Daten ##

- Klimadaten .txt (Quelle: DWD): für Berlin (Berlin), Köln (NRW), Stuttgart (BW) und jeweils Temperatur und Niederschlagsdate
- Fußballdaten .csv (Quelle: UEFA): EM und WM der Jahre 2012, 2014, 2016, 2018, 2021, 20224
- Stromverbrauchsdaten .txt (Quelle: Bundesnetzagentur, SMARD.de): von 2015 bis 2024 in 15min Schritten

## Code ##

- main.ipynb: Hauptcode, welcher auszuführen ist, um Ergebnisse der Modelle
  Lineare Regression, Random Forest und LSTM zu erhalten. Bezieht Funktionen aus restlichen Jupyter Notebooks

- Preprocessing.ipynb: Funktionen zu Preprocessing
- feature_engineering.ipynb: Funktionen zu Feature Engineering
- Modelling.ipynb: Funktionen zu Modellierung
- Visualization.ipynb: Funktion zur Visualisierung