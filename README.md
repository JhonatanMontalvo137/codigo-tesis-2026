# Códigos de la Tesis - Licenciatura en Matemáticas

Repositorio con los códigos utilizados en mi tesis de **Licenciatura** titulada:

> "**Implementación numérica de la ecuación de Poisson para campos gravitacionales mediante PINNs**"

**Universidad:** Universidad Abierta y a Distancia de México 
**Autor:** Jhonatan Alonso Montalvo Adrián  
**Año:** 2026

## Descripción del Proyecto

Este repositorio contiene la implementación en **PyTorch** de modelos basados en **Physics-Informed Neural Networks (PINNs)** para resolver la ecuación de Poisson en 1D y 2D.

Se incluyen:
- Entrenamiento de múltiples corridas con diferentes configuraciones.
- Análisis de pesos y sesgos de los modelos entrenados.
- Scripts y notebooks para reproducir los experimentos.

## Estructura del Repositorio

- **`notebooks/`** → Notebooks principales de Google Colab (análisis y experimentos)
- **`src/`** → Código fuente modular y reutilizable
- **`scripts/`** → Scripts para ejecutar experimentos completos
- **`experiments/`** → Resultados de los entrenamientos (modelos `.pt`)
- **`figures/`** → Gráficos generados
- **`results/`** → Tablas y resúmenes

## Notebooks Principales

| Notebook | Descripción |
|----------|-----------|
| `01_Poisson1D_Torch_100run.ipynb` | Experimentos de entrenamiento masivo (100 corridas) para la ecuación de Poisson 1D |
| `02_Analisis_pesos_y_sesgos.ipynb` | Análisis estadístico de pesos y sesgos de los modelos entrenados |
