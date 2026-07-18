# Predicción de accidentes de tráfico mediante análisis de Big Data

Proyecto académico orientado al análisis de factores asociados con los accidentes de tráfico y al desarrollo progresivo de un modelo predictivo que apoye la toma de decisiones en materia de seguridad vial.

## Descripción

El proyecto analiza un conjunto de datos con información sobre condiciones climáticas, características de la carretera, densidad del tráfico, límite de velocidad, tipo de vehículo y datos generales del conductor.

El objetivo es identificar patrones y preparar los datos para predecir la ocurrencia y la severidad de accidentes mediante técnicas de análisis de datos y machine learning.

> **Estado del proyecto:** fase exploratoria. El repositorio incluye la propuesta, el análisis inicial del conjunto de datos, visualizaciones y la división de los registros en conjuntos de entrenamiento y prueba. Todavía no contiene un modelo predictivo final desplegado.

## Objetivo general

Desarrollar un modelo predictivo que permita analizar factores de riesgo y estimar la ocurrencia y severidad de accidentes de tráfico a partir de datos históricos.

## Trabajo realizado

- Definición del problema, justificación y objetivos del proyecto.
- Carga e inspección inicial del conjunto de datos.
- Identificación de tipos de datos y valores faltantes.
- Generación de estadísticas descriptivas.
- Análisis exploratorio mediante gráficos e histogramas.
- Evaluación inicial de variables como límite de velocidad, tipo de carretera y condiciones del entorno.
- División aleatoria de los datos en:
  - 80 % para entrenamiento.
  - 20 % para prueba.

## Conjunto de datos

Se utiliza el dataset **Traffic Accident Prediction**, disponible en Kaggle. El notebook trabaja con aproximadamente 840 registros y 14 variables.

Entre las variables analizadas se encuentran:

- `Weather`: condición climática.
- `Road_Type`: tipo de carretera.
- `Time_of_Day`: momento del día.
- `Traffic_Density`: densidad del tráfico.
- `Speed_Limit`: límite de velocidad.
- `Number_of_Vehicles`: cantidad de vehículos involucrados.
- `Driver_Alcohol`: presencia de consumo de alcohol.
- `Accident_Severity`: severidad del accidente.
- `Road_Condition`: condición de la carretera.
- `Vehicle_Type`: tipo de vehículo.
- `Driver_Age`: edad del conductor.
- `Driver_Experience`: experiencia del conductor.
- `Road_Light_Condition`: condición de iluminación.
- `Accident`: indicador de ocurrencia del accidente.

Fuente del dataset: [Traffic Accident Prediction en Kaggle](https://www.kaggle.com/datasets/denkuznetz/traffic-accident-prediction)

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Anaconda
- Git y GitHub

## Estructura del repositorio

```text
Proyecto_BigData/
├── Borrador/
│   └── Propuesta de proyecto.ipynb
└── .gitignore
```

## Ejecución local

### 1. Clonar el repositorio

```bash
git clone https://github.com/carvamar/Proyecto_BigData.git
cd Proyecto_BigData
```

### 2. Crear y activar un entorno virtual

```bash
python -m venv .venv
```

En Windows:

```bash
.venv\Scripts\activate
```

En macOS o Linux:

```bash
source .venv/bin/activate
```

### 3. Instalar las dependencias

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Agregar el dataset

El notebook espera encontrar el archivo:

```text
dataset_traffic_accident_prediction1.csv
```

Colóquelo en el directorio desde el cual se ejecutará el notebook o actualice la ruta definida en el código.

### 5. Abrir Jupyter Notebook

```bash
jupyter notebook
```

Luego abra:

```text
Borrador/Propuesta de proyecto.ipynb
```



## Alcance y limitaciones

Este es un proyecto académico y exploratorio. 
## Autora

**María del Mar Canales Carvajal**

- GitHub: [carvamar](https://github.com/carvamar)
- LinkedIn: [mariacanales](https://www.linkedin.com/in/mariacanales)
