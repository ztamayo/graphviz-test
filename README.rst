**************
graphviz-test
**************
Testing graphviz

Create .dot file
#################

.. code-block::
  > file.dot

Edit .dot file
###############

.. code-block::
  digraph test {
  A->B
  B->C
  }

Create graph from .dot file
##############################

.. code-block::
  dot -Tpng file.dot > file.png		
-T(extension of graph file)

Open .png file
################

.. image:: graphs/file.png
