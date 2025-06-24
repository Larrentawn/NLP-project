# Airlnes reviews
### NLP Project
<img src="https://github.com/user-attachments/assets/e46a2fe1-0382-484d-a6f3-5e7ec23daf34" alt="Arlines" width="200" height="200">
            <img src="https://github.com/user-attachments/assets/d1fd6fac-3c75-44de-b688-9ddf4eec71b6" alt="Reviews" width="100" height="100">
                          <img src="https://github.com/user-attachments/assets/1a943c00-f34f-46da-b378-385dd0edef0b" alt="Reviews2" width="180" height="100"></br>


## Objetivo

Los aerolíneas juegan un rol muy importante en los movimientos de viaje y relaciones a nivel global, tanto por motivos laborales o de ocio.

Las reseñas de éstas, se convirtieron en un estándar para orientar a los usuarios en la comparación al momento de elegir. Pero además, permiten a las aerolíneas, obtener un insight sobre la experiencia de los pasajeros, sus preferencias y el nivel de satisfacción en cada caso.

Con el acceso a herramientas e información que poseemos hoy en día, podemos categorizar miles de reseñas en etiquetas de sentimiento positivo, negativo, o neutral.

El objetivo es trabajar este conjunto de datos con reseñas en texto de diversas aerolíneas, junto a diversas calificaciones, generales de 1 a 9 (1 siendo muy negativo y 9 siendo muy positivo) y otras mas especificas como Precio-calidad, comodidad de asientos, etc. A partir de esta clasificación, al obtener una reseña nueva, se puede predecir si ésta es positiva o negativa.

## Índice del proyecto
1. Presentación
2. Objetivo
3. EDA
4. Análisis de texto y pre-procesamiento:
   - Longitud y frecuencia de palabras y oraciones
   - Análisis sintáctico y semántico
   - PoS Tagging
   - N-grams
   - Lemmatización
   - Codificación a vectores (TF-Idf)
5. Feature selection y balanceo de clases
6. Modelos, validación, fine tuning y reports.
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost
   - DistillBERT
7. Conclusiones Finales

---

## Contenido del dataset
### Columnas

**Airline Name** = Nombre de la Aerolínea </br>
**Overall Rating** = Calificación total</br>
**Review Title** = Titulo de la reseña</br>
**Review Date** = Fecha de la reseña</br>
**Verified** = Si la reseña está verificada o no</br>
**Review** = Texto de la reseña</br>
**Aircraft** = Tipo de avión</br>
**Type of Traveller** = Tipo de pasajero</br>
**Seat Type** = Tipo de asiento</br>
**Route** = Ruta de viaje</br>
**Date Flown** = Fecha de vuelo</br>
**Seat Comfort** = Calificación de comodidad del asiento</br>
**Cabin Staff Service** = Calificación del staff de cabina</br>
**Food & Beverages** = Calificación de la comida y bebida</br>
**Ground Service** = Calificación del servicio en tierra</br>
**Inflight Entertainment** = Calificación del entretenimiento en el vuelo</br>
**Wifi & Connectivity** = Calificación de WiFi y conectividad</br>
**Value for Money** = Calificación de relación precio/calidad</br>
**Recommended** = Recomendado si/no</br>

---

## Citaciones

Recopilación por Juhi Bhojani y subido en Kaggle y Github

  . https://www.kaggle.com/datasets/juhibhojani/airline-reviews

  . https://github.com/Juhibhojani/Airline-Reviews-

Las reviews de aerolíneas de este dataset fueron obtenidas por el autor desde:

  . https://www.airlinequality.com/review-pages/a-z-airline-reviews/
