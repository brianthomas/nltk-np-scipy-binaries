# Ubuntu textmining binaries

Ubuntu compiled binaries for Python textmining in support of a Heroku buildpack.

# About

Most of these packages were compiled on a virtual machine that matched Heroku's
runtime environment. The virtual machine ran Ubuntu 14.04 LTS.

For the 14.04 packages the Python interpreter used to compile these packages was 
Python 3.4.3.

This project also includes `npscipy.tar.gz`, which contains compiled runtime
libraries for BLAS, LAPACK, ATLAS, and Fortran, which are needed by NumPy and
SciPy at runtime.

For older binaries, please take a look at https://github.com/dbrgn/npscipy-binaries
or https://github.com/thenovices/npscipy-binaries

