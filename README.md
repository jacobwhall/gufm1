GUFM1
=====
This package provides Python code to calculate magnetic fields of Andrew Jackson's [GUFM1](http://jupiter.ethz.ch/~cfinlay/gufm1.html) historical magnetic field model.

Details of the GUFM1 model can be found on the website, or in the paper
> Jackson, A., Jonkers, A. R., & Walker, M. R. (2000). Four centuries of geomagnetic secular variation from historical records. Philosophical Transactions of the Royal Society of London A: Mathematical, Physical and Engineering Sciences, 358(1768), 957-990.
This code was largely based off of the Fortran code *eval_field.f* found on his website, but is completely re-written in native Python.

Usage
-----
To use, simply clone the git directory, then `import gufm1` to begin using the methods.

Users should be able to be calculate fields for any year from 1590 to 1990 from the main gufm1_data.txt file, but you can also use data files from individual years downloaded directly from his website if desired.


Citations
--------
