Esta es la estructura:

Pset2_cucalon/ 
├── data/
│   ├── raw/  → Datos originales
│   ├── processed/  → Datos limpios y transformados
├── models/  → Modelos entrenados (.pkl)
├── notebooks/  → Jupyter Notebooks 
├── scripts/  → No se utilizo
├── requirements.txt  → Dependencias del proyecto
└── README.md  → Explicación del proyecto

En data:
Raw -> Originales 
Processed ->
   - Airbnb_Cleaned  ->  Datos limpiados
   - Airbnb_Featured  ->  Datos con características seleccionadas
   - Airbnb_Featured_Scaled  ->  Datos con características escalados

Estos datos se utilizaron para revisar las diferentes características, que luego se eligieron para Airbnb_Featured
   - city_feature  ->  Características de la ciudad
   - property_type_feature  ->  Tipos de propiedades
   - cleaning_fee_feature  ->  Tarifa de limpieza
   - bed_type_feature  ->  Tipos de camas
   - amenities_feature  ->  Características y comodidades
   - room_type_feature  ->  Tipos de habitación
   - ubi_feature  ->  Ubicación

En notebooks:
1_exploratory_data_analysis.ipynb -> EDA.
2_data_wrangling.ipynb -> Limpieza y transformación de los datos.
3_feature_engineering.ipynb -> Creación y selección de características.
4_model_training.ipynb -> Entrenamiento de modelos de Machine Learning.
5_evaluation_and_results.ipynb -> Evaluación de modelos y análisis de resultados.

En models:
Modelos Entrenados 
model_evaluation_results -> Evaluation data guardado
predicciones_modelos -> Un ejemplo guardado
