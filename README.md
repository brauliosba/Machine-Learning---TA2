# Machine-Learning---TA2


COMO FUNCIONA:
En las redes neuronales, la red neuronal convolucional (CNN) es una de las principales categorías para hacer reconocimiento de imágenes, clasificaciones de imágenes. La detección de objetos,  reconocimiento de rostros, etc.
Las clasificaciones de imágenes de CNN toman una imagen de entrada, la procesan y la clasifican en ciertas categorías (por ejemplo, perro, gato, tigre, león). Las computadoras ven una imagen de entrada como una matriz de píxeles y depende de la resolución de la imagen. Según la resolución de la imagen, verá alto x ancho x profundidad (alto = alto, ancho = ancho, d = dimensión). Por ejemplo, una imagen de matriz de matriz de 6 x 6 x 3 de RGB (3 se refiere a valores RGB) y una imagen de matriz de matriz de 4 x 4 x 1 de imagen en escala de grises.

Secuencia de un CNN:
-Se proporcione la imagen de entrada en la capa de convolución
-Se elijen parámetros, aplican filtros con pasos, relleno si es necesario. Se realiza la convolución en la imagen y aplica la activación ReLU a la matriz.
Se realiza agrupación para reducir el tamaño de dimensionalidad
Se agregan tantas capas convolucionales hasta que esté satisfecho
Se aplana la salida y alimenta a una capa completamente conectada (capa FC)
Se imprime la clase usando una función de activación (Regresión logística con funciones de costo) y clasifica imágenes.
