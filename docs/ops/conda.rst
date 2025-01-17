=========================
 Miniconda (recommended)
=========================

Install Miniconda
=================

Follow conda installation guide for your platform: https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

Configure Miniconda
===================

Add the conda-forge channel

.. code::

    conda config --add channels conda-forge

The conda-forge channel provides a multitude of community maintained packages.
Find out more about it here https://conda-forge.org/

Create the environment
======================

.. code::

    conda create --name cubeenv python=3.8 datacube

Activate the environment on **Linux** and **OS X**

.. code::

    source activate cubeenv

Activate the environment on **Windows**

.. code::

    activate cubeenv

Find out more about managing virtual environments here https://conda.io/docs/using/envs.html


Install other packages
======================

.. code::

    conda install jupyter matplotlib scipy

Find out more about managing packages here https://conda.io/docs/using/pkgs.html
