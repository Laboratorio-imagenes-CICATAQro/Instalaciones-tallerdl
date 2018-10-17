__Taller de Deep Learning__

Instrucciones de instalación de programas y librerías para el taller de Deep Learning. CICATA Qro. 2018.

Antes de comenzar, llena la siguiente encuesta por favor: https://goo.gl/forms/PrqKqTbNFRtNh1zg2.


Aunque tendremos disponibles computadoras de trabajo, te sugerimos traer tu laptop con las siguientes instalaciones:

1) Anaconda con Python 3.4+ (https://www.anaconda.com/download/).

2) También te recomendamos activar una cuenta en Github (github.com) y traer tu usuario y contraseña.


__Instalación de librerías__

conda create -n py36 python=3.6 anaconda

![ima001](https://docs.google.com/drawings/d/e/2PACX-1vTbUqswknPfLuDOWezlqqNNuhZ2hwlSGkxnh-pSieYD3sa_Uh-Yr5-Wq6WVDsJkCGcjHjoaHsw-JsW2/pub?w=753&h=216)

conda activate py36

conda install -c anaconda git jupyter numpy matplotlib cython scikit-image

![ima002](https://docs.google.com/drawings/d/e/2PACX-1vQS5Z2_WR9oDPHOz5g5f0bHot8UpA6meyWwU20HxxsC-h3dDxY4N-o8jRdYI1i8VAbyrThnMMmpwnFx/pub?w=405&h=124)

conda install anaconda-client

pip install opencv-contrib-python

conda install tensorflow 

conda install -c conda-forge tqdm

conda install pytictoc -c ecf

conda update --all


# Verificación de instalación

Probablemente te preguntes ¿Cómo puedes comprobar que tu instalación es correcta? Escribe las siguientes líneas de código:

python -V

git --version

jupyter --version

python

import numpy as np

import matplotlib as plt

import cv2

cv2.__version__

![ima003](https://docs.google.com/drawings/d/e/2PACX-1vSeZYvCdT1r0aTybL4pf_IA1frawKi_94KIVfjzFdAoDA4LfHr4vXD2VqHjT0aT1yzWhV9jS2rtE45X/pub?w=380&h=155)

import tensorflow as tf

hello = tf.constant('Hello, TensorFlow!')

sess = tf.Session()

print(sess.run(hello))

exit()


## Clonación de este repositorio

Desde tu ventana de comandos de Anaconda, ejecuta la siguiente línea:

git clone https://github.com/Laboratorio-imagenes-CICATAQro/Instalaciones-tallerdl.git

Anota la dirección en la que clonaste el directorio de "Instalaciones-tallerdl".

Abre el directorio en donde clonaste el repositorio con el comando "cd", como se muestra en la siguiente imagen.

![cd](https://github.com/SandraFB/instalaciones/blob/master/imagen14.jpg)



## Entorno virtual

Una vez generado tu entorno virtual (conda create -n py36 python=3.6 anaconda), deberás activarlo para que todas las instalaciones y modificaciones que realices no alteren tu entorno base de anaconda (imagina que estarás trabajando con un usuario adicional en tu computadora llamado py36).

activate py36

Cuando necesites desactivar el entorno, únicamente escribe "deactivate". Considera que deberás haber trabajado desde "Anaconda prompt", es decir, desde el entorno "base".




## Jupyter notebook

Escribe en tu línea de comandos: 

jupyter notebook

![Jupyter](https://github.com/SandraFB/instalaciones/blob/master/imagen15.jpg)

Desde Jupyter Notebook, crearemos un nuevo documento:

![Nuevo](https://github.com/SandraFB/instalaciones/blob/master/imagen3.jpg)

![Nuevo Notebook](https://github.com/SandraFB/instalaciones/blob/master/imagen6.jpg)

3. Prácticas en Python

A forma de taller introductorio para Python, puedes ejecutar las prácticas 1, 2 y 3 en Jupyter Notebook.

Primero selecciona la práctica a realizar y abre el enlace.


![Selección](https://github.com/SandraFB/instalaciones/blob/master/imagen9.jpg)


Después, ejecuta el código línea por línea y observa el resultado.


![Ejecución](https://github.com/SandraFB/instalaciones/blob/master/imagen10.jpg)



## Referencias

1. Python 3.6 documentation.

