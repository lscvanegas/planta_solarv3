<<<<<<< HEAD
# Planta_Solar
Este proyecto permite generar modelos basados en Redes Neuronales Artificiales Recurrentes (RNN) para problemas de regresión y series temporales en general, y de plantas solares en particular. El objetivo específico del proyecto es construir modelos capaces de predecir a corto y largo plazo la producción de energía eléctrica de una planta fotovoltaica mediante modelos univariables y multivariables (integrando variables climáticas en estos últimos).

# Funcionalidad de cada archivo y directorio.

* "get_and_prep_data.py" => de acuerdo con los datos proporcionado para esta investigación, este script toma los archivos(.xlsx) ubicados en el directorio "/data_files" y realiza la preparación y limpieza de los datos obteniendo un único archivo con el cual se entrenan y se prueban los modelos. Este script hace uso del archivo "tools.py" que contiene las funciones de preprocesamiento y el archivo "settings.py" donde se definen algunos valores de configuración, especialmente, rutas y archivos. El archivo "expl.py" construye gráficos relacionados con el análisis exploratorio de los datos generados.

* "univariate_model.py" and "multivariate_model.py" => Estos archivos son los encargados de generar modelos univariables y multivariables respectivamente a partir de los archivos de configuración "u_config.json" y "m_config.json", los cuales permiten definir los parámetros para construir los modelos de los cuales sus estructuras se encuentran definidas en el directorio "/models_mk". El archivo "ml_tools.py" contiene las herramientas utilizadas para generar los modelos. Los resultados del último modelo generado se encuentran en los directorios "/models" y "/graphics". En el directorio "/experiments" se guarda en un directorio, único y definido por la fecha y hora, todo lo referente al modelo: gráficos, datos del desempeño y archivos referentes al modelo generado. El archivo "graph.py" contiene las funciones para generar os gráficos.

* "multi_model_analizer" => permite realizar un análisis comparativo entre los modelos ubicados en el directorio "/to_analize". (estos modelos deben estar en el formato con el que almacenan los experimentos).

* "solar_predict_app.py" => este script corresponde a una aplicación web desarrollada a través de steamlit.io para mostrar el potencial de los modelos univariables, realizar predicciones y comparaciones al cambiar algunos parámetros. Por defecto la aplicación utiliza los datos ubicados en "/app_src". La aplicación hace uso de modelos entrenados previamente ubicados en app_models, los cuales son generados mediante el script "univariate_2app.py". Esta aplicaciín esta alojada en un servidor de streamlit y se puede acceder mediante el link: https://share.streamlit.io/cesarhdez/planta_solar/solar_predict_app.py

#---------------------------------------------------------------------------------

# Solar plant
This project allows generate models based on Recurrent Artificial Neural Networks (RNN) for regression problems and time series in general, and solar plants in particular. The specific objective of the project is to build models capable to predict in the short and long term the electrical energy production of a photovoltaic plant using univariate and multivariable models (integrating climatic variables in the latter).

# Functionality of each file and directory.

* "get_and_prep_data.py" => according to the data provided for this investigation, this script takes the files (.xlsx) located in the directory "/data_files" and performs the preparation and cleaning of the data obtaining a single file with the which models are trained and tested. This script makes use of "tools.py" file that contains the preprocessing functions and "settings.py" file where some configuration values ​​are defined, especially paths and files. The file "expl.py" builds graphs related to the exploratory analysis of the proseced data.

* "univariate_model.py" and "multivariate_model.py" => These files are in charge of generating univariate and multivariate models respectively from the configuration files "u_config.json" and "m_config.json", which allow defining parameters to build the models whose structures are defined in the "/models_mk" directory. The file "ml_tools.py" contains tools used to generate these models. The results of the last generated model are found in "/models" and "/graphics" directories. In  "/experiments" directory, everything related to the model is stored in a single directory defined by date and time: graphics, performance data and files related to the generated model. The file "graph.py" contains the functions to generate the graphs.

* "multi_model_analizer" => allows a comparative analysis between the models located in "/to_analize" directory. (These models must be in the format in which they store the experiments).

* "solar_predict_app.py" => this script corresponds to a web application developed through steamlit.io to show the potential of univariate models, make predictions and comparisons by changing some parameters. By default the application uses the data located in "/app_src". The application makes use of previously trained models located in app_models, which are generated by the script "univariate_2app.py". This application is hosted on a streamlit server and can be accessed through the link: https://share.streamlit.io/cesarhdez/planta_solar/solar_predict_app.py
=======
# Planta_Solarv2
IA para planta solar
>>>>>>> a3df00351ef2cb7a2ae1aec2256a2ae6da4ed556
