====
git
====

Install git either by source or by package

Tested minion OSes:
- Ubuntu 12.04.3 Server AMD64
- Ubuntu 14.04.1 LTS
- Ubuntu 15.04 Server AMD64
- CentOS release 6.6 (Final)
- Red Hat Enterprise Linux Server release 6.6 (Santiago)

Available states
================

.. contents::
    :local:

``git``
-------

Install git via the method specified in the pillar data.

``git.source``
--------------

Compiles and installs the given git version directly from source.

``git.package``
---------------

Install git from the system package repository.

``git.pkgrepo``
---------------

Sets up a package repo containing the most recent git package. Currently only used for Ubuntu git PPA.
