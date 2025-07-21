# Curvas de Rotación de Galaxias

Este repositorio contiene un código en Python para realizar ajustes de datos experimentales de curvas de rotación de galaxias.

## Objetivo

- Ajustar datos observacionales de velocidad en función del radio galáctico usando métodos de regresión.
- Calcular parámetros del ajuste, sus errores y la varianza residual.
- Evaluar la calidad del ajuste mediante la fracción de varianza explicada.
- Visualizar y guardar la gráfica resultante.

## Contenido

- `rotation_curve_fit.ipynb`: Notebook con el código para el ajuste y visualización.
- `data/GALAXIA7331.txt`: Archivo con los datos de velocidad radial y radio de la galaxia NGC 7331.
- `requirements.txt`: Dependencias necesarias para ejecutar el código.

## Cómo usar

1. Clonar el repositorio
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
