# **🧠 Proyecto de Machine Learning – Predicción de Precios de Vehículos**

Este proyecto tiene como objetivo construir un sistema capaz de predecir el precio estimado de un vehículo a partir de sus características (año, marca, modelo, estado, kilometraje, etc.).
El trabajo incluye limpieza de datos, análisis exploratorio, preprocesamiento, entrenamiento de modelos y evaluación con validación cruzada.

## **📌 1. Descripción del proyecto**

Una empresa del sector automotriz busca una forma automática de estimar el valor de los coches que recibe.
Para ello, se ha creado un pipeline completo de Machine Learning que:

* Analiza los datos originales
* Limpia y transforma las variables
* Entrena varios modelos
* Selecciona el más preciso y estable

## **📁 2. Estructura del proyecto**

```Estructura
├── EliasRobles_Proyecto_Machine_Learning.ipynb
├── /Images/
│   └── (Imagenes usadas en el cuaderno)
├── /Dataset/
│   └── car_prices.csv
└── /Dataset/
    └── (Archivos de Modelos y otros)
```

## **📊 3. Contenido del Notebook**

El notebook incluye:

✔ Exploración de datos:

* Distribuciones de año, marca, modelo, carrocería y estado del vehículo
* Análisis de odómetro y precios MMR
* Histogramas y gráficos descriptivos
* Detección y tratamiento de valores nulos

✔ Preparación de datos:

* Limpieza y formateo de columnas
* Codificación de variables categóricas (OrdinalEncoder)
* División en training y test
* Revisión de correlaciones

✔ Modelos entrenados:

* DecisionTreeRegressor
* DecisionTree limitado
* RandomForestRegressor
* RandomForest limitado
* Linear Regression
* Ridge Regression

✔ Evaluación:

* Métricas MAE, MSE, RMSE, R²
* Validación cruzada con 3 folds
* Comparación entre modelos

## **🏆 4. Resultados principales**

Los resultados muestran que:

* Los árboles de decisión funcionan bien pero son los peores del conjunto.
* Los Random Forest obtienen un rendimiento muy alto y muy consistente.
* La regresión lineal y Ridge funcionan sorprendentemente bien, con resultados comparables a Random Forest.
* El modelo más robusto y preciso termina siendo el Random Forest limitado.

## **📌 5. Tecnologías utilizadas**

* Python
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-Learn
* Jupyter Notebook

## **▶️ 6. Cómo ejecutar el proyecto**

* Clonar o descargar el repositorio.
* Instalar dependencias.
* Abrir el notebook: `EliasRobles_Proyecto_Machine_Learning.ipynb`
* Ejecutar las celdas en orden

## **🧑‍💻 Autor**

### *Elías Robles Ruiz*

Proyecto realizado para el Máster de Inteligencia Artificial y Big Data.

## 📄 Licencia

Este proyecto está licenciado bajo la **MIT License**.

Puedes usar, copiar, modificar y distribuir el código libremente, siempre que mantengas la atribución al autor original.
