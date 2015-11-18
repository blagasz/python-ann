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
(2to3 transition almost finished)
https://wiki.python.org/moin/Python2orPython3




Using Interactive Python
------------------------

http://ipython.org/

http://ipython.org/notebook.html

http://nbviewer.ipython.org/

http://jupyter.readthedocs.org/en/latest/index.html

http://nbviewer.ipython.org/github/masinoa/machine_learning/blob/master/04_Neural_Networks.ipynb



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



Design problems
---------------

To find the most convenient syntax for creating neural networks
and using them is not straight forward.


The non-linear function is confusingly called sigmoid, but uses a tanh. In a lot of people's minds the sigmoid function is just the logistic function 1/1+e^-x, which is very different from tanh! The derivative of tanh is indeed (1 - y**2), but the derivative of the logistic function is s*(1-s). The link does not help very much with this.



Jelölje a továbbiakban m az inputok, n az outputok és p
a rejtett neuronok számát.


Az adatokat érdemes standardizálni.
A rendelkezésre álló input-célérték párok száma (N)
legyen legalább a súlyok számának ((m + 1)p + (p + 1)n)
tízszerese.

Az input-célérték adatokat 50:25:25 arányban érdemes
tanulási, tesztelési és kiértékelési adatokba sorolni. A
tanulási folyamat addig folytatandó, amíg a kiértékelési
adatok a hibafüggvény csökken. Végül a tesztelési
adatokon ellen orizzük,
hogy milyen jó eredményeket
produkál a betanított neurális hálónk.



Analyze standalone code
-----------------------

link



Walk through one neurolab example
-----------------------------

link
