# Songs Population

By: Jacobo Ayala Giraldo

## Descripción del Proyecto

Este proyecto utiliza técnicas de machine learning y deep learning para predecir la popularidad de canciones basándose en sus características musicales. El objetivo es desarrollar modelos que puedan estimar qué tan popular podría ser una canción basándose en sus atributos técnicos y musicales.

## Estructura del Proyecto

```
songs_population/
├── data/
│   ├── processed/          # Datos procesados y limpios
│   └── raw/               # Datos originales sin procesar
├── notebooks/
│   ├── preprocessing_songs_population-introduction.ipynb  # Preprocesamiento inicial
│   ├── data_visualization.ipynb                          # Análisis visual de datos
│   ├── featuring_decomposition.ipynb                     # Análisis de características
│   ├── selecting_features.ipynb                          # Selección de features
│   ├── Machine Learning/
│   │   └── linear_regression.ipynb                       # Modelo de regresión lineal
│   └── Neuronal Networks/
│       └── neuronal_netowork.ipynb                       # Modelo de red neuronal
```

## Metodología

El proyecto sigue los siguientes pasos:

1. **Preprocesamiento de Datos**
   - Limpieza de datos musicales
   - Transformación y normalización de características
   - Manejo de valores faltantes

2. **Análisis Exploratorio**
   - Visualización de distribuciones de popularidad
   - Análisis por género musical
   - Identificación de correlaciones entre características

3. **Modelado**
   - Implementación de modelos de regresión lineal
   - Desarrollo de redes neuronales
   - Comparación de rendimiento entre modelos

## Configuración del Entorno

### Requisitos
- Python 3.10
- Conda (recomendado para gestión del entorno)

### Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/jaayg23/songs_popularity.git
cd songs_population
```

2. Crear y activar el entorno conda:
```bash
conda env create -f environment.yml
conda activate songs_population
```

## Resultados

Los resultados del análisis y predicciones se pueden encontrar en:
- `notebooks/Machine Learning/real_vs_predicted_popularity.png`: Comparación visual entre popularidad real y predicha
- `notebooks/popularity_by_genre.png`: Análisis de popularidad por género musical

