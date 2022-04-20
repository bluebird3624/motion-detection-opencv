# motion-detection-opencv
using opencv to detect motion by comparing previous and current frames.
The absdiff() method gives the absolute value of pixel intensity differences of two frames used to dettect change and thus motion 
The THRESH_BINARY method paints the background in black and motion in white thee dilate() method removes all the gaps in between 
Using contours, we can find the white images in the black background.
using the findCountours() method we detect contuours and it returns contours and hirachy 
We use boundingRect() to retrieve the rectangle bounds and the rectangle() function to draw the rectangle onto frame1.
