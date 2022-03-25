|Binder|

FISSA Suite2p Example
=====================

In the notebook we provide an example workflow to combine the `FISSA <fissa_>`_ and `Suite2p <suite2p_>`_ methods.

This repository mainly functions to provide environment files to run this notebook on Binder.
For the most up-to-date code and extensive documentation on FISSA, see the `FISSA <fissa_>`_ repository.

You can `view <suitehtml_>`_ the notebook on GitHub, `download <suitedown_>`_ it to your local machine, or interact with it in your web browser on `Binder <suitebind_>`_.
Note that launching a Binder session can take 10 minutes.

.. _fissa: https://github.com/rochefort-lab/fissa
.. _suite2p: https://suite2p.readthedocs.io/
.. _suitebind: https://mybinder.org/v2/gh/rochefort-lab/fissa-suite2p-example/v0.7.x?filepath=Suite2p%20example.ipynb
.. _suiteview: https://github.com/rochefort-lab/fissa-suite2p-example/blob/v0.7.x/Suite2p%20example.ipynb
.. _suitedown: https://raw.githubusercontent.com/rochefort-lab/fissa-suite2p-example/v0.7.x/Suite2p%20example.ipynb

This notebook can also be run on your own machine.
To do so, you will need to:

1.  Download `a copy of this repository <download_repo_>`_, unzip it, and cd into the ``fissa-suite2p-example`` directory.

2.  Create a new conda environment with ``conda env create --file .binder/environment.yml``.

3.  Activate the environment with ``conda activate suite2p-fissa``.

4.  Start up a Jupyter notebook server to run our notebooks ``jupyter notebook``.

If you're new to Jupyter notebooks, here is `an approachable tutorial`_.

.. _download_repo: https://github.com/rochefort-lab/fissa-suite2p-example/archive/v0.7.x.zip
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


.. |Binder| image:: https://mybinder.org/badge_logo.svg
   :target: suitebind_
   :alt: Open in Binder
