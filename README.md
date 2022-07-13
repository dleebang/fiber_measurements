# fiber_measurements
Automation of muscle fiber measurements

This Python, Jupyter script, was written to automate extraction of measurements of curved line structures (in this case, muscle fibers). The script first takes a scale with known distance and takes it as calibration for real size measurements. Then, the algorithm implements some functions from the openCV module to transform the image (e.g. erode, dilatation, binarization, skeletonization and contour finding) so it will be able to take the length of the line structures in pixels to be converted to centimeters. 

The last part of the script is dedicated to processing the storage of those extracted measurements into a dataframe, while dealing with specific filenames.
