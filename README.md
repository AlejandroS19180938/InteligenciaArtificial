# Inteligencia Artificial

Prácticas de la materia de **Inteligencia Artificial** en el Instituto Tecnológico de San Luis Potosí. El repositorio va desde implementar a mano los modelos clásicos (Perceptrón y Adaline) con NumPy, hasta entrenar redes neuronales con TensorFlow/Keras.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## Contenido

### `perceptron/`: modelos clásicos desde cero

| Archivo | Qué hace |
|---|---|
| `practica1_advertising.py` | Perceptrón que predice si un usuario hace clic en un anuncio a partir del tiempo en el sitio y su edad (dataset *Advertising*). |
| `practica3_iris.py` | Perceptrón aplicado al dataset Iris para separar *setosa* de *versicolor*. Descarga los datos directamente del repositorio UCI. |
| `perceptron_adaline_carros.py` | Clasificación de **carros vs. camionetas** por tamaño y velocidad. Compara el Perceptrón con Adaline (descenso de gradiente) usando distintas tasas de aprendizaje y grafica las regiones de decisión. |

### `redes-neuronales-tensorflow/`: redes neuronales con Keras

| Notebook | Qué hace |
|---|---|
| `practica1_conversion_temperatura.ipynb` | Una red de una sola neurona aprende a convertir °C a °F sin conocer la fórmula, y después reutiliza el mismo enfoque para convertir litros a galones. Exporta el modelo a TensorFlow.js. |
| `practica2_clasificador_fashion_mnist.ipynb` | Red densa que clasifica prendas de ropa del dataset **Fashion-MNIST** en 10 categorías. |

Los notebooks tienen un botón **Open in Colab** para abrirlos y ejecutarlos directamente en el navegador.

### `investigacion/`

- `perceptron_adaline_riesgos_empresariales.pdf`: investigación sobre el uso del Perceptrón y Adaline para identificar riesgos en el sector empresarial (detección de fraudes, riesgo crediticio, etc.).

## Cómo ejecutarlo

```bash
git clone https://github.com/AlejandroS19180938/InteligenciaArtificial.git
cd InteligenciaArtificial
pip install -r requirements.txt

# Ejemplo: Perceptrón con el dataset Iris
python perceptron/practica3_iris.py
```

> `practica1_advertising.py` necesita `advertising.csv` y `perceptron_adaline_carros.py` necesita `Cars.csv`. Coloca cada CSV en la carpeta desde donde ejecutes el script.

## Autor

**Luis Alejandro Soto Loredo**, Instituto Tecnológico de San Luis Potosí
