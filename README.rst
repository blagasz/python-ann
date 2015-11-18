Programming ANN in Python
=========================



Why Python
----------

Easy to learn

Very readable code (easy to follow structure)

Procedural, object-oriented and functional element are
all present to some extent

Available on all platforms

Completele free

Widely used in scientific computing
(as powerful as MATLAB, Mathematica or Maple)

Widely used for general programming tasks


History
*******

1980s Guido van Rossum starts working on Python

1989 first implementation ready

1994 Python 1.0

2008 Python 2to3 transition started

Current versions 3.5.0 and 2.7.10

2 to 3 transition almost finished
https://wiki.python.org/moin/Python2orPython3


Python Tutorial
***************

https://docs.python.org/2/tutorial/index.html




Using Interactive Python
------------------------

http://ipython.org/

http://ipython.org/notebook.html

http://nbviewer.ipython.org/

http://jupyter.readthedocs.org/en/latest/index.html

http://nbviewer.ipython.org/github/masinoa/machine_learning/blob/master/04_Neural_Networks.ipynb

https://www.python.org/shell/

https://repl.it/languages/python3





Tutorials, Packages, Implementations
------------------------------------

Neurolab code

https://github.com/blagasz/neurolab

Neurolab documentation

https://pythonhosted.org/neurolab/index.html



NEURAL NETWORKS by Christos Stergiou and Dimitrios Siganos

http://www.doc.ic.ac.uk/~nd/surprise_96/journal/vol4/cs11/report.html


Neural Network Back-Propagation using Python

https://visualstudiomagazine.com/articles/2014/12/01/back-propagation-using-python.aspx


Neural Networks with backpropagation for XOR using one hidden layer

http://www.bogotobogo.com/python/python_Neural_Networks_Backpropagation_for_XOR_using_one_hidden_layer.php


Simple Back-propagation Neural Network in Python source code

http://code.activestate.com/recipes/578148-simple-back-propagation-neural-network-in-python-s/



Design desisions
----------------

To find the most convenient syntax for creating neural networks
and using them is not straight forward.

Standardize input data

Usually need to experiment with network layout

Let the number of neurons in each layer be *m* for input layer neurons, *n* for
output layer neurons and *p* for the hidden layer, then the training data
input-output numbers should be minimum 10 times ``(m+1)p + (p+1)n``.

The input-output traning pair should be divided in 50:25:25 into
training, testing, and actual working data.


`Analyze standalone code`_

.. _Analyze standalone code: example-simple-bp.py


`Walk through one neurolab example`_

.. _Walk through one neurolab example: example-neurolab.py


