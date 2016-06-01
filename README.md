Python Wrapper for Hilbert–Huang Transform MATLAB Package
=========================================================

HHTpywrapper is a python interface to call Hilbert–Huang Transform (HHT) MATLAB package and plot results by Matplotlib.
HHT is an empirical method to decompose a signal into basis components, called intrinsic mode functions (IMFs), based on the signal itself, and transform these components into instantaneous frequencies and amplitudes as functions of time. HHT has found many applications in different scientific and engineering fields, and it work well for signals generated by non-stationary and non-linear processes.

Requirements
------------
- Python
- MATLAB
- Numpy
- Scipy
- Matplotlib
- [pymatbridge](https://github.com/arokem/python-matlab-bridge) (A simple Python => MATLAB(R) interface and a matlab magic for ipython)
- [HHT MATLAB package](http://rcada.ncu.edu.tw/research1.htm) (Please run downloadHHTpackage.py first)
- [pyunpack](https://pypi.python.org/pypi/pyunpack) and [patool](http://wummel.github.io/patool/) (For extracting the .zip/.rar HHT MATLAB package files)

Usage
-----
- Run downloadHHTpackage.py to download HHT MATLAB package.
- For time series analysis: set the parameters in main1d.py and run it.
- For image analysis: set the parameters in main2d.py and run it.
- You can modify the plot functions in HHTplots.py.

Important Links
---------------
- [Research Center for Adaptive Data Analysis](http://rcada.ncu.edu.tw/intro.html)
- [References of HHT](http://rcada.ncu.edu.tw/research1_clip_reference.htm)

Other HHT-related Python Codes
---------------
- [PyHHT](https://github.com/jaidevd/pyhht) ; [PyHHT’s documentation](http://pyhht.readthedocs.io/en/latest/index.html) (by Jaidev Deshpande)
- [pyeemd](http://pyeemd.readthedocs.io/en/latest/) (by Perttu Luukko)
- [Python implementation of EMD/EEMD](https://laszukdawid.com/codes/) (by Dawid Laszuk)

Authors
-------

* [Yi-Hao Su](https://github.com/YihaoSu) (yhsu@astro.ncu.edu.tw) <br>
HHTpywrapper is my project during the [Astro Hack Week 2015](http://astrohackweek.github.io/). Welcome any contributions and suggestions!
