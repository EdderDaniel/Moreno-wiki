.. Moreno lab documentation master file, created by Daniel Diaz

Welcome to the Moreno lab Wiki v0.0.1!
=====================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   getting_started
   computational_resources
   slurm
   search

Getting started
===============

.. include:: getting_started.rst


Computational resources
=======================

.. include:: computational_resources.rst


SLURM
=====

This section explains how to use SLURM in the Moreno lab cluster.

Getting your account
--------------------

Steps to request and activate a new SLURM account.

Account setup
~~~~~~~~~~~~~

Instructions for setting up your environment (modules, conda, environment variables).

SSH access
~~~~~~~~~~

How to log in to the cluster via SSH.

Submitting jobs
---------------

Overview of how to submit jobs to the scheduler.

Batch jobs with sbatch
~~~~~~~~~~~~~~~~~~~~~~

Writing and submitting batch scripts.

Interactive jobs with srun
~~~~~~~~~~~~~~~~~~~~~~~~~~

Running commands interactively on compute nodes.

Job arrays
~~~~~~~~~~

Submitting multiple jobs efficiently using job arrays.

Monitoring and managing jobs
----------------------------

How to check job status and manage your jobs.

Checking job status
~~~~~~~~~~~~~~~~~~~

Using `squeue`, `sacct`, and other commands.

Canceling jobs
~~~~~~~~~~~~~~

How to stop jobs with `scancel`.

Resource management
-------------------

How to request CPUs, memory, GPUs, and control job runtime.

Partitions and queues
~~~~~~~~~~~~~~~~~~~~~

Understanding lab-specific partitions and queues.

Best practices
--------------

Tips for efficient and fair use of SLURM resources.



Search
======

.. include:: search.rst


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
