# DEEP LEARNING PARA EL RECONOCIMIENTO DE IMÁGENES: ENTRENAMIENTO DE REDES CONVOLUCIONALES MEDIANTE EL ALGORITMO ADAM

Trabajo de fin de grado del grado de Ingeniería informática en la Universidad Rey Juan Carlos de Madrid.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />La memoria está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional</a>.


## Resumen
El siguiente trabajo de fin de grado pretende explicar de manera sencilla, y sin necesidad de conocimientos previos, la teoría necesaria para entender cómo se realiza el reconocimiento de imágenes digitales y los algoritmos de optimización utilizados en su aplicación. 

Con el objetivo de asentar los conocimientos básicos de visión artificial e introducir los cimientos de este campo, se explican los términos de inteligencia artificial y aprendizaje automático y se explican las redes neuronales y su funcionamiento básico.

Las redes neuronales son el principal modelo de computación en el deep learning, un subcampo del aprendizaje automático centrado en redes neuronales profundas, es decir, con una gran cantidad de capas y neuronas. Se relatan los beneficios que tiene la implementación de un modelo de IA basado en deep learning y cómo se construye una red neuronal sencilla.

Con estos conocimientos explicados se introducen las redes neuronales convolucionales, redes específicas para el reconocimiento de imágenes. Este tipo de redes permiten guardar o captar las relaciones entre los píxeles de una imagen para extraer información útil y aumentar la eficacia del entrenamiento. 

Se explican los diferentes algoritmos de optimización que pueden ser utilizados en el reconocimiento de imágenes y se realiza un experimento para medir los resultados de diferentes modelos de reconocimiento de imágenes con los conjuntos de datos MNIST y CIFAR-10.

Este experimento se ha realizado utilizando el framework Pytorch. Pytorch es una framework de código abierto escrito en Python que facilita la investigación de prototipos basados en redes neuronales. Cuenta con una gran cantidad de manuales y una interfaz sencilla para la creación de modelos de deep learning. 

Con los resultados del experimento se ha llevado a cabo una comparativa del rendimiento y desempeño de los diferentes algoritmos en los modelos llegando varias conclusiones o ideas. Estos algoritmos son el gradiente descendente estocástico, con y sin momento, y el algoritmo ADAM.

El algoritmo ADAM es utilizado actualmente por numerosas aplicaciones dado su grado de eficiencia y rapidez a la hora de conseguir modelos óptimos basados en deep learning. Este algoritmo se basa en el uso del momento y tasas de aprendizaje adaptativos para cada parámetros ajustable de la red neuronal.

Se concluye con un resumen de los objetivos conseguidos, observaciones obtenidas del experimento y líneas futuras de investigación.

## Software utilizado
 - Red neuronal de ejemplo
    - Documento --> NNSample.ipynb
 - Clasificador de imágenes de la base de datos MNIST
    - Documento --> MNISTClassifier.ipynb
 - Clasificador de imágenes de la base de datos CIFAR-10
    - Documento --> CIFAR-10Classifier.ipynb
    
## Software License
[MIT](https://github.com/ARubiose/TFG-Reconocimiento-Imagenes/blob/master/LICENSE)
