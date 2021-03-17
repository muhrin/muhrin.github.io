---
layout: page
title: Codes
---

As part of my work I often bake delicious code, and I always share my recipes.  Here you will find some of the latest.

<img src="https://mincepy.readthedocs.io/en/latest/_static/logo.svg"  width=128 alt="mincePy"/>

**[`mincePy`](https://mincepy.readthedocs.io/en/latest/): Python object storage with versioning made simple**

![mincePy](https://img.shields.io/pypi/dm/mincepy?style=flat-square)
[![Documentation](https://readthedocs.org/projects/mincepy/badge/?version=latest)](https://mincepy.readthedocs.io/en/latest/?badge=latest&style=flat-square)


I created mincePy because I wanted to collaborate on scientific projects as easily as it is to work together on a Google Doc, or source code in a github repository.
MincePy uses MongoDB to let you store, find and keep versions of any Python object (numpy arrays, pandas `DataFrames`, pytorch networks, etc) in real time from anywhere in the world.


<img src="https://pyos.readthedocs.io/en/latest/_static/logo.svg" width=128 alt="pyOS"/>

**[`pyOS`](https://pyos.readthedocs.io/en/latest/): A fresh way to interact with your python objects as though they were files on your filesystem**

![pyOS](https://img.shields.io/pypi/dm/pyos?style=flat-square)
[![Documentation](https://readthedocs.org/projects/pyos/badge/?version=latest)](https://pyos.readthedocs.io/en/latest/?badge=latest&style=flat-square)

PyOS builds on mincePy to provide a bash-like shell where instead of files you have Python objects and instead of a local disk you are connected to a database.

<img src="https://kiwipy.readthedocs.io/en/latest/_static/logo.svg" width=128 alt="kiwiPy" />

**[`kiwiPy`](https://kiwipy.readthedocs.io/en/latest/): Robust, high-volume, message based communication made easy**

![kiwiPy](https://img.shields.io/pypi/dm/kiwipy?style=flat-square)
[![Documentation](https://readthedocs.org/projects/kiwipy/badge/?version=latest)](https://kiwipy.readthedocs.io/en/latest/?badge=latest&style=flat-square)
[![paper](https://joss.theoj.org/papers/10.21105/joss.02351/status.svg)](https://doi.org/10.21105/joss.02351)

KiwiPy is a high-level client for RabbitMQ.  It takes the pain out of creating robust message queues which are an essential part of any automated scientific workflow.  
Lost your connection the supercomputer?  Laptop crashed whilst running a long, multi-step, workflow?  Need to launch 10k processes and be certain that they all complete?  KiwiPy takes care of all this and more, with a minimal learning curve.

<img src="http://www.aiida.net/wp-content/uploads/2013/08/aiida-logo2.png" width="128" alt="AiiDA">

**[`AiiDA`](https://kiwipy.readthedocs.io/en/latest/): a scalable computational infrastructure for automated reproducible workflows and data provenance**



![AiiDA](https://img.shields.io/pypi/dm/aiida-core?style=flat-square)
[![Documentation](https://readthedocs.org/projects/aiida/badge/?version=latest)](https://aiida.readthedocs.io/en/latest/?badge=latest&style=flat-square)
[Main paper](https://www.nature.com/articles/s41597-020-00638-4)
[Engine paper](https://www.sciencedirect.com/science/article/pii/S0927025620305772?via%3Dihub)

I was the principal architect of the workflow engine in AiiDA, a highly-scalable and robust workflow engine for scientific workflows.  AiiDA has been used in a large number of [scientific works](https://www.aiida.net/science/) with [plugins](https://aiidateam.github.io/aiida-registry/) having been written for a large number of community codes, and best of all it's FOSS!



<img src="https://plumpy.readthedocs.io/en/latest/_static/logo.svg" width="128" alt="AiiDA">

**[`plumPy`](https://plumpy.readthedocs.io/en/latest/): A python workflows library that supports writing Processes with a well defined set of inputs and outputs that can be chained together and nested.**



![plumPy](https://img.shields.io/pypi/dm/plumpy?style=flat-square)
[![Documentation](https://readthedocs.org/projects/plumpy/badge/?version=latest)](https://plumpy.readthedocs.io/en/latest/?badge=latest&style=flat-square)

PlumPy is a key component of the AiiDA workflow engine and is used to create Processes with well-defined inputs and outputs and manage their lifecycle in a robust and dependable way.  It can be used entirely independently of AiiDA and is a perfect fit wherever a state machine with inputs, outputs and state transitions is needed, particularly where persistence (i.e. saving and loading of state) is useful.
