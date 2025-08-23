# 📘 proyecto Analisis de datos

Primera parte: <br>
Estudiantes: <br>
ALEJANDRA FORERO RODRIGUEZ  <br>
JOSE REALPE MUÑOZ  <br>
SANTIAGO ARISTIZABAL MORALES  <br>
1. Descripción del problema: <br>
Las lesiones en fútbol universitario generan pérdidas de minutos de juego, bajo rendimiento y
costos de rehabilitación; predecir el riesgo de lesión permite ajustar cargas de entrenamiento y
reducir bajas en la siguiente temporada. El dataset seleccionado fue creado precisamente para
“predecir si un jugador sufrirá una lesión en la próxima temporada académica.”
2. Justificación del uso de Ciencia de Datos o IA: <br>
Este problema puede resolverse efectivamente utilizando algoritmos de aprendizaje
automático para clasificación binaria aplicados a la predicción de lesiones deportivas. Los datos
disponibles en el dataset "University Football Injury Prediction Dataset" incluyen 18
características comprehensivas de 800 jugadores universitarios, abarcando:
• Datos físicos: edad, altura, peso, BMI
• Métricas específicas del fútbol: posición, horas de entrenamiento, historial de partidos
• Evaluaciones de condición física: fuerza, flexibilidad, velocidad, agilidad
• Factores de estilo de vida: sueño, estrés, nutrición
• Cumplimiento de entrenamiento: adherencia a programas establecidos
La variable objetivo "Injury_Next_Season" permite entrenar modelos de clasificación binaria
para predecir si un jugador sufrirá una lesión que cause ≥7 días consecutivos de ausencia en la
siguiente temporada académica.
Los enfoques de IA más adecuados incluyen:
• Métodos basados en árboles como Random Forest y XGBoost
• Redes Neuronales y Máquinas de Vectores de Soporte para capturar patrones
complejos
• Análisis de series temporales para evaluar tendencias de carga de entrenamiento
3. Formulación de una pregunta SMART: <br>
"¿Es posible desarrollar un modelo de clasificación de aprendizaje supervisado capaz de
predecir con una precisión, AUC-ROC, o F1-Score ≥ 0.85 qué jugadores de fútbol universitario
sufrirán lesiones en los próximos 6 meses, utilizando datos de características físicas, técnicas y
de estilo de vida dataset 'University Football Injury Prediction Dataset' para informar la creación
de un programa de intervención preventiva personalizado que se implementará para la
temporada 2025-2026?"


# My Project

This repository contains the analysis and results of my project.

## Notebooks

- [Analisis Univariado](analisis_univariado.ipynb)
- [Analisis Bivariado](analisis_bivariado.ipynb)
- [Diccionario de datos](DiccionarioDatos.txt)
- [Analisis y creacion de modelos](main.ipynb)





## ⚙️ Requirements
- [Python 3.10+](https://www.python.org/)  
- [uv package manager](https://github.com/astral-sh/uv)  
- [VS Code](https://code.visualstudio.com/) with the **Python** and **Jupyter** extensions  

---

## 🚀 Setup

Clone the repository:
```bash
git clone https://github.com/sam2800ml/Proyecto-Anlisis-de-datos-1
```

1. Install dependencies with uv
```bash
uv sync
```
This will create a .venv/ folder with all the required dependencies defined in pyproject.toml and locked in uv.lock.

2. Register the Jupyter kernel
```bash
uv run python -m ipykernel install --user --name=project-name --display-name "Python (project-name)"
```
--name=project-name → internal ID (use your project name)
--display-name → what will appear in VS Code’s kernel picker

3. Open in VS Code

Open the project folder in VS Code.
Open any .ipynb file.
Select the kernel Python (project-name) from the top-right kernel picker.