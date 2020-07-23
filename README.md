# License-plate-detection
Number Plate Recognition is a computer system that recognizes any digital image automatically on the number plate. This system includes various operations like taking pictures, localizing the number pad, truncating characters and OCR from alphanumeric characters. The main purpose of this system is to design and develop effective image processing techniques and algorithms to localize the license plate in the captured image, to divide the characters from the number plate and also to identify each character of the segment by using the Open Computer Vision Library. A rear image of the vehicle’s number plate is captured and processed using various algorithms. 

SOFTWARE REQUIREMENTS:
Environment to run python .Eg,Spyder,python ide,etc.
OpenCV for image processing.
Tesseract-OCR for character recognition

PROPOSED METHOD:.
The proposed ANPR method makes use of python OPENCV for image processing where the image is converted into a grayscale followed by edge detection methods to find the number plate.We then apply character recognition using pytesseract to get the license plate number.It is stored in a csv form .

1.	Read the original image
2.	Resize the image
3.	Convert it to grayscale.
4.	Apply Bilateral Filter.
5.	Identify and store the Canny edges.
6.	Find the contours in from the edges detected and sort the top 30 contours.
7.	Get the perimeter of each contour and select those with 4 corners.
8.	Mask all other parts of the image and show the final image.
9.	Read the text using Tesseract OCR.
10.	Append to csv file

