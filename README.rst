#基于PyCUDA调用GPU系列接口的Python库Scikits.Cuda
.. -*- rst -*-

..  image:: https://raw.githubusercontent.com/lebedov/scikit-cuda/master/docs/source/_static/logo.png
   :alt: scikit-cuda

Package Description
-------------------
scikit-cuda provides Python interfaces to many of the functions in the CUDA
device/runtime, CUBLAS, CUFFT, and CUSOLVER libraries distributed as part of
NVIDIA's `CUDA Programming Toolkit <http://www.nvidia.com/cuda/>`_, as well as
interfaces to select functions in the free and standard versions of the `CULA
Dense Toolkit <http://www.culatools.com/dense>`_.  Both low-level wrapper
functions similar to their C counterparts and high-level functions comparable to
those in `NumPy and Scipy <http://www.scipy.org>`_ are provided.

.. image:: https://zenodo.org/badge/doi/10.5281/zenodo.40565.svg
    :target: http://dx.doi.org/10.5281/zenodo.40565
    :alt: 0.5.1
.. image:: https://img.shields.io/pypi/v/scikit-cuda.svg
    :target: https://pypi.python.org/pypi/scikit-cuda
    :alt: Latest Version
.. image:: https://img.shields.io/pypi/dm/scikit-cuda.svg
    :target: https://pypi.python.org/pypi/scikit-cuda
    :alt: Downloads
.. image:: http://prime4commit.com/projects/102.svg
    :target: http://prime4commit.com/projects/102
    :alt: Support the project
.. image:: https://www.openhub.net/p/scikit-cuda/widgets/project_thin_badge?format=gif
    :target: https://www.openhub.net/p/scikit-cuda?ref=Thin+badge
    :alt: Open Hub

Documentation
-------------
Package documentation is available at
`<http://scikit-cuda.readthedocs.org/>`_.

Development
-----------
The latest source code can be obtained from
`<https://github.com/lebedov/scikit-cuda>`_.

Citing
------
If you use scikit-cuda in a scholarly publication, please cite it as follows: ::

    @misc{givon_scikit-cuda_2015,
        author       = {Lev E. Givon and
                        Thomas Unterthiner and
                        N. Benjamin Erichson and
                        David Wei Chiang and
                        Eric Larson and
                        Luke Pfister and
                        Sander Dieleman and
                        Gregory R. Lee and
                        Stefan van der Walt and
                        Teodor Mihai Moldovan and
                        Fr\'{e}d\'{e}ric Bastien and
                        Xing Shi and
                        Jan Schl\"{u}ter and
                        Brian Thomas and
                        Chris Capdevila and
                        Alex Rubinsteyn and 
                        Michael M. Forbes and
                        Jacob Frelinger and 
                        Tim Klein and
                        Bruce Merry and
                        Lars Pastewka and
                        Steve Taylor and
                        Feng Wang and
                        Yiyin Zhou},
        title        = {scikit-cuda 0.5.1: a {Python} interface to {GPU}-powered libraries},
        month        = December,
        year         = 2015,
        doi          = {10.5281/zenodo.40565},
        url          = {http://dx.doi.org/10.5281/zenodo.40565},
        note         = {\url{http://dx.doi.org/10.5281/zenodo.40565}}
    }

Authors & Acknowledgments
-------------------------
See the included `AUTHORS`_ file for more information.

.. _AUTHORS: docs/source/authors.rst

Related
-------
Python wrappers for `cuDNN <https://developer.nvidia.com/cudnn>`_ by Hannes 
Bretschneider are available `here
<https://github.com/hannes-brt/cudnn-python-wrappers>`_.

License
-------
This software is licensed under the 
`BSD License <http://www.opensource.org/licenses/bsd-license.php>`_.
See the included `LICENSE`_ file for more information.

.. _LICENSE: docs/source/license.rst
