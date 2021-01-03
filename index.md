### [Home](/index) |  [Code](#code)

Hi and welcome!  My name is Martin Uhrin, I'm a computational physicist with many interests but most of my work revolves around developing and applying computational methods that help us to understand atomic structures, be they solids, molecules, clusters, etc, and how these relate to their properties.

My dream is to create algorithms that understand the structure/property relationship so well that they can propose brand new structures likely to have some set of desired properties. 

## Code {#code}

As part of my scientific work I often bake delicious code, and I always share my recipes.  Here's some of the latest.

<img src="https://mincepy.readthedocs.io/en/latest/_static/logo.svg"  width=128 alt="mincePy"/>

**[`mincePy`](https://mincepy.readthedocs.io/en/latest/): Python object storage with versioning made simple**

![mincePy](https://img.shields.io/pypi/dm/mincepy?style=flat-square)
[![Documentation](https://readthedocs.org/projects/mincepy/badge/?version=latest)](https://mincepy.readthedocs.io/en/latest/?badge=latest&style=flat-square)


I created mincePy because I wanted to collaborate on scientific projects as easily as it is to work together on a Google Doc, or source in a github repository.
MincePy uses MongoDB to let you store, find and keep versions of any Python object (numpy arrays, pandas `DataFrames`, pytorch networks, etc) in real time from anywhere in the world.


<img src="https://pyos.readthedocs.io/en/latest/_static/logo.svg" width=128 alt="pyOS"/>

**[`pyOS`](https://pyos.readthedocs.io/en/latest/): A fresh way to interact with your python objects as though they were files on your filesystem**

![pyOS](https://img.shields.io/pypi/dm/pyos?style=flat-square)
[![Documentation](https://readthedocs.org/projects/pyos/badge/?version=latest)](https://pyos.readthedocs.io/en/latest/?badge=latest&style=flat-square)

PyOS builds on mincePy to provide a bash-like shell where instead of files on your filesystem you have Python objects and instead of a local disk you are connected to a database.

<img src="https://kiwipy.readthedocs.io/en/latest/_static/logo.svg" width=128 alt="kiwiPy" />

**[`kiwiPy`](https://kiwipy.readthedocs.io/en/latest/): Robust, high-volume, message based communication made easy**

![kiwiPy](https://img.shields.io/pypi/dm/kiwipy?style=flat-square)
[![Documentation](https://readthedocs.org/projects/kiwipy/badge/?version=latest)](https://kiwipy.readthedocs.io/en/latest/?badge=latest&style=flat-square)
[![paper](https://joss.theoj.org/papers/10.21105/joss.02351/status.svg)](https://doi.org/10.21105/joss.02351)

KiwiPy is a high-level client for RabbitMQ.  It takes the pain out of creating robust message queues which are any essential part of any automated scientific workflow.  
Lost your connection the supercomputer?  Laptop crashed whilst running a long, multi-step, workflow?  Need to launch 10k and be certain that they all complete?  KiwiPy takes care of all this and more, with a minimal learning curve.

<img src="http://www.aiida.net/wp-content/uploads/2013/08/aiida-logo2.png" width="128" alt="AiiDA">

**[`AiiDA`](https://kiwipy.readthedocs.io/en/latest/): a scalable computational infrastructure for automated reproducible workflows and data provenance**



![AiiDA](https://img.shields.io/pypi/dm/aiida-core?style=flat-square)
[![Documentation](https://readthedocs.org/projects/aiida/badge/?version=latest)](https://aiida.readthedocs.io/en/latest/?badge=latest&style=flat-square)
[Main paper](https://www.nature.com/articles/s41597-020-00638-4)
[Engine paper](https://www.sciencedirect.com/science/article/pii/S0927025620305772?via%3Dihub)

I was the principal architect of the workflow engine in AiiDA, a highly-scalable and robst workflow engine for scientific workflows.