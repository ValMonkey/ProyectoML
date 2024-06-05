# ProyectoML
Proyecto correspondiente al curso de Machine Learning de la Lic. en Inteligencia Artificial.




------------------------------------------------------------------------------------- Descripción del problema: Predicción.

El problema de predicción fue abordado mediante un dataset de 10 electrocardiogramas extraidos de 10 personas diferentes, de las cuales 5 eran personas jovenes y el resto eran adultos mayores. El dataset es parte de la base de datos Fantasia de PhysioNet. Los electrocardiogramas fueron tomados mientras las personas viaulizaban una pelicula (Fantasía, Disney). Cada columna contiene intervalos RR cardiacos en segundos, con una duración total de aproximadamente dos horas.
Una de las series de tiempo cortaba antes que el resto, por lo que los datos fueron recortados hasta ese registro.
Lo que deseaba realizar era predecir los siguientes puntos de la serie de tiempo mediante modelos de predicción.

------------------------------------------------------------------------------------- Modelos utilizados: Predicción

Para abordar el problema utilicé tecnicas como: 
- Regresión lineal
- Regresión logistica

------------------------------------------------------------------------------------- Resultados de los modelos: Predicción.

Con esta implementación pudimos percatarnos de que en este caso el modelo de predicción lineal fue mejor que el de regresión lógistica, ya que el R2 del mismo, fue más favorable que el de regresión lineal.





------------------------------------------------------------------------------------- Descripción del problema: Clasificación.

El problema de clasificación fue trabajado con un dataset extraido de kaggle que abordaba las frecuencias del uso de drogas respecto a variables como presion arterial, sexo biologico, edad, etc. 
Se realizo un balanceo de clases durante el preprocesamiento de los datos.
Se buscaba clasificar cada una de las clases (drogas). 

------------------------------------------------------------------------------------- Modelos utilizados: Clasificación.

Para abordar este problema se utilizaron dos diferentes modelos de clasificación: 
- Arbol de decisión.
- Regresión logistica

------------------------------------------------------------------------------------- Reultados de los modelos: Clasificación.

Se obtuvo que el accuracy con el modelo de regresión logistica fue de 98.33%, mientras que el accuracy para el arbol de decisión fue de 96.67%, concluyendo así que en esta ocasión la regresión logistica, obtuvo mejores resultados. 


