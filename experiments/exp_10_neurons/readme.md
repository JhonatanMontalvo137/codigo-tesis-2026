# Experimento: Arquitectura con pocas neuronas (10 neuronas)

## Resumen General

- **Total de corridas**: 100
- **Corridas exitosas**: 16 (16%)
- **Corridas fallidas**: 84 (84%)
- **Tasa de éxito**: 16%

Este experimento corresponde a una arquitectura reducida (10 neuronas por capa), lo que explica la baja tasa de convergencia.

## Primeras 5 corridas

| run | loss           | max_error | success | epochs_used |
|-----|----------------|-----------|---------|-------------|
| 1   | 1.112256e-11  | 0.002806 | False   | 2000        |
| 2   | 1.541470e-11  | 0.003439 | False   | 2000        |
| 3   | 8.291051e-02  | 1.991917 | False   | 2000        |
| 4   | 1.533581e-12  | 0.005337 | False   | 2000        |
| 5   | 1.122883e-01  | 2.030587 | False   | 2000        |

## Estadísticas Descriptivas

**Loss:**
- Media: 0.029923
- Mediana: 0.000159
- Mínimo: 1.53e-12
- Máximo: 0.2777

**Max Error:**
- Media: 0.805886
- Mediana: 0.020708
- Mínimo: 0.000628
- Máximo: 2.166483

## Observaciones

- Solo el **16%** de las corridas logró converger satisfactoriamente.
- La mayoría de los entrenamientos se estancaron con errores altos.
- Este experimento sirve como **contraste** respecto a arquitecturas más grandes (50 neuronas), donde se observó mucho mejor rendimiento.

## Archivos disponibles

- `results_experiment.csv` → Tabla completa de las 100 corridas
- `config.json` → Configuración usada
- `model_run_*.pt` → Modelos guardados (solo los exitosos o todos según configuración)
