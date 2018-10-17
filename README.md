__Taller de Deep Learning__

Instrucciones de instalación de programas y librerías para el taller de Deep Learning. CICATA Qro. 2018.


Antes de comenzar, reponde la siguiente encuesta por favor: https://goo.gl/forms/PrqKqTbNFRtNh1zg2.



Aunque tendremos disponibles computadoras de trabajo, te sugerimos traer tu laptop con las siguientes instalaciones:

1) Anaconda con Python 3.4+ (https://www.anaconda.com/download/).

2) También te recomendamos activar una cuenta en Github (github.com) y traer tu usuario y contraseña.



__Instalación de librerías__

conda create -n py36 python=3.6 anaconda

![ima001](https://docs.google.com/drawings/d/e/2PACX-1vTbUqswknPfLuDOWezlqqNNuhZ2hwlSGkxnh-pSieYD3sa_Uh-Yr5-Wq6WVDsJkCGcjHjoaHsw-JsW2/pub?w=753&h=216)

conda activate py36

conda install -c anaconda git jupyter numpy matplotlib cython scikit-image

![ima002](https://docs.google.com/drawings/d/e/2PACX-1vQS5Z2_WR9oDPHOz5g5f0bHot8UpA6meyWwU20HxxsC-h3dDxY4N-o8jRdYI1i8VAbyrThnMMmpwnFx/pub?w=1012&h=307)

conda install anaconda-client

pip install opencv-contrib-python

conda install tensorflow 

conda install -c conda-forge tqdm

conda install -c conda-forge keras

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

![ima003](https://docs.google.com/drawings/d/e/2PACX-1vSeZYvCdT1r0aTybL4pf_IA1frawKi_94KIVfjzFdAoDA4LfHr4vXD2VqHjT0aT1yzWhV9jS2rtE45X/pub?w=1362&h=549)

import tensorflow as tf

hello = tf.constant('Hello, TensorFlow!')

sess = tf.Session()

print(sess.run(hello))

exit()


## Clonación de este repositorio

Desde tu ventana de comandos de Anaconda, ejecuta la siguiente línea:

git clone https://github.com/Laboratorio-imagenes-CICATAQro/Instalaciones-tallerdl.git

cd Instalaciones-tallerdl

![cd](https://docs.google.com/drawings/d/e/2PACX-1vROKmNJ80Rpu6_QtJnSLett-or3dWASUnUZyzi6NaHVciiwOcIy-AkujKJx1DgKizZVWnRx6JtDPAS7/pub?w=933&h=380)



## Entorno virtual

Una vez generado tu entorno virtual (conda create -n py36 python=3.6 anaconda), deberás activarlo para que todas las instalaciones y modificaciones que realices no alteren tu entorno base de anaconda (imagina que estarás trabajando con un usuario adicional en tu computadora llamado py36).

activate py36

Cuando necesites desactivar el entorno, únicamente escribe "deactivate". Considera que deberás haber trabajado desde "Anaconda prompt", es decir, desde el entorno "base".


## Jupyter notebook

Escribe en tu línea de comandos: 

jupyter notebook

![Jupyter](https://docs.google.com/drawings/d/e/2PACX-1vS8k7jfRjA8eNm0iwOlIgyTjQto66Rm4nUM4lrLJUtFeEeLpvTPVqfO4BrNy1r0fNez5-u3Qc1Fug8F/pub?w=957&h=540)

Desde Jupyter Notebook, ejecutaremos algunas prácticas en Python

![Jupyter2](https://docs.google.com/drawings/d/e/2PACX-1vRXxxFsOCAEPAyk1ZIx1Xhz72aQEYnlrebVRZrf7n3ZNat_07EM3r_EfCzCqNnUVMpg8oiYp50QFhhl/pub?w=1040&h=377)

![Jupyter3](https://docs.google.com/drawings/d/e/2PACX-1vSjzhLZYMmdA5lQy2PZrRkNUVmjIAyQp8DgzQzwg_aVGqA6CWSJGxmxiHoNSGboxbw0mM3_x_RuwPi-/pub?w=957&h=446)


## Referencias

1. Python 3.6 documentation.

