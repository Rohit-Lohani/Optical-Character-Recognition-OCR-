# Optical-Character-Recognition-OCR-
1. Important Python libraries are being installed -

 		i.   cv2
		
    	ii.  matplotlib
		
    	iii. numpy 
		
    	iv.  imutils   # Used for Image Processiong
		
    	v.   easyocr   # Used for Character Recognition in image
    
2. Importing the image in Gray Scale format (single layer) and used some morphological process and edge detection techniques
![image](https://user-images.githubusercontent.com/101550107/201488327-7cbc8b62-5b37-45c4-b16e-72dbecf8a034.png)


3. Now we look for Contours which have 4 sides, basically we are looking for the number plate.

4. Using the EasyOCR Library we search the Characters in that contour and print it.

![image](https://user-images.githubusercontent.com/101550107/201488157-e6b6a964-303d-4868-8496-08a5ea1faac9.png)

