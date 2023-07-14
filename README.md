# ML_task2
Inicialemnte se extraen características del conjunto de datos, como el nº de palabras por tweet, nº de signos de puntuación, etc.
Features_task2
Preprocesado del conjunto de datos. Aplicación de algorimos de Machine Learning.
Preprocesado : 
Eliminar usuarios identificados por @
Eliminar URL's y links
Eliminar referencias link o video
Eliminar entidades HTML
Eliminar caracteres especiales y convertir a minúsculas
Elimnar los caracteres que no coincidan con el patrón
Tokenizar el texto utilizando SpaCy/NLTK
Eliminar stopwords
Unir los tokens procesados en un texto procesado

Se convierten a numéricas las categorias de la clase objetivo.
Se vectoriza, TD_IF para extraer características.
Se aplican los algorimtos SVC, XGBoost; Random Forest y NB_Mutinomial.
Los resultados no son buenos y se valoran otras opciones para intentar mejorar los modelos.

Para mejorar los resultados se opta :
Aplicar  configurar los hiperparámetros.
Añadir muestras nuevas mediant oversampling(SMOTE).
