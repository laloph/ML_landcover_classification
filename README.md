# Clasificación de Cobertura del Suelo con Random Forest  
# Land Cover Classification with Random Forest

## 🧠 Descripción del Proyecto / Project Description

**Español:**  
Este proyecto de Machine Learning tiene como objetivo clasificar diferentes tipos de cobertura del suelo utilizando datos ambientales y topográficos. Se ha empleado el **Forest Cover Type Dataset** del UCI Machine Learning Repository para entrenar un modelo de clasificación basado en **Random Forest**. Este proyecto surge del interés en aplicar técnicas de ML en geología y minería, donde la identificación y clasificación del terreno es fundamental para la planificación y gestión ambiental.

**English:**  
This Machine Learning project aims to classify different land cover types using environmental and topographic data. The **Forest Cover Type Dataset** from the UCI Machine Learning Repository was used to train a classification model based on **Random Forest**. This project stems from the interest in applying ML techniques in geology and mining, where identifying and classifying terrain is crucial for planning and environmental management.

---

## 📊 Dataset

- **Nombre / Name:** Forest Cover Type Dataset  
- **Fuente / Source:** [UCI ML Repository](https://archive.ics.uci.edu/dataset/31/covertype)  
- **Formato / Format:** CSV  
- **Descripción / Description:**  
  Contiene variables geográficas y topográficas (como altitud, pendiente, distancias y tipos de suelo) con la etiqueta `Cover_Type`, que clasifica el tipo de cobertura del suelo en 7 clases.  
  Includes geographic and topographic variables (such as elevation, slope, distances, and soil types) with the `Cover_Type` label that classifies land cover into 7 classes.

- **Tamaño / Size:**  
  Aproximadamente 581,012 registros y 55 columnas (dataset completo) / Muestra de 10,000 registros para GitHub.  
  Approximately 581,012 records and 55 columns (full dataset) / Sample of 10,000 records for GitHub.

---

## 📁 Estructura del Proyecto / Project Structure

ML_landocover_classification/
├── README.md
├── .gitignore
└── src/
├── data_sample/ # Muestra del dataset (<5MB)
├── img/ # Imágenes como portada y matriz de confusión
├── models/ # Modelo entrenado en formato .pkl video y dataset
├── notebooks/ # Notebooks exploratorios y de pruebas
├── results_notebook/ # Notebook final limpio y ejecutable
└── utils/ # Funciones auxiliares y scripts


---

## 🧪 Solución Adoptada / Solution Approach

1. Análisis exploratorio de datos (EDA) / Exploratory Data Analysis (EDA)
2. Limpieza y preparación del dataset / Data cleaning and preparation
3. Entrenamiento del modelo con `RandomForestClassifier` / Model training with `RandomForestClassifier`
4. Evaluación con matriz de confusión y métricas de clasificación / Evaluation using confusion matrix and classification metrics
5. Guardado del modelo final en formato `.pkl` / Saving the final model in `.pkl` format

---

## ▶️ Cómo Ejecutar / How to Run

1. Clona este repositorio / Clone this repository:
   ```bash
   git clone https://github.com/tuusuario/ML_landcover_classification.git

2. Instala las dependencias / Install dependencies:

pip install -r requirements.txt

3. Ejecuta el notebook en src/results_notebook/ML_landcover_classification.ipynb
Run the notebook located at src/results_notebook/ML_landcover_classification.ipynb.

4. El modelo entrenado se guardará en src/models/random_forest_covertype.pkl
The trained model will be saved in src/models/random_forest_covertype.pkl.

🎥 Presentación / Presentation
El proyecto está acompañado por una presentación en formato PowerPoint (ES + EN) y un video de máximo 7 minutos explicando el desarrollo y los resultados del modelo.
The project is accompanied by a PowerPoint presentation (ES + EN) and a video of up to 7 minutes explaining the development and results of the model.

🙌 Autor / Author
Eduardo Pérez Hernández
Bootcamp de Data Science - The Bridge



