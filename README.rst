.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/raybellwaves/xskillscore-tutorial/master?urlpath=lab

xskillscore-tutorial
====================

Welcome to the `xskillscore <https://github.com/raybellwaves/xskillscore>`_ tutorial.

This was designed for a talk at the `Data Science Study Group: South Florida
<https://www.meetup.com/Data-Science-Study-Group-South-Florida/>`_ on April 1 :sup:`st` 2020.

Running
-------

You can run this tutorial interactively by clicking on the
`launch | binder <https://mybinder.org/v2/gh/raybellwaves/xskillscore-tutorial/master?urlpath=lab>`_
button at the top.

You can also clone and run locally:

.. code-block:: bash

   $ git clone https://github.com/raybellwaves/xskillscore-tutorial.git
   $ cd xskillscore-tutorial
   $ conda env create -f binder/environment.yml
   $ conda activate xskillscore-tutorial
   $ jupyter labextension install dask-labextension
   $ jupyter labextension install @jupyter-widgets/jupyterlab-manager
   $ jupyter labextension install @bokeh/jupyter_bokeh
   $ jupyter lab workspaces import binder/jupyterlab-workspace.json

References
----------

This tutoial was adapted from the `dask-tutorial <https://github.com/dask/dask-tutorial>`_.


