# Colour-Detection

Used masking to find out the dominant colour in a photo clicked using the PiCam. Works on the Raspberry Pi directly. Algorithm :

Import image.
FInd the total no. of pixels by multiplying width and height.
Mask the image in colours of ranges (RED, GREEN, BLUE)
Calculate the no. of non zeros for each specific colour.
Compare the non zeros of each specific colour to find the highest colour density.
Speech output the dominant colour in the picture.
