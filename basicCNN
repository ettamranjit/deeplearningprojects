import numpy as np
import tensorflow as tf
import matplotlib.pyplot as plt
from itertools import product
 
# set the param
plt.rc('figure', autolayout=True)
plt.rc('image', cmap='magma')
 
# define the kernel
kernel = tf.constant([[-1, -1, -1],
                    [-1,  8, -1],
                    [-1, -1, -1],
                   ])
 
# load the image
image = tf.io.read_file('Ganesh.jpg')
image = tf.io.decode_jpeg(image, channels=1)
image = tf.image.resize(image, size=[300, 300])
