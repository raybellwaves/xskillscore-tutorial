.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/raybellwaves/xskillscore-tutorial/master?urlpath=lab

xskillscore-tutorial
====================

Welcome to the `xskillscore <https://github.com/raybellwaves/xskillscore>`_ tutorial.

You can run this tutorial interactively by clicking on the
`launch | binder <https://mybinder.org/v2/gh/raybellwaves/xskillscore-tutorial/master?urlpath=lab>`_
button at the top.

Otherwise you can clone and run locally:

.. code-block:: bash
    $ git clone https://github.com/raybellwaves/xskillscore-tutorial.git
    $ cd xskillscore-tutorial
    $ conda env create -f binder/environment.yml
    $ conda activate xskillscore-tutorial
    $ jupyter labextension install dask-labextension
    $ jupyter labextension install @jupyter-widgets/jupyterlab-manager
    $ jupyter labextension install @bokeh/jupyter_bokeh
    $ jupyter lab workspaces import binder/jupyterlab-workspace.json


