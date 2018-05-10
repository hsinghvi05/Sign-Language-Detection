# Sign-Language-Detection
American Sign Language Recognizer

Libraries: See the code for required libraries.
___________________________________________________________________________

"Train.py":

	1. Our final trained model is already provided "keras.FINAL_MODEL4".

	2. If model is not present, create model using this file (Needs Dataset).
		dataset:
				A:
					A_1.jpg
					..
					..
					A_200.jpg
				B:
				..
				..
				Z:
	   To run-> 'python3 train.py'
_____________________________________________________________________________

"Run.py":

	1. Run using 'python run.py <index>'
		Index: 0 for default camera, 1 for external camera.
	2. Controls: 
		s	: Toggle hand band detection (green band on wrist).
			  Value can be ajusted using trackbar.
		d	: Toggle contour for debugging band detection.
		ijkl: moving the band box in corresponding direction.
	3. Use trackbar for adjusting the HSV values for band color detection.

_____________________________________________________________________________
