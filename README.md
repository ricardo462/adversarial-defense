# adversarial-defense
Poryecto de AI para el curso Inteligencia Computacional El-4106 de la Universidad de Chile, semestre primavera 2021. El proyecto consiste en tres etapas:

- Generación de ejemplos adversarios en la detecección de imágenes de redes neuronales, usando los métodos de FGSM y PGD.
- Implementación de una red neuronal que sea robusta frente a ataques adversarios.
- Ataque de caja negra a un modelo que reconozca imágenes.

En el archivo AdversarialGeneration.ipynb se encuentra el código para generar ejemplos adversarios utilizando los métodos de FGSM y PGD. Para visualizar los resultados se deben correr todas las celdas. 

Por otra parte, en el archivo Adversarial_training.ipynb se encuentra el código que se realizó para el entrenamiento adversario. En el caso de querer realizar el entrenamiento, se deben correrr todas las celdas y cambiar la variable "pretrained" a False. En el caso contrario, se deben correr todas las celdas, menos las de entrenamiento. 

Finalmente, en el archivo BlackBoxAttack.ipynb es tiene el código que se implementó para realizar el ataque adversario. En el caso de querer entrenar el modelo, se deben correr todas las celdas y cambiar las variables "train" y "pretrained" a True y False, respectivamente. 