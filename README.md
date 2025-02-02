# Standalone Application-Installers
The need for high-fidelity modelling of radiation detectors to perform reliable detector performance optimization using Monte Carlo simulations requires to accurately simulate the light transport in the scintillator and the light collection by the photodetector. Within the “Imaging Physics Modeling and Simulation Tools” project, we implement our well validated model of crystal reflectance computed from 3D crystal surface measurement in an opensource standalone application to allow researchers to generate fully customized crystal reflectance look-up-tables (LUTs) to be used in optical Monte Carlo simulation.

The LUTDavisModel standalone is a user-friendly tool for researchers to generate LUTs in their specific scintillator-coupling-reflector configuration and to use them in GATE optical Monte Carlo simulation.

Created with App Designer (MATLAB 2019b) and packaged with MATLAB Compiler™ (MATLAB 2019b), the LUT Davis Model Standalone can be installed and used on Windows, macOS and Linux independently of MATLAB based on MATLAB Runtime. The installers for the three operating systems will be downloadable together with the standalone User’s Guide from several sources. It contains a detailed description of the app functionalities together with a description of the installation procedure which takes from few seconds to 30 minutes depending on the preinstallation of MATLAB Runtime, which can automatically be downloaded and installed.

Given a surface sample, the algorithm computes the angular distribution of reflectance and transmittance and the angular distribution of reflected and transmitted rays as a function of incidence angle (from 0° to 90°). The LUT computation includes the reflector, the coupling medium, and the photon tracking between the two interfaces. 

This algorithm allows accurate modeling of photon interactions with crystal surfaces with or without a reflector.
The Davis LUT model has been validated against experimental data and implemented in GATE v8.0.
