# install-tensorflow-on-windows
Follow the installation steps in the PDF files without any changes. It should work right away
To test your installation, in spyder you write the heelo world code

import tensorflow as tf
hello = tf.constant('Hello, TensorFlow!')
sess = tf.Session()
print(sess.run(hello))
