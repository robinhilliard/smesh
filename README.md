
[![Build Status](https://travis-ci.org/tpaviot/smesh.png?branch=master)](https://travis-ci.org/tpaviot/smesh)

Description
-----------

A complete OpenCascade based MESH framework. Note this is not the original SALOME SMESH project but an effort to create a standalone mesh framework based on the existing one from SALOME project. This is a fork of the salomesmesh project available at:
http://sourceforge.net/projects/salomesmesh/ (Original project by Fotis Soutis). This fork is intended for a use in the pythonocc project.

We use the following online resources:
  * Sources
       https://github.com/tpaviot/smesh
  * Bug tracker
       https://github.com/tpaviot/smesh/issues
  * Mailing list
       http://groups.google.com/group/smesh-dev/about
  * Travic-CI
       https://travis-ci.org/tpaviot/smesh

Just ask @tpaviot (tpaviot@gmail.com) for a request regarding write access to the repository.

How to create a local copy of the repository?
---------------------------------------------

    git clone git://github.com/tpaviot/smesh.git


How to stay up to date with latest developements?
-------------------------------------------------

    cd smesh
    git pull

Build - Install
---------------

For both OSX, Linux and Windows (please use Mingw on Windows), the instructions are the same.

Requirements
------------
  * a c++ and a fortran compiler 

  * cmake 2.8 or higher

  * oce 0.16

Build
-----

    $ mkdir cmake-build
    $ cd cmake-build
    $ make
    $ make install

Install binaries on Ubuntu 14.04
--------------------------------
A linux ppa is available at launchpad. To install smesh, just:

    $ sudo add-apt-repository ppa:freecad-maintainers/oce-release -y
    $ sudo add-apt-repository ppa:tpaviot/smesh -y
    $ sudo apt-get update -q
    $ sudo apt-get install smesh
