## Heart-Disease-Risk-Prediction-Logistic-Regression-Homework---Tomas-Espitia
Tarea N2 TDSI
Este proyecto implementa un modelo de regresión logística desde cero para la predicción del riesgo de enfermedad cardíaca a partir de variables clínicas. El objetivo principal es comprender y aplicar todas las etapas de un flujo de aprendizaje automático, incluyendo el análisis exploratorio de los datos, el preprocesamiento, el entrenamiento, la evaluación del modelo, la visualización de las fronteras de decisión, la regularización y una implementación exploratoria en la nube mediante Amazon SageMaker.

El modelo se entrena con un conjunto de datos clínicos reales y prioriza la interpretabilidad, lo que lo convierte en una herramienta adecuada como sistema de apoyo a la toma de decisiones en contextos sanitarios.

## Empezando

Estas instrucciones permiten obtener una copia del proyecto en funcionamiento en el equipo local para fines de desarrollo y pruebas. Para la implementación del proyecto en un entorno de ejecución en la nube utilizando Amazon SageMaker, se recomienda consultar la sección de Despliegue.

## Prerrequisitos

Para ejecutar este proyecto es necesario contar con los siguientes requisitos:

- Python 3.9 o superior

- Git

## Librerías necesarias

pip install numpy pandas matplotlib

## Instalación

- Paso 1: Clonar el Respositorio: git clone https://github.com/tu_usuario/heart-disease-logistic-regression.git
cd heart-disease-logistic-regression

- Paso 2: instalar dependencia: pip install numpy pandas matplotlib

- Paso 3 :Ejecutar el NoteBook

## Ejecutando las pruebas 

El proyecto evalúa el desempeño del modelo utilizando métricas estándar de clasificación binaria.

Pruebas de extremo a extremo
Estas pruebas permiten evaluar el funcionamiento completo del modelo, desde la carga y preprocesamiento de los datos hasta la generación de predicciones sobre el conjunto de prueba. Para esta evaluación se utilizan métricas como accuracy, precision, recall y F1-score, las cuales permiten medir de forma integral el desempeño del clasificador.
