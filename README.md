# XRD_cake_slices
# interprets large X-ray diffraction detector images to estimate crystal sizes in an azimuthally variant distribution
# This repository includes the datafiles used for data analysis of cement compacts and is meant to be run in Python. 
# The advantage of this repository over an analysis such as MAUD (the most powerful Reitveld refinement software out there) 
#   is that the repository is capable of looking at multiple azimuthal slices to calculate an aspect ratio of a grain. 
#   
# To use:
# 1. Load your datafile into Dioptas (http://www.clemensprescher.com/programs/dioptas)
# 2. Save the cake as a .txt, either as a 360x5000 or 90x5000 (360 for a 1 degree azimuthal slice, 90 for a 4 degree, and the 2-th or q axis is ~5000 pixels long
# 3. Input the file to np.loadtxt() from your preferred location
