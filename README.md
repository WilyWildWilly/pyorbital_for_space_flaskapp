Pyorbital for my Flask app
=========

This for of the awesome pyorbital library is just a lightly customised version, adapted for use on the application I'm working on.

I'll probably adapt it to use MongoDB and my free tier Atlas cluster one day, but for now SQLite3 is more than enough.

Shoutout to the wonderful space nerds that made this happen. I was doing a lot of the work on orbital data on my own until I realised how hard it would be to convert the TEME coordinates I was getting out of SGP4 to ECEF coordinates without incurring in the CPU limits of an EC2 instance. I knwe I didn't need the whole Skyfield library, or PyEphemer. This library was the answer.

[![Build status](https://github.com/pytroll/pyorbital/workflows/CI/badge.svg?branch=main)](https://github.com/pytroll/pyorbital/workflows/CI/badge.svg?branch=main)
[![Coverage Status](https://coveralls.io/repos/github/pytroll/pyorbital/badge.svg?branch=main)](https://coveralls.io/github/pytroll/pyorbital?branch=main)
[![PyPI version](https://badge.fury.io/py/pyorbital.svg)](https://badge.fury.io/py/pyorbital)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6078954.svg)](https://doi.org/10.5281/zenodo.6078954)



This is the Pyorbital, a Python package for computing orbital parameters from TLE
files, and making various astronomical computations.

It is part of the Pytroll project: http://pytroll.org

