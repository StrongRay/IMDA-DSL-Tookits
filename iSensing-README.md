# IMDA-DSL-Tookits
IMDA Digital Services Lab developed a “Intelligent Sensing Toolbox” [https://www.imda.gov.sg/industry-development/infrastructure/technology/digital-services-lab/intelligent-sensing-toolbox] to identify outliers in a sample appliances-energy-prediction dataset. But the key objective is for the application of anomaly detection in different areas where human monitoring can be made redundant and more effective.  

Technically the developed toolkit is based on

Python 3
sklearn.preprocessing
isensing toolkit with adapted codes from robpca [https://feb.kuleuven.be/public/u0017833/Programs/pca/robpca.txt]

Using standard off the shelf plotly [https://plot.ly] scatterplot API, Isensing Anomalies plots the data in a 2-dimensional space with the outilers marked by the individual algorithm.  The beautiful graphical chart is shown as follows

![image](https://github.com/StrongRay/IMDA-DSL-Tookits/blob/master/iSensing-PlotPy.png)

with  Anomalies data errors detected in a pandas dataframe, rules can be configured in python to trigger alerts to the human operators or perform pre-defined actions


