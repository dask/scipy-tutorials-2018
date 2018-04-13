SciPy Tutorials 2018
====================

This repository organizes efforts to use Dask within tutorials for the SciPy
2018 conference.  Our objective is to complement existing tutorials with a
small Dask section that can show how to parallelize the algorithms and APIs
presented within the tutorial.

We expect that doing this effectively will require collaboration between a few
groups:

1.  The organizers of the tutorials who understand the domain, algorithms
    involved, opportunities for parallelism, and how to communicate effectively
    to the audience
2.  Developers with Dask expertise who may be able to help tutorial organizers
    develop parallel computing examples in some cases
3.  Developers with JupyterHub or cloud deployment expertise who can help to
    ensure that different environments are publicly available and can help
    triage issues with load during the conference.


Example Infrastructure
----------------------

Initially we are considering modeling this after the
[pangeo.pydata.org](http://pangeo.pydata.org) deployment that combines
JupyterHub, Dask, and cloud data storage.  This deployment includes
software and examples for the earth science community (NetCDF, XArray, ...) and
has had broad impact in advancing the discussion of the future of scalable
computing within that domain.  We encourage those interested to try running
examples on that infrastructure to get a sense for what a tutorial
experience might look like.  Login is publicly available with GitHub
credentials.


What to do now?
---------------

If you are organizing one of the [SciPy 2018
tutorials](https://scipy2018.scipy.org/ehome/299527/711308/) we encourage you
to raise an issue with the title of your tutorial.  The issue template has a
few questions to start discussion.


Managing Expectations
---------------------

This is intended as a collaboration between the three parties above.  However
we expect that most of the content generation will be handled by the tutorial
authors themselves.
