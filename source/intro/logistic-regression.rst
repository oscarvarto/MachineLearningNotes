Logistic Regression
===================

Model for logistic regression

.. math::

   \hat{y} = \frac{1}{1 + e^{-v}}

.. plot::

   import numpy as np
   import matplotlib.pyplot as plt

   v = np.linspace(-2 * np.pi, 2 * np.pi)
   y_hat = 1 / (1 + np.exp(-v))
   plt.plot(v, y_hat)
   plt.grid()
   plt.show()
