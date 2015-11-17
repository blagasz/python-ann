Programming ANN in Python
=========================



Why Python
----------

Más nyelvekhez képest könnyen elsajátítható.
 ̋
Tömörsége miatt az algoritmusok áttekinthet obbek,
oktatási szempontból a kódok kivetítése kevesebb helyet
igényel. Áttekinthet osége a struktogramokkal vetekszik.
A kód olvashatósága kiemelt szerepet játszik a Pythonban.
Mind a procedurális, az objektumorientált és a funkcionális
központú programozást támogatja.
Rendszer független (Windows, Linux, Mac OS X).
 ̋ ami a háttérkönyvtáraira is igaz
Szabadon letölthet o,
(webkiszolgáló, numerikus és szimbolikus számítások,
szimuláció stb.)

A tudományos számítások területén elterjedt. Olyan drága
szoftverekkel vetekszik, mint a MATLAB, Mathematica
vagy a Maple.

1980-as években kezdte fejleszteni Guido van Rossum.
1989-ben kezd od
az els o  ̋ implementációja.
1994-re elkészült a Python 1.0.
Jelenleg használt változatok a 2.7.5-ös és a 3.3.2-es
verziók.
Többek között használja a YouTube, az eredeti BitTorrent
kliens, a Google, a Yahoo!, a CERN és a NASA




Using Interactive Python
------------------------

http://ipython.org/notebook.html







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
