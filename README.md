# prediction-electricity-time-series
Forecast the demand on electricity for next 12 months 

**Skill sets**
- time series
- correct a dataset of its innate variable,s 
- deseasonalisation / correction time series of seasonality 
- prediction with stationary data and non-stationary data through diverse methods: Exponential Smoothing, SARIMA 

------


**Mise en situation**

Vous êtes employé chez Enercoop, société coopérative qui s'est développée grâce à la libéralisation du marché de l’électricité en France. Elle est spécialisée dans les énergies renouvelables.

La plupart de ces énergies renouvelables est cependant intermittente, il est donc difficile de prévoir les capacités de production d'électricité. De plus, la demande en électricité des utilisateurs varie au cours du temps, et dépend de paramètres comme la météo (température, luminosité, etc.) Tout le challenge est de mettre en adéquation l'offre et la demande !

**Les données**

Vous téléchargerez les données mensuelles de consommation totale d'électricité en énergie à partir de cette page.

Les données météo que vous utiliserez pour corriger les données de l'effet température sont présentes ici : https://cegibat.grdf.fr/simulateur/calcul-dju

**Votre mission**

Vous vous concentrerez uniquement sur la prédiction de la demande en électricité.

1. Corrigez les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.
2. Effectuez une désaisonnalisation de la consommation que vous aurez obtenue après correction, grâce aux moyennes mobiles. 
3. Effectuez une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode SARIMA sur la série temporelle.

https://openclassrooms.com/fr/paths/65/projects/150/assignment
