# Titanic
El hundimiento del RMS Titanic en 1912 es uno de los desastres más emblemáticos de la historia moderna y ha sido objeto de estudio durante más de un siglo. En este trabajo, se utilizará el conjunto de datos del Titanic, disponible públicamente, para explorar y predecir la probabilidad de supervivencia de los pasajeros basándonos en características como la clase de boleto, el sexo, la edad y otros factores. El análisis se realizará utilizando un modelo de regresión logística, que es adecuado para problemas de clasificación binaria, como en este caso donde se busca predecir si un pasajero sobrevivió o no.

La regresión logística es un modelo estadístico que permite estimar las probabilidades de ocurrencia de un evento, en este caso, la supervivencia de los pasajeros, a partir de variables predictoras. A través de este análisis, se identificará qué variables tienen mayor impacto en la probabilidad de supervivencia y cómo se pueden utilizar para hacer predicciones en datos no vistos.

Además, se desarrollará un dashboard interactivo utilizando Power BI para presentar los resultados de manera clara y accesible. Este dashboard permitirá a los usuarios explorar de forma visual los diferentes factores que influyen en la supervivencia de los pasajeros del Titanic, brindando una comprensión más profunda del modelo y de los insights obtenidos.

Las herramientas utilizadas para llevar a cabo este análisis incluyen Python (en JupyterLab) para la creación del modelo de regresión logística y el procesamiento de datos, y Power BI para la visualización interactiva de los resultados.

Resultados

Los resultados del modelo de regresión logística indican que ciertos factores, como el sexo, la clase de pasajero y la edad, tienen un impacto significativo en la probabilidad de supervivencia. En particular, las pasajeras y aquellos pasajeros en clases superiores tenían más probabilidades de sobrevivir. La edad también jugó un papel importante, siendo los niños los que tenían una tasa de supervivencia más alta en comparación con los adultos. El modelo alcanzó una exactitud del 94%, una sensibilidad del 92% y un área bajo la curva ROC del 98%, lo que demuestra su efectividad para predecir la supervivencia. Estos resultados destacan el fuerte rendimiento del modelo, especialmente al distinguir entre sobrevivientes y no sobrevivientes. El dashboard interactivo permite a los usuarios explorar más a fondo estas tendencias y proporciona información sobre cómo diferentes características impactan la probabilidad de supervivencia.

El objetivo de este trabajo es proporcionar un enfoque práctico para aplicar la regresión logística en la predicción y ofrecer una herramienta visual que facilite la interpretación de los resultados.

..
The sinking of the RMS Titanic in 1912 is one of the most iconic disasters in modern history and has been studied for over a century. In this work, the Titanic dataset, publicly available, will be used to explore and predict the likelihood of passenger survival based on characteristics such as ticket class, sex, age, and other factors. The analysis will be performed using a logistic regression model, which is suitable for binary classification problems, such as predicting whether a passenger survived or not.

Logistic regression is a statistical model that allows estimating the probabilities of an event occurring, in this case, passenger survival, based on predictor variables. Through this analysis, the goal is to identify which variables have the most impact on the probability of survival and how they can be used to make predictions on unseen data.

Additionally, an interactive dashboard will be developed using Power BI to present the results clearly and accessibly. This dashboard will allow users to visually explore the different factors that influence Titanic passenger survival, providing a deeper understanding of the model and insights obtained.

The tools used to carry out this analysis include Python (in JupyterLab) for creating the logistic regression model and processing the data, and Power BI for interactive visualization of the results.

Results

The results of the logistic regression model indicate that certain factors, such as sex, passenger class, and age, have a significant impact on the probability of survival. In particular, female passengers and those in higher passenger classes were more likely to survive. Age also played a role, with children having a higher survival rate compared to adults. The model achieved an impressive accuracy of 94%, a sensitivity of 92%, and an area under the ROC curve of 98%, demonstrating its effectiveness in predicting survival. These results highlight the strong performance of the model, especially in distinguishing between survivors and non-survivors. The interactive dashboard allows users to explore these trends further and provides insights into how different features impact survival likelihood.

The goal of this work is to provide a practical approach to applying logistic regression for prediction and to offer a visual tool that facilitates the interpretation of the results.
