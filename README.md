The most important methods used in this project include:

cv2.VideoCapture(): This method is used to capture video frames from the webcam.

cv2.cvtColor(): Used to convert color spaces, in this case, from BGR to HSV.

cv2.inRange(): This method creates a mask of pixels that fall within a specified color range.

Image.fromarray(): From the Pillow library, this method converts a NumPy array (in this case, the mask) to a Pillow image.

Image.getbbox(): Used to obtain the bounding box of detected objects.

cv2.rectangle(): Draws a rectangle on the original frame to represent the bounding box.

cv2.imshow(): Displays the frame with bounding boxes in real-time.

cv2.waitKey(): Waits for a key press to exit the program loop and close the window.

These methods collectively form the core functionality of the color detection project, enabling real-time detection and visualization of yellow objects captured by the webcam.
