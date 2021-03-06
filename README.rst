JQuantLib is a free, open-source, comprehensive framework for
quantitative finance, written in 100% Java. It provides "quants" and
Java application developers several mathematical and statistical tools
needed for the valuation of shares, options, futures, swaps, and other
financial instruments.

JQuantLib is based on QuantLib, which is written in C++, aiming to be a
complete rewrite of QuantLib, offering features Java developers expect
to find. JQuantLib aims to be fast, correct, strongly typed,
well-documented, and user-friendly.

JQuantLib does its best efforts to mimic as close as possible the API
exposed by QuantLib, offering a smooth transition path for developers
and organizations willing to employ financial applications written in
Java whilst keeping commitment to high performance and low latency.

More info: http://www.jquantlib.org

Quick guide for the impatient
=============================

On a Unix-like console

::

    # branch from Github with git
    git clone http://github.com/frgomes/jquantlib

    # run demo number 9 (EquityOptions)
    cd jquantlib
    ./sbt clean samples/run     # or simply `sbt clean samples/run` if you have SBT installed

For impatient developers
========================

More info: http://www.jquantlib.org/en/latest/developersguide.html

Modules
=======

Main modules
------------

-  jquantlib -- main module, which resembles QuantLib/C++

-  jquantlib-helpers -- helper classes

-  jquantlib-contrib -- 3rd party contributions

-  jquantlib-samples -- sample code

Related software
----------------

-  jquantlib-ooplugin -- OpenOffice Calc plugin (outdated, not
   maintained)

-- Richard Gomes
