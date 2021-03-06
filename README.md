pyFlow - a lightweight parallel task engine
===========================================

[![Build Status][tcistatus]][tcihome]
[![Build status][acistatus]][acihome]


pyFlow is a tool to manage tasks in the context of a task dependency
graph. It has some similarities to make. pyFlow is not a program – it
is a python module, and workflows are defined using pyFlow by writing
regular python code with the pyFlow API

For more information, please see the [pyFlow website][site].

[site]:http://illumina.github.io/pyflow/

[tcistatus]:https://travis-ci.org/Illumina/pyflow.svg?branch=master
[tcihome]:https://travis-ci.org/Illumina/pyflow

[acistatus]:https://ci.appveyor.com/api/projects/status/fkovw5ife59ae48t/branch/master?svg=true
[acihome]:https://ci.appveyor.com/project/ctsa/pyflow/branch/master


License
-------

pyFlow source code is provided under the [BSD 2-Clause License](pyflow/COPYRIGHT.txt).


Releases
--------

Recent release tarballs can be found on the github release list here:

https://github.com/Illumina/pyflow/releases

To create a release tarball corresponding to any other version, run:

    git clone git://github.com/Illumina/pyflow.git pyflow
    cd pyflow
    git checkout ${VERSION}
    ./scratch/make_release_tarball.bash
    # tarball is "./pyflow-${VERSION}.tar.gz"

Note this README is at the root of the pyflow development repository
and is not part of the python source release.


Contents
--------

For the development repository (this directory), the sub-directories are:

pyflow/

Contains all pyflow code intended for distribution, plus demo code and
documentation.

scratch/

This directory contains support scripts for tests/cleanup/release
tarballing.. etc.

