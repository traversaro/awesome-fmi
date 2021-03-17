# Awesome FMI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Functional Mock-up Interface (FMI) libraries, tools and resources.

Functional Mock-up Interface (FMI) is a tool independent standard to support both model exchange and co-simulation of dynamic models.
See the [official FMI website](http://fmi-standard.org/) for the official specification and more information about the FMI standard.

## Contents

- [FMI 2](#fmi-2)
  - [Libraries](#libraries)
    - [C](#c)
    - [C++](#c-1)
    - [Python](#python)
    - [Java](#java)
    - [MATLAB/Simulink](#matlabsimulink)
    - [Rust](#rust)
  - [Tools](#tools) 
- [FMI 3](#fmi-3) 
- [Community](#community)


## FMI 2 

The latest (as of March 2021) stable release of the FMI specification is `2.0.2`, released on 2020-12-23 .
You can find the text of the FMI specification 2.0.2 at https://github.com/modelica/fmi-standard/releases/tag/v2.0.2 . 
Unless noted  otherwise, the tools and libraries listed are compatible with FMI 2.

### Libraries

Libraries to import, simulate and export FMUs (Functional Mock-up Units) that support FMI 2. 

#### C 
- [FMI Library](http://jmodelica.org/FMILibrary) - C library for import of FMUs. [BSD] 
- [FMU SDK](https://www.qtronic.de/en/fmusdk.html) - C library for exporting FMUs. [BSD]

#### C++
- [FMI++](https://sourceforge.net/projects/fmipp/) - C++ library for import and export of FMUs. [BSD]
- [FMI4cpp](https://github.com/NTNU-IHB/FMI4cpp) - FMI 2.0 implementation written in modern C++. [MIT]

#### Python
- [PyFMI](http://www.pyfmi.org/) - Python package for loading and interacting with FMUs, based on the FMI Library. [LGPL]
- [FMPy](https://github.com/CATIA-Systems/FMPy) - Python package for loading and interacting with FMUs. It supports also the latest [System Structure and Parameterization (SSP standard)](https://www.modelica.org/projects). [BSD]
- [FMI++ Python Interface](https://pypi.python.org/pypi/fmipp) - Python interface for the FMI++ library. [BSD, BOOST]
- [SimulatorToFMU](https://github.com/LBNL-ETA/SimulatorToFMU) - Python package that allows to export a memoryless Python-driven simulation program or script as a FMU. [BSD]
- [modestpy](https://github.com/sdu-cfei/modest-py) - Python package for parameter estimation in FMUs. [BSD]
- [PythonFMU](https://github.com/NTNU-IHB/PythonFMU) - Framework for exporting Python code as FMUs. [MIT]

#### Java
- [FMI4j](https://github.com/NTNU-IHB/FMI4j) - Java/Kotlin library for dealing with FMUs on the JVM platform. [MIT]
- [javaFMI](https://bitbucket.org/siani/javafmi) - Java library for import and export of FMUs. [LGPL3]

#### MATLAB/Simulink
- [Simulink FMU Importing](https://mathworks.com/help/simulink/in-product-solutions.html)/[Export a Model as a Tool-Coupling FMU](https://mathworks.com/help/simulink/ug/_mw_54e936ec-2fa7-4418-be70-d99c8f91d2bd.html) - Out-of-the-box official support for FMU import and export (tool coupling) in Simulink. [Commercial]
- [FMI Toolbox for MATLAB/Simulink](https://www.modelon.com/products-services/modelon-deployment-suite/fmi-toolbox/) - Toolbox with support for Simulink FMU Import/Export and MATLAB FMU import. [Commercial]
- [matlab-fmu](https://sourceforge.net/projects/matlab-fmu/) - MATLAB Toolbox for Windows with support for import of FMUs for Model-Exchange and Co-Simulation as well as the export of MATLAB scripts as FMUs for Co-Simulation, based on the FMI++ library. [BSD]
- [Simulix](https://github.com/Kvixen/Simulix) - A third-party Simulink tool to generate FMUs from Simulink models using the C-API. [GPL3]
- [FMIKit-Simulink](https://github.com/CATIA-Systems/FMIKit-Simulink) - Import and export Functional Mock-up Units with Simulink. [BSD]

#### Rust
- [rust-fmi](https://crates.io/crates/fmi) - A Rust interface to FMUs (Functional Mockup Units) that follow the FMI Standard. [APACHE2/MIT]

### Tools 
For the official list of tools that support FMI 2, check http://fmi-standard.org/tools/ . 

- [λ-Sim](https://github.com/mbonvini/LambdaSim) - Tool that converts FMU simulation models into REST APIs. [MIT]
- [FMIGo!](http://www.fmigo.net/) - A set of tools for dealing with the FMI and SSP standards. [MIT]
- [FMITerminalBlock](https://github.com/AIT-IES/FMITerminalBlock) -  Two way interface between the FMI and IEC 61499-based controllers. [BSD]
- [FMU-proxy](https://github.com/NTNU-IHB/FMU-proxy/) - Framework that allows Functional Mock-up Units (FMUs) to be accessed through language independent RPC calls and that permits to transform a co-simulation FMU into a proxified version of the same FMU, so that each FMU can run in a separate process. [MIT]
- [Unity-FMI-Addon](https://github.com/CATIA-Systems/Unity-FMI-Addon) - FMI support for [Unity](https://unity3d.com/), a cross-platform game engine. [BSD]
- [ROS fmi_adapter](https://github.com/boschresearch/fmi_adapter) - FMI support for [ROS](http://www.ros.org/), a flexible framework for writing robot software. [APACHE2]
- [fmi_adapter_ros2](https://github.com/boschresearch/fmi_adapter_ros2) - FMI support for [ROS2](https://index.ros.org/doc/ros2/), the new version of the Robot Operating System. [APACHE2]

## FMI 3

FMI 3.0  development is currently in Alpha phase. General information on the FMI 3.0 feature list can be found in https://fmi-standard.org/faq/, and the development is ongoing on the repo https://github.com/modelica/fmi-standard . You can find the latest, automatically generated version of the FMI 3.0 alpha standard at https://fmi-standard.org/docs/3.0-dev/ .

**Warning: FMI 3.0 is still under heavy development, and most of the tools listed in the following they support it only in an experimental way. If you want stable tools, use FMI 2 for the time being.**

Some of the projects listed in the previous section also have prototypal support for FMI 3 alpha: 

- **Examples**: 
  - [Reference-FMUs](https://github.com/modelica/Reference-FMUs) : `3.0-alpha.5` examples FMUs are available, including examples for new co-simulation features such as scheduled co-simulation and early return in co-simulation.
  - [PMSFIT/FMI30TestFMUs](https://github.com/PMSFIT/FMI30TestFMUs) : Some examples FMUs based on the draft FMI 3.0 specificatiion are available, including features such as binary variables.
- **Python:** 
  - [fmpy](https://github.com/CATIA-Systems/FMPy) - As of verson `0.2.26` experimental support for FMI `3.0-alpha.5` is available.
- **Simulink:** 
  - [FMIKit-Simulink](https://github.com/CATIA-Systems/FMIKit-Simulink) - As of version `2.9` experimental support for export of FMU `3.0-alpha.5` is available.
- **Formal models**
  - [FMI-VDM-Model](https://github.com/INTO-CPS-Association/FMI-VDM-Model) - [VDM](https://en.wikipedia.org/wiki/Vienna_Development_Method) formal models for the FMI3.0 specification.

## Community

- [Stack Overflow](https://stackoverflow.com/tags/fmi) - Questions related to FMI in Stack Overflow. 
- [Twitter's FMI Info and News](https://twitter.com/fmi_info) - Unofficial news account about the FMI Standard, FMI usage and FMI tools.


## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
