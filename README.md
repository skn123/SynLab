# SynLab

0. OVERVIEW

1D synchrosqueezed wave packet transforms (SSWPT):    
Analyzing instantaneous properties (instantaneous frequencies, phases and amplitudes) of non-linear oscillatory signals in a superposition. 

2D synchrosqueezed curvelet transform (SSCT):     
Anlayzing local properties of non-linear oscillatory textures in a superposition. 

Applications:    
Geophysics:  seismic wave field separation and ground-roll removal.    
Materials science:  atomic crystal image analysis, grain boundary and local defects identification, elastic deformation estimation.    
Art:  Canvas painting analysis for art forensics.

1. INTRODUCTION

SynLab is a collection of Matlab and MEX routines which implements 1D and 2D synchrosqueezed transforms proposed in [1]-[4]. It contains numerical examples in [2][5][6].

[1] H. Yang. Synchrosqueezed wave packet transforms and diffeomorphism based spectral analysis for 1d general mode decompositions. Applied and Computational Harmonic Analysis, (0):–, 2014.
[2] H. Yang, J. Lu, and L. Ying. Crystal image analysis using 2d synchrosqueezed trans- forms. arXiv:1402.1262 [math.NA], Submitted on 6 Feb 2014.
[3] H. Yang and L. Ying. Synchrosqueezed wave packet transform for 2d mode decompo- sition. SIAM Journal on Imaging Sciences, 6(4):1979–2009, 2013.
[4] H. Yang and L. Ying. Synchrosqueezed curvelet transform for two-dimensional mode decomposition. SIAM Journal on Mathematical Analysis, 46(3):2052–2083, 2014.
[5] H. Yang and L. Ying. Robustness Analysis of Synchrosqueezed Transforms. Preprint.
[6] H. Yang, J. Lu, W. P. Brown, I. Daubechies, and L. Ying, Quantitative Canvas Weave Analysis Using 2D Synchrosqueezed Transforms. Preprint. 

2. INSTALLING SYNLAB

run the file SetPath.m first. It will automatically add all the MATLAB codes to your MATLAB path and compile all MEX files. After this, you can run all demo codes to see how to use this tool box.

3. COPY RIGHT

SynLab is copyright reserved. For further information, please contact Haizhao Yang at haizhao@math.stanford.edu
