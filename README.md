# Image_Processing

The code assumes a dark particle with a white background

Input files must be in the following format: filename.framerate.filetype (e.g. sphere_test.500.mov)

For the particle tracking, the code assumes the particle shape can be defined by a bounding rectangle. If the particle in use can't be defined by a bounding rectangle, the angle values will be invalid. The vertical and horizontal position should still be valid unlesss the rotation of the particle causes the centroid of the visible area to significantly shift 

For the gaussian kernel test, the input text file is a column of values

10X20newtank1.data is an example folder that shows the format of the input text file for all the code
