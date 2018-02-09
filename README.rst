ITKVtkGlue
=================================

.. |CircleCI| image:: https://circleci.com/gh/Besler/ITKVTKGlue.svg?style=shield
    :target: https://circleci.com/gh/Besler/ITKVTKGlue

.. |TravisCI| image:: https://travis-ci.org/Besler/ITKVTKGlue.svg?branch=master
    :target: https://travis-ci.org/Besler/ITKVTKGlue

.. |AppVeyor|  image:: https://img.shields.io/appveyor/ci/Besler/itkvtkglue.svg
    :target: https://ci.appveyor.com/project/Besler/itkvtkglue

=========== =========== ===========
   Linux      macOS       Windows
=========== =========== ===========
|CircleCI|  |TravisCI|  |AppVeyor|
=========== =========== ===========

ITK is an open-source, cross-platform library that provides developers with an extensive suite of software tools for image analysis. VTK enables visualization of images in three dimension. This module converts ITK and VTK image data structures in a processing pipelining without copying the pixel buffer.

How to Build
============
1. Checkout this repository as ``ITKVtkGlue`` (note the case).
2. Create a folder named ``ITKVtkGlue-build`` (note the case) next to the repository folder.
3. `Download <https://www.vtk.org/download/>`_ and `build VTK <https://www.vtk.org/Wiki/VTK/Building>`_ in ``ITKVtkGlue-build/VTK-build``.
4. `Download <https://github.com/InsightSoftwareConsortium/ITKPythonPackage/tree/master/scripts>`_ the adequate ``*-download-cache-and-build-wheels`` script and run it from the repository folder.
