# Optical-Character-Recognition-OCR-
1. Important Python libraries are being installed -
    cv2
    matplotlib
    numpy 
    imutils    #Used for Image Processiong
    easyocr    #Used for Character Recognition in image
    
2. Importing the image in Gray Scale format (single layer) and used some morphological process and edge detection techniques

3. Now we look for Contours which have 4 sides, basically we are looking for the number plate.

4. Using the EasyOCR Library we search the Characters in that contour and print it.
