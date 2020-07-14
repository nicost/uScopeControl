# uScopeControl

Development of new microscopes most often depends on concurrent software development. To identify and address common challenges and solutions in microscope control software, we assembled a small group of researchers that develop or use software to control their custom-build microscopes at the Janelia Research Campus for a two day workshop in February 2020. The outcome of the workshop was the definition of clear milestones, as well as the recognition of an involved community, much larger than the one assembled at the workshop. The White Paper linked below summarizes the major issues identified, proposes approaches to address these as a community, and outlines the next steps that can be taken to develop a framework facilitating shared microscope software development, significantly speeding up development of new microscopy systems. A video recording of the presentation by the attendees identifying their unique challenges and solutions is also available below.

**White Paper Draft:**

On arxiv: https://arxiv.org/abs/2005.00082

Or on github: https://github.com/nicost/uScopeControl/blob/master/Software%20for%20Microscopy%20Workshop%20WhitePaper.pdf

**Workshop Video Coverage:**

Plenary talk by Nico Stuurman:  https://youtu.be/JEzsy-qtcbE  
5-min presentations of all attendees (part 1/2):  https://youtu.be/N55imdegYPc  
5-min presentations of all attendees (part 2/2):  https://youtu.be/irAKA4wVf_Y



**Online resources related to open source microscope control software and attempts towards unification:**

Please expand this list and descriptions (use a Pull Request).

- [Micro-Manager](https://micro-manager.org): Open source microscope control software with a user interface written in Java and a device abstraction layer in C++ (see: [Project Overview](https://micro-manager.org/wiki/Micro-Manager_Project_Overview)). The device abstraction layer can be used in C/C++, Java (MMCoreJ_wrap.jar), and [Python](https://github.com/micro-manager/pymmcore). More than [200 "device adapters"](https://micro-manager.org/wiki/Device_Support) are available.  [Pycro-Manager](https://github.com/micro-manager/pycro-manager) is a ZeroMQ-based interface between the Micro-Manager Java layer and Python.

- [Python Microscopy environment](http://www.python-microscopy.org/): is an open-source package providing image acquisition and data analysis functionality for a number of microscopy applications.

- [MicronOxford Python Microscopy package](https://github.com/MicronOxford/microscope): Microscope hardware abstraction in Python (with separate user interface Cockpit). Alias for [Python Microscope](https://www.python-microscope.org/).

- [ScanImage](http://scanimage.vidriotechnologies.com/display/SIH/ScanImage+Home) is an open-source software application for laser scanning microscopy, electrophysiology, laser scanning photostimulation, and other physiological methods focused on neurobiology. Developed in Matlab.

- [BakingTray](https://github.com/SainsburyWellcomeCentre/BakingTray/) wrapper around the ScanImage API that provides serial section 2-photon imaging system inspired by the TeraVoxel [Economo, et al](https://elifesciences.org/articles/10566) and [MouseLight](https://github.com/MouseLightPipeline) [(Winnubst, et al)](https://www.sciencedirect.com/science/article/pii/S0092867419308426?via%3Dihub) projects. 
  
- [SciScan](https://www.cambridge.org/core/journals/microscopy-today/article/opensource-software-for-controlling-twophoton-laser-scanning-microscopes/DC9B64CA4836866115A6F812DB28237E/core-reader): LabView-based open source software for two-photon laser scanning microscopy.

- [Tormenta](https://github.com/fedebarabas/tormenta): Measurement control and analysis for super-resolution localization fluorescence microscopy.

- [ACQ4](http://www.acq4.org/) is a python-based platform for experimental neurophysiology. It includes support for patch-clamp electrophysiology, multiphoton imaging, scanning laser photostimulation, and many other experimental techniques. 

- [Python-data-acquisition](https://github.com/python-data-acquisition/meta):  Discussions concerning unifying microscope control with Python.

- [LabPy](https://github.com/LabPy/labpy-discussion/issues): Discussions about Python for lab automation.

- [Pymeasure](https://github.com/ralph-group/pymeasure/issues/53%5D): More discussions about Python and lab automation.

- [Itom](https://itom.bitbucket.io/index.html): General lab automation software in Python/QT/OpenCV.

- [Storm-Control](https://github.com/ZhuangLab/storm-control): Python based software for microscopy applications, originally designed for STORM data acquistion and then extended for MERFISH data acquisition.
