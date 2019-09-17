# SOEM including Safety over EtherCAT (FSoE) DEMO
[![Build Status](https://travis-ci.org/OpenEtherCATsociety/SOEM.svg?branch=master)](https://travis-ci.org/OpenEtherCATsociety/SOEM)
[![Build status](https://ci.appveyor.com/api/projects/status/bqgirjsxog9k1odf?svg=true)](https://ci.appveyor.com/project/hefloryd/soem-5kq8b)

IMPORTANT
========
* The FSoE sample is for demonstration purpose only, to implement an FSoE Device one must follow applicable guidelines and sepcifications. Good start: https://www.ethercat.org/download/documents/ETG5101_V1i3i0_G_R_FSoEImplementationGuide.pdf.
* Build and run test\linux\fsoe_sample as legacy SOEM samples
* The FSoE stack is provided as a pre-built library for Linux and Windows. For more information or support for other targets please visit: https://rt-labs.com/products/safety-over-ethercat-fsoe/

BUILDING
========

Prerequisites for all platforms
-------------------------------

 * CMake 2.8.0 or later


Windows (Visual Studio)
-----------------------

 * Start a Visual Studio command prompt then:
   * `mkdir build`
   * `cd build`
   * `cmake .. -G "NMake Makefiles"`
   * `nmake`

Linux & macOS
--------------

   * `mkdir build`
   * `cd build`
   * `cmake ..`
   * `make`

ERIKA Enterprise RTOS
---------------------

 * Refer to http://www.erika-enterprise.com/wiki/index.php?title=EtherCAT_Master

Documentation
-------------

See https://openethercatsociety.github.io/doc/soem/


Want to contribute to SOEM or SOES?
-----------------------------------

If you want to contribute to SOEM or SOES you will need to sign a Contributor
License Agreement and send it to us either by e-mail or by physical mail. More
information is available in the [PDF](http://openethercatsociety.github.io/cla/cla_soem_soes.pdf).
