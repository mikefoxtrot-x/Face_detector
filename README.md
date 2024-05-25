# Face_detector V1.1
  A python program for detection of human faces. It uses an OpenCV library for detection of faces. First test image is saved in the same folder. Then this colored pixel image is converter to B&W or grayscale image. Because the model is trained to work on grayscale pixels. OpenCV can do this too. No need to write external functions for this. Then this grayscaled image is fed into Algorithm. Basically this model finds the coordinates in which human face lies. once these coordinates are found, we draw a rectangle from these coordinates. And superimpose this rectangle over the test image. Thus, human face is detected.

  
#Limitations
	This program works on human faces only.
	Sometimes it rectangles hands too.
  	Works on single image only.
	Image must be downloaded/present in same folder.
 	Not GUI friendly, requires Terminal/VSCode.
