# Perceptrón multicapa — Evaluación de desempeño

Actividad de la Semana 2 del curso **Inteligencia Artificial y Sistemas Inteligentes** (UNIMINUTO, Ingeniería de Software).

Implementación paso a paso de un perceptrón multicapa (MLP) para clasificación binaria con Keras/TensorFlow, aplicando aprendizaje supervisado, normalización de datos, partición entrenamiento/prueba y evaluación con métricas (accuracy, AUC-ROC, matriz de confusión, precisión, recall y F1).

**Autor:** Alejandro [apellidos]

## Contenido

| Archivo | Qué contiene |
| --- | --- |
| `perceptron_multicapa.ipynb` | Notebook con el desarrollo completo; cada sección corresponde a un paso del reporte (4.1 a 4.8) |
| `requirements.txt` | Librerías necesarias para ejecutar el notebook |
| `figuras/` | Gráficas generadas por el notebook |

## Cómo ejecutarlo

**Opción 1 — Google Colab (sin instalar nada):** abrir `perceptron_multicapa.ipynb` desde GitHub en [Colab](https://colab.research.google.com/) y ejecutar las celdas en orden.

**Opción 2 — En el computador:**

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate    |    macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook perceptron_multicapa.ipynb
```

## Pasos del desarrollo

1. Librerías y entorno
2. Generación de los datos
3. División entrenamiento / prueba
4. Normalización
5. Construcción del modelo en Keras
6. Entrenamiento (retropropagación)
7. Evaluación con métricas
8. Comparación con una red simple
