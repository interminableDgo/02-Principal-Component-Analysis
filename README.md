# Análisis de Componentes Principales (PCA) — Wine Quality (White)

Autor: Aldo Elio Peña Salas – 635861

Fecha: 16 de febrero de 2026

Descripción
- Este repositorio contiene un notebook que realiza un análisis exploratorio y una reducción de dimensionalidad por PCA sobre el dataset "Wine Quality (White)". El objetivo es estudiar la estructura de las variables físico-químicas y la varianza explicada por los componentes principales.

Dataset
- Fuente: UCI Machine Learning Repository — White Wine
- URL: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv

Contenido
- Assignment_3_Principal_Components_Analysis (2).ipynb: Notebook con limpieza, EDA, estandarización, cálculo de la matriz de covarianza, eigenvalores/vectores, y visualizaciones 2D/3D de los PCs.

Requisitos
- Python 3.8 o superior
- Instalar dependencias con `pip install -r requirements.txt`

Instrucciones para ejecutar
1. Crear o activar un entorno virtual (recomendado):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Instalar dependencias:

```powershell
pip install -r requirements.txt
```

3. Abrir el notebook con Jupyter Notebook o VS Code y ejecutar las celdas:

```powershell
jupyter notebook "Assignment_3_Principal_Components_Analysis (2).ipynb"
```

Notas
- El notebook descarga el dataset desde la UCI, por lo que no es necesario bajarlo manualmente.
- Si reutilizas el análisis para otro dataset, ajusta la columna objetivo (`quality`) y el separador si es distinto.

Resultados esperados
- Visualizaciones de la matriz de correlación, Scree plot (varianza explicada) y gráficos 2D/3D de los primeros componentes principales. Con las primeras 2-7 componentes se conserva la mayor parte de la varianza.

Créditos
- Notebook y análisis por Aldo Elio Peña Salas.

Licencia
- Uso académico y para fines de aprendizaje. Cite al autor si reutilizas el material.
