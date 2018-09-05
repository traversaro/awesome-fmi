# Awesome FMI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Functional Mock-up Interface (FMI) libraries, tools and resources.

Functional Mock-up Interface (FMI) is a tool independent standard to support both model exchange and co-simulation of dynamic models.
See the [official FMI website](http://fmi-standard.org/) for the official specification and more information about the FMI standard.

## Contents

- [Libraries](#section)
  - [C](#c)
  - [C++](#c-1)
  - [Python](#python)
  - [Java](#java)
- [Tools](#tools) 
- [Community](#community)


## Libraries

Libraries to import, simulate and export FMUs (Functional Mock-up Units). 

### C 
- [FMI Library](http://jmodelica.org/FMILibrary) - C library for import of FMUs. [BSD] 
- [FMU SDK](https://www.qtronic.de/en/fmusdk.html) - C library for import of FMUs. [BSD]

### C++
- [FMI++](https://sourceforge.net/projects/fmipp/) - C++ library for import and export of FMUs. [BSD]
- [FMI4cpp](https://github.com/SFI-Mechatronics/FMI4cpp) - FMI 2.0 implementation written in modern C++. [MIT]

### Python
- [PyFMI](http://www.pyfmi.org/) - Python package for loading and interacting with FMUs, based on the FMI Library. [LGPL]
- [FMPy](https://github.com/CATIA-Systems/FMPy) - Python package for loading and interacting with FMUs. It supports also the latest [System Structure and Parameterization (SSP standard)](https://www.modelica.org/projects). [BSD]
- [FMI++ Python Interface](https://pypi.python.org/pypi/fmipp) - Python interface for the FMI++ library. [BSD, BOOST]
- [SimulatorToFMU](https://github.com/LBNL-ETA/SimulatorToFMU) - Python package that allows to export a memoryless Python-driven simulation program or script as a FMU. [BSD]
- [modestpy](https://github.com/sdu-cfei/modest-py) - Python package for parameter estimation in FMUs. [BSD]

### Java
- [FMI4j](https://sfi-mechatronics.github.io/FMI4j/) - Java/Kotlin library for dealing with FMUs on the JVM platform. [MIT]
- [javaFMI](https://bitbucket.org/siani/javafmi) - Java library for import and export of FMUs. [LGPL3]

### MATLAB/Simulink
- [Simulink FMU Importing](https://mathworks.com/help/simulink/in-product-solutions.html) - Out-of-the-box official support for FMU import in Simulink. [Commercial]
- [FMI Toolbox for MATLAB/Simulink](https://www.modelon.com/products-services/modelon-deployment-suite/fmi-toolbox/) - Toolbox with support for Simulink FMU Import/Export and MATLAB FMU import. [Commercial]
- [matlab-fmu](https://sourceforge.net/projects/matlab-fmu/) - MATLAB Toolbox for Windows with support for import of FMUs for Model-Exchange and Co-Simulation as well as the export of MATLAB scripts as FMUs for Co-Simulation, based on the FMI++ library. [BSD]
- [Simulix](https://github.com/Kvixen/Simulix) - A third-party Simulink tool to generate FMUs from Simulink models using the C-API. [GPL3]


## Tools 
For the official list of tools that support FMI, check http://fmi-standard.org/tools/ . 

- [λ-Sim](https://github.com/mbonvini/LambdaSim) - Tool that converts FMU simulation models into REST APIs. [MIT]
- [FMITerminalBlock](https://github.com/AIT-IES/FMITerminalBlock) -  Two way interface between the FMI and IEC 61499-based controllers. [BSD]
- [FMU-proxy](https://sfi-mechatronics.github.io/FMU-proxy/) - Tool that allows FMUs to be accessed through language independent RPC calls using [gRPC](https://grpc.io/), [Apache Thrift](https://thrift.apache.org/) and/or [JSON-RPC](http://www.jsonrpc.org/specification). [MIT]
- [Unity-FMI-Addon](https://github.com/CATIA-Systems/Unity-FMI-Addon) - FMI support for [Unity](https://unity3d.com/), a cross-platform game engine. [BSD]
- [ROS fmi_adapter](https://github.com/boschresearch/fmi_adapter) - FMI support for [ROS](http://www.ros.org/), a flexible framework for writing robot software. [APACHE2]


## Community
- [Stack Overflow](https://stackoverflow.com/tags/fmi) - Questions related to FMI in Stack Overflow. 
- [Twitter's FMI Info and News](https://twitter.com/fmi_info) - Unofficial news account about the FMI Standard, FMI usage and FMI tools.


## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
