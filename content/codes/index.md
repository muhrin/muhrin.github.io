---
title: "Codes"
description: "Open-source software projects by Martin Uhrin."
---

As part of my work I often bake delicious code, and I always share my recipes. Here are some of the latest.

<div class="projects-grid">

{{< project 
    title="milad" 
    link="https://github.com/muhrin/milad/"
    subtitle="Moment Invariants Local Atomic Descriptor"
    logo="https://raw.githubusercontent.com/muhrin/milad/develop/docs/source/img/milad_logo.svg"
    badges="![milad](https://img.shields.io/pypi/dm/milad?style=flat-square)"
>}}
Milad is a code I created as part of my research to explore ways to encode atomic environments (or any point clouds) in a rotationally invariant fingerprint that can be decoded back into the original environment (modulo global rotation.)
If that sounds like something that's up your street then check out the paper, here:

[Uhrin, M. (2021). Through the eyes of a descriptor: Constructing complete, invertible, descriptions of atomic environments](https://arxiv.org/abs/2104.09319).
{{< /project >}}

{{< project 
    title="AiiDA" 
    link="https://aiida.readthedocs.io/en/latest/"
    subtitle="a scalable computational infrastructure for automated reproducible workflows and data provenance"
    logo="https://raw.githubusercontent.com/aiidateam/aiida-core/main/docs/source/images/aiida-logo.svg"
    badges="![AiiDA](https://img.shields.io/pypi/dm/aiida-core?style=flat-square) [![Documentation](https://readthedocs.org/projects/aiida/badge/?version=latest)](https://aiida.readthedocs.io/en/latest/?badge=latest&style=flat-square)"
>}}
I was the principal architect of the workflow engine in AiiDA, a highly-scalable and robust workflow engine for scientific workflows. AiiDA has been used in a large number of [scientific works](https://www.aiida.net/science/) with [plugins](https://aiidateam.github.io/aiida-registry/) having been written for a large number of community codes, and best of all it's FOSS!

Papers:
[Uhrin et al. (2021)](http://doi.org/10.1016/j.commatsci.2020.110086), [Huber et al. (2020)](http://doi.org/10.1038/s41597-020-00638-4).
{{< /project >}}

{{< project 
    title="mincePy" 
    link="https://mincepy.readthedocs.io/en/latest/"
    subtitle="Python object storage with versioning made simple"
    logo="https://mincepy.readthedocs.io/en/latest/_static/logo.svg"
    badges="![mincePy](https://img.shields.io/pypi/dm/mincepy?style=flat-square) [![Documentation](https://readthedocs.org/projects/mincepy/badge/?version=latest)](https://mincepy.readthedocs.io/en/latest/?badge=latest&style=flat-square)"
>}}
I created mincePy because I wanted to collaborate on scientific projects as easily as it is to work together on a Google Doc, or source code in a github repository.
MincePy uses MongoDB to let you store, find and keep versions of any Python object (numpy arrays, pandas `DataFrames`, pytorch networks, etc) in real time from anywhere in the world.
{{< /project >}}

{{< project 
    title="pyOS" 
    link="https://pyos.readthedocs.io/en/latest/"
    subtitle="A fresh way to interact with your python objects as though they were files"
    logo="https://pyos.readthedocs.io/en/latest/_static/logo.svg"
    badges="![pyOS](https://img.shields.io/pypi/dm/pyos?style=flat-square) [![Documentation](https://readthedocs.org/projects/pyos/badge/?version=latest)](https://pyos.readthedocs.io/en/latest/?badge=latest&style=flat-square)"
>}}
PyOS builds on mincePy to provide a bash-like shell where instead of files you have Python objects and instead of a local disk you are connected to a database.
{{< /project >}}

{{< project 
    title="kiwiPy" 
    link="https://kiwipy.readthedocs.io/en/latest/"
    subtitle="Robust, high-volume, message based communication made easy"
    logo="https://kiwipy.readthedocs.io/en/latest/_static/logo.svg"
    badges="![kiwiPy](https://img.shields.io/pypi/dm/kiwipy?style=flat-square) [![Documentation](https://readthedocs.org/projects/kiwipy/badge/?version=latest)](https://kiwipy.readthedocs.io/en/latest/?badge=latest&style=flat-square) [![paper](https://joss.theoj.org/papers/10.21105/joss.02351/status.svg)](https://doi.org/10.21105/joss.02351)"
>}}
KiwiPy is a high-level client for RabbitMQ. It takes the pain out of creating robust message queues which are an essential part of any automated scientific workflow.
[Uhrin & Huber (2020)](https://joss.theoj.org/papers/10.21105/joss.02351).
{{< /project >}}

{{< project 
    title="plumPy" 
    link="https://plumpy.readthedocs.io/en/latest/"
    subtitle="A python workflows library for nested processes with well defined inputs/outputs"
    logo="https://plumpy.readthedocs.io/en/latest/_static/logo.svg"
    badges="![plumPy](https://img.shields.io/pypi/dm/plumpy?style=flat-square) [![Documentation](https://readthedocs.org/projects/plumpy/badge/?version=latest)](https://plumpy.readthedocs.io/en/latest/?badge=latest&style=flat-square)"
>}}
PlumPy is a key component of the AiiDA workflow engine and is used to create Processes with well-defined inputs and outputs and manage their lifecycle in a robust and dependable way.
{{< /project >}}

</div>
