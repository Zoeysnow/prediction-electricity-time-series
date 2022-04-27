# Forecast the demand on electricity for next 12 months

**Skill sets**
- time series
- correct a dataset of its innate variable,s 
- deseasonalisation / correction time series of seasonality 
- prediction with stationary data and non-stationary data through diverse methods: Exponential Smoothing, SARIMA 

------


**Mise en situation / Context & Challenge**

Vous êtes employé chez Enercoop, société coopérative qui s'est développée grâce à la libéralisation du marché de l’électricité en France. Elle est spécialisée dans les énergies renouvelables.

La plupart de ces énergies renouvelables est cependant intermittente, il est donc difficile de prévoir les capacités de production d'électricité. De plus, la demande en électricité des utilisateurs varie au cours du temps, et dépend de paramètres comme la météo (température, luminosité, etc.) Tout le challenge est de mettre en adéquation l'offre et la demande !

*ENERCOOP is a French electricity company specialised in renewable electricty production. While the company had difficulty in forecasting the electricity consumption, especially when it differs with time and depends on many factors such as weather (temperature, sunshine, huminity etc). As a Data Analyst, you're going to fill the gap between demand and production.*

**Les jeux de données / Data sets**

- les données mensuelles de consommation totale d'électricité en énergie 
- *(Dataset on monthly electricity consumption)*: 
https://www.rte-france.com/eco2mix/telecharger-les-indicateurs

- les données météo pour corriger les données de l'effet température 
- *(original data on weather, where the temperature effect is measured by DJU)*: 
- https://cegibat.grdf.fr/simulateur/calcul-dju

**Mission / Business goal**

Vous vous concentrerez uniquement sur la prédiction de la demande en électricité.
1. Corrigez les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.
2. Effectuez une désaisonnalisation de la consommation que vous aurez obtenue après correction, grâce aux moyennes mobiles. 
3. Effectuez une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode SARIMA sur la série temporelle.

------
# You're going to forecast the future consumption on electricity. Tasks hereinafter: * 
* 1. Correct the monthly electricity consumtion data of the effect from temperature (precisely due to electric heating). 
* 2. Once you got the corrected dataset from Q1, we need to deseasonalize (remove the seasonal effect) it to obtain the trend.  
* 3. Forecast the electricity consumption for the futuer 12 months (without taking into account the temperature effect) by using 2 methods for time series: Exponential Smoothing, SARIMA. 

https://openclassrooms.com/fr/paths/65/projects/150/assignment
