
=======================
sparc.parametricfitting
=======================

This Python package uses numpy to fit an OpenCMISS-Zinc generated heart mesh to a select set of fiducial markers.

Requirements
============

- Numpy

Fiducial landmarks
==================

The 0.1.0 version requires 11 manually placed fiducial points on the image data - see 'fiducial_landmarks_example.png'.

Fitting
=======

Once the fiducial landmarks are placed on the image data, run 'Rigid Fitting' so that the mesh is scaled, rotated, and trnaslated, 
then run 'Non-Rigid Fitting' to deform the mesh with respect to the heart image data.

Referencing
===========

The codes in the module sparc.parametricfitting are based on the algorithms presented in Myronenko and Song [1] and Khallaghi et al. [2].
If used in a project leading to a scientific publication, please acknowledge this fact by citing the relevant papers:


[1] Myronenko and Song., "Point set registration: Coherent point drift." Pattern Analysis and Machine Intelligence, IEEE Transactions on 32(12), 2010.

[2] Khallaghi et al., "Biomechanically Constrained Surface Registration: Application to MR-TRUS Fusion for Prostate Interventions", Medical Imaging, IEEE Transactions on 34(11), 2015.
