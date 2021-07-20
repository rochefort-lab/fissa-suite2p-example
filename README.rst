FISSA Suite2p Example
=====================
In the notebook we provide an example workflow to combine the `FISSA <fissa_>`_ and `Suite2p <suite2p_>`_ methods.

This repository mainly functions to provide environment files to run this notebook on `Binder <Binder_>`_.
For the most up-to-date code see the original `FISSA <fissa_>`_ repository.

You can `view <suitehtml_>`_ the notebook or directly interact with it on `Binder <suitebind_>`_. The notebook can also be separately `downloaded <suitedown_>`_.


.. _Binder: https://mybinder.org/v2/gh/rochefort-lab/fissa/master?filepath=examples

.. _fissa: https://github.com/rochefort-lab/fissa

.. _suite2p: https://suite2p.readthedocs.io/
.. _suitebind: https://mybinder.org/v2/gh/rochefort-lab/fissa-suite2p-example/master?filepath=Suite2p%20example.ipynb
.. _suitehtml: https://rochefort-lab.github.io/fissa/examples/Suite2p%20example.html
.. _suiteview: https://github.com/rochefort-lab/fissa/blob/master/examples/Suite2p%20example.ipynb
.. _suitedown: https://raw.githubusercontent.com/rochefort-lab/fissa/master/examples/Suite2p%20example.ipynb

This notebook can also be run on your own machine.
To do so, you will need to:

0.  If you want to run the Suite2p notebook, you'll have to install everything
    into a conda environment, as per their `installation instructions <install_suite2p_>`_.
    Note that this notebook was tested with Suite2p version 0.10.0
    
1.  Install fissa with its plotting dependencies ``pip install fissa[plotting]``.

2.  Download `a copy of the repository <download_repo_>`_, unzip it and browse
    to the examples_ directory.

3.  Start up a Jupyter notebook server to run our notebooks ``jupyter notebook``.

If you're new to Jupyter notebooks, here is `an approachable tutorial`_.

.. _install_suite2p: https://mouseland.github.io/suite2p/_build/html/installation.html
.. _download_repo: https://github.com/rochefort-lab/fissa/archive/master.zip
.. _examples: https://github.com/rochefort-lab/fissa/tree/master/examples
.. _an approachable tutorial: https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook


License
-------

Unless otherwise stated in individual files, all code is Copyright (c)
2015–2021, Sander Keemink, Scott Lowe, and Nathalie Rochefort. All rights
reserved.

This program is free software; you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation; either version 3 of the License, or (at your
option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General
Public License for more details.

You should have received a copy of the GNU General Public License along
with this program. If not, see http://www.gnu.org/licenses/.
